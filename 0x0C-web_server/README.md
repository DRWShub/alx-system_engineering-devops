# ALX - General (Intellectual Property)

*    What is the main role of a web server: 
        The web  server plays an important role in storing, processing, and delivering web content to users over the internet. A web server is a computer or software 		    that stores website files (such as HTML tags, XML, images, CSS, JavaScript files etc) and responds to requests from user agents (web browsers). When a user           or browser requests a web page, the web server processes the request, retrieves the relevant files, and sends them back to the user's device. 
        Web servers handle various tasks, such as sending and receiving emails, managing file transfers, and hosting webpages. They play a crucial role in the                functioning of the World Wide Web by facilitating the communication between users' devices and the content they wish to access.
*    What is a child process: 
        A child process in computing refers to a process that is created by a parent process. This concept aids operating systems multitasking  and is often referred         to as a subprocess or subtask. Child processes are created to perform specific tasks within the context of the parent process. They inherit certain                   attributes from the parent process, such as file handles, environment variables, and memory space. Child processes can be created using system calls like             fork in Unix-like systems. 
*    Why web servers usually have a parent process and child processes:
        Web servers often utilize parent and child processes to efficiently handle incoming requests. The main server process acts as the parent process and is            responsible for listening to incoming requests. When a request arrives, the parent process spawns a child process to handle the request. This approach             allows the web server to handle multiple requests simultaneously, as each child process is dedicated to processing a single request.

        The parent process maintains control and coordination of the child processes. Child processes are lightweight and independent, which helps in achieving            better resource utilization and responsiveness. Communication between the parent and child processes is crucial for managing and distributing incoming             requests effectively.

        This architecture enables web servers to provide high performance and scalability, as multiple requests can be processed concurrently. However, proper             coordination and management of parent and child processes are essential to ensure efficient resource usage and prevent issues like process exhaustion.

        Parent-child process architecture is a fundamental concept in designing efficient and responsive web servers, contributing to their ability to handle a            large number of requests simultaneously.

*    What are the main HTTP requests

* DNS

*    What DNS stands for
*    What is DNS main role

* DNS Record Types

*    A
*    CNAME
*    TXT
*    MX
