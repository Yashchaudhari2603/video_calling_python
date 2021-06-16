# video_calling_python
Python based application for video calling...

Task Description 📄

📌 Create Live Streaming Video Chat App without voice using cv2 module of Python

𝐖𝐨𝐫𝐤𝐢𝐧𝐠:- Here, we have used EC2 instance as server and our local systems are clients. First, server code is run so that clients can connect to it, and then both the clients establish a connection with the server. Then client's picture is clicked by his/her local system and is being sent to the server and the server is storing the data in some variable and that data is sent to the other client by the server. And the same process goes for the other client. All this data transferring is taking place in parallel for which threading concept is used.
𝙽𝚘𝚝𝚎:- EC2 instance(server) is not clicking any picture, it is just receiving the data from the clients and sending it to each other.
