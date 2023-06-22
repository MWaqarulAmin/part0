sequenceDiagram 
  participant User
  participant Browser
  participant Server
  
  User -->> Browser: open URL: https://studies.cs.helsinki.fi/exampleapp/spa
  Browser -->> Server: GET /spa
  Server --->> Browser: HTML, CSS, JS files
  Browser -->> User: Render the interface
  User -->> Browser: use the app
