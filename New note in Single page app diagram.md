sequenceDiagram
  participant User
  participant Browser
  participant Server
  
  User -->> Browser: type text
  User -->> Browser: submit the field
  Browser -->> Server: {"content:", "date"}
