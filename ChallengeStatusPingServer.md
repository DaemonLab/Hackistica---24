# Challenge status Ping Server
### Description:
The SSH Server Ping and Challenge Status Checker is a tool designed for cybersecurity purposes. It allows users to ping an SSH server and retrieve the status of various challenges within a cybersecurity competition. The tool helps assess the availability and responsiveness of the SSH server while providing an overview of the status of individual challenges.
### Specification:
-   The tool should establish an SSH connection with the target server using the provided credentials (IP address, username, and password/private key).
    
-   The tool should ping the SSH server to check its availability and response time. It should display the ping statistics, including packet loss percentage, round-trip time (RTT), and average response time.
    
-   **Challenge Status Retrieval**: The tool should retrieve the status of various challenges hosted on the SSH server. It can use SSH commands or protocols (e.g., SSH sessions, SCP) to interact with the server and fetch the challenge status.
    
-   **Challenge Status Display**: The tool should present the challenge status in a clear and organized manner. It can display a list of challenges along with their respective statuses, such as "solved," "unsolved," "in progress," or "locked." The tool can provide additional details for each challenge, such as the challenge description, point value, and any relevant hints or instructions.
