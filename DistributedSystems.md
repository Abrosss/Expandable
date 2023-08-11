A distributed system is a collection of independent computers that appear to its users as one computer. </br>
Distributed network architectures refer to a design approach where a collection of independent computers work togeher to achieve a common goal. Rather than relying on a single central server, these architectures distribute tasks, resources and data across the network to enhance performance, scalability and reliability.
One of the key benefits is improved speed and efficiency in serving large applications.

1. A request is made
2. Web server processes the file
3. Uploads to the database </br>
What if the file is too large, what if there are a lot of files? How long will it take to upload the file?
</br>
In distributed network architectures:
-Computers operate concurrently
-Computers fail independently
-Computers do not share a global clock

  Is uploading a large file to a server a good option after all? </br>
  This is what happens:
  Object storage - Rabbit MQ - Consumer - Database - API server



Resources:
- https://www.youtube.com/watch?v=CESKgdNiKJw
