# Project Title
Node.js SMTP (Simple Mail Transfer Protocol) Server

## Project Description
A lightweight SMTP server designed to receive, process, and log incoming email streams. Deployed on AWS EC2 and routed via Cloudflare.

## Screenshots
<img width="611" height="293" alt="ReadmeAttachment1" src="https://github.com/user-attachments/assets/90cc0974-231d-44fa-9854-1f0a0c863061" />
<img width="650" height="320" alt="ReadmeAttachment2" src="https://github.com/user-attachments/assets/7b7c52d0-d7d5-4bb1-9d2f-69767157f7a2" />
<img width="1103" height="548" alt="image" src="https://github.com/user-attachments/assets/1756e995-2b7a-4fc7-92aa-a82f602342f1" />
<img width="912" height="483" alt="image" src="https://github.com/user-attachments/assets/c6447e03-1e2e-4f9d-9823-233c57a97c05" />



## Hosted URL
This is a backend SMTP server and cannot be accessed via a web browser. To test the server, send an email to any address at this domain:  
address@aniirudh.me <br>
address@rjainil.me <br>
address@palksh.me

## Features Implemented

### Frontend
N/A (Backend-only application)

### Backend
- Listens for inbound SMTP traffic on TCP port 25.
- Captures and logs sender (onMailFrom) and recipient (onRcptTo) metadata.
- Processes raw email data streams and outputs them directly to the console.
- Executes via standard Node.js runtime attached to the active terminal session.

## Technologies/Libraries/Packages Used
- Runtime: Node.js  
- Libraries: smtp-server  
- Infrastructure: AWS EC2  
- DNS/Networking: Cloudflare  

## Local Setup

- Clone the repository: git clone [https://github.com/anirudhm2007/SMTP-server]
- Install dependencies: ```npm install smtp-server```
- Start the server: ```sudo node index.js```

  
## Team Members
1. Anirudh Madhavan   
2. Palksh Upadhyay
3. Rathwa Jainil
