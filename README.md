# Flask CI/CD Pipeline

This project demonstrates how to build a CI/CD pipeline for a simple Flask application using Docker, GitHub Actions, and CircleCI.
The pipeline automatically builds a Docker image and runs the app every time code is pushed to the repository.

# Project Structure
```
flask-ci-cd/
│── app.py
│── Dockerfile
│── requirements.txt
│── .github/
│   └── workflows/
│       └── ci.yml
│── .circleci/
│   └── config.yml
```
# Tech Stack

- Python 3.12
- Flask
- Docker
- GitHub Actions (CI/CD)
- CircleCI (CI/CD)

# Running Locally 

```
  git clone <your-repo-url>
  cd flask-ci-cd
```
```
  docker build -t flask-ci-cd .    
  docker run -p 5000:5000 flask-ci-cd
```
Open the file in `http://localhost:5000`

