![Screenshot 2025-04-09 100237](https://github.com/user-attachments/assets/fb707238-78fc-4eae-a5c4-4230bc516b24)
![Screenshot 2025-04-09 100152](https://github.com/user-attachments/assets/989442dd-e7cd-48c0-a9bf-76c7a9593552)
The screenshots illustrate successful GET requests to a RESTful API hosted at http://localhost:8080. Here's a breakdown:

1. User Summary Endpoint
Endpoint: GET /user/summary/1

Response:

json
Copy
Edit
{
  "id": "1",
  "username": "john_doe",
  "email": "john@example.com",
  "fullName": "John Doe",
  "Number of Post": 2,
  "Number of comments": 1
}
This endpoint returns a detailed summary of the user with ID 1, including:

Basic user info (username, email, full name)

Post and comment statistics (2 posts and 1 comment)

2. Post Comments Endpoint
Endpoint: GET /post/1/comments

Response:

json
Copy
Edit
[
  {
    "commentator": "Alice Smith",
    "comment": "Great tips! I will definitely try these out."
  },
  {
    "commentator": "Bob Jackson",
    "comment": "Thanks for sharing. It's important to prioritize health."
  }
]
This endpoint retrieves the list of comments for the blog post with ID 1. Each comment includes:

Commentator's name

The actual comment text

✅ Status Code
Both requests returned 200 OK, confirming the API endpoints are working as expected.
