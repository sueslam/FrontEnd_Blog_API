# FrontEnd_Blog_API
Provide Golang API with a real UI.
Key concepts
- Pages: routes/screens (Login, Signup, Posts list, Post detail, Editor)
- API client: single module that calls backend
- Auth state: store token + user in memory/context (or localStorage for simplicity)
- Route protection: require login for editor/admin routes
