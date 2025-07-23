# docker-calculator
A simple calculator app containerized with Docker

# What This App Does

- Asks the user for two numbers and an operation (+, -, *, /)
- Shows the result

# Files in This Project

- calculator.py → Python program for calculator
- Dockerfile → Instructions to create Docker image

# Steps:

1. Wrote a simple Python calculator program and saved it as `calculator.py`
2. Created a file named `Dockerfile` with instructions to run the app
3. Build the Docker Image : docker build -t calculator-app .
4. Run the Docker Container : docker run -it calculator-app
