# cloud.github.io
<hr />

<h1>Name : SMIT THAKORE </h1>

<h1>Roll Number : 21BCP370</h1>

<h1>Cloud IA2</h1>


<h3>Project Overview</h3>
This project contains a login form and an additional form for adding products. Each component of the application (frontend, backend, MySQL database) is containerized using Docker. The necessary Dockerfiles and Docker Compose configuration are provided in this repository.

<h3>Prerequisites</h3>
Make sure you have Docker installed on your system. You can download and install Docker from here.

<h3>Getting Started</h3>
1.To get started with this project, follow these steps:
  git clone https://github.com/aryan-1503/todo_db.git
2.Navigate to the project directory:
  cd your-repo
3.Build the Docker images::
  docker pull smitthakore/cloud370
# Add commands to build your Docker images for both the login form and the product form
4.Run the Docker containers using Docker Compose:
  



<h3>1. Project Download:</h3>
   - Download a project containing both frontend and backend code with a MySQL database. For example, a project with a simple form frontend, a Flask backend, and MySQL database.

<h3>2. Making Dockerfile:</h3>
   - Write Dockerfiles for frontend, backend, and database.
   - Each Dockerfile should define the necessary environment and dependencies for the respective component.
   - Ensure that the Dockerfiles correctly set up the container environment for running the frontend, backend, and database components.

<h3>3. DockerHub Repository:</h3>
   - Create a new repository on Docker Hub where you will push your Docker images.
   - Log in to Docker Hub if you haven't already.


<h3>4. Creating Images and Containers:</h3>
   - Build the Docker images for frontend, backend, and database:
     
     **docker build -t username/Reponame .**
     
     Replace `username` with your Docker Hub username and `Reponame` with the name of your repository.
   - Use Docker Compose to bring up the containers:
     
     **docker-compose up**
    


<h3>5. Log in to Docker Hub:</h3>
   - Log in to Docker Hub using the following command:
     
     docker login
    
   - Enter your Docker Hub username and password when prompted.

<h3>6. Push the Images and Containers:</h3>
   - Push your Docker images to Docker Hub using the following command:
   
     docker push username/Reponame
    
     Replace `username` with your Docker Hub username and `Reponame` with the name of your repository.


By following these steps, you should be able to build Docker images for your frontend, backend, and database components, run them as containers, and then push them to Docker Hub for deployment or sharing. Make sure to replace placeholder values like `username` and `Reponame` with your actual Docker Hub username and repository name.
