📚 BookNest — E-Commerce Book Store

BookNest is a modern e-commerce website designed for browsing and exploring books through a simple and user-friendly interface.

The project is developed as a web application and containerized using Docker, making it easier to build and run consistently across different environments.

✨ Features

- 📚 Browse books
- 🔍 Search and explore books
- 🛒 E-commerce-style shopping experience
- 📖 Book details and information
- 💻 Responsive web interface
- 🐳 Dockerized application
- 🚀 Easy setup and deployment

🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- React
- Docker
- Apache HTTP Server

📁 Project Structure

BookNest/
│

├── public/
├
── src/
├
── Dockerfile
├
── package.json
├
── package-lock.json

└── README.md

«The exact project structure may vary depending on the current version of the project.»

🐳 Run BookNest with Docker

1. Clone the repository

git clone https://github.com/yogitha-ns/BookNest.git

2. Open the project

cd BookNest

3. Build the Docker image

docker build -t booknest .

4. Run the container

docker run -d --name booknest-container -p 5173:80 booknest

5. Open the website

Open your browser and visit:

http://localhost:5173

🛑 Stop the Container

docker stop booknest-container

▶️ Start the Container Again

docker start booknest-container

🗑️ Remove the Container

docker rm -f booknest-container

📦 Docker Image

Build the project image using:

docker build -t booknest .

The Docker image packages the website and its required web-server environment so that the application can be run as a container.

🎯 Project Purpose

The purpose of BookNest is to develop a practical e-commerce web application while gaining hands-on experience with:

- Web development
- Frontend development
- Git and GitHub
- Docker
- Containerized application deployment

👩‍💻 Author

Yogitha N S

Computer Science and Engineering Student

GitHub: "yogitha-ns" (https://github.com/yogitha-ns)

📄 License

This project is developed for educational and portfolio purposes.
