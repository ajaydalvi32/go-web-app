# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

We built a CI/CD pipeline using GitHub Actions. Every push to main automatically builds a Docker image, pushes it to AWS ECR, and updates the Kubernetes deployment on AWS EKS, so the latest version is live without manual intervention.
## Running the server

To run the server, execute the following command:

```bash
go run main.go
```

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this

![Website](static/images/golang-website.png)


