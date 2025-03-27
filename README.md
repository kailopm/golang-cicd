# Introduction
This is the sample project for a Golang app with a full-stream CI/CD pipeline using AWS, Kubernetes, and others.

1. Containerizing the app (Docker)
2. Create Kubernetes Manifest
3. Set up CI using GitHub Actions
4. Set up CD using GitOps (Argo CD)
5. Create Kubernetes Cluster (EKS)
6. Set up Helm Chart for app (Different Environments)
7. Set up Ingress Controller (Expose My App)

# Go Web Application

This is a simple website written in Golang. It uses the `net/http` package to serve HTTP requests.

## Running the server

To run the server, execute the following command:

```bash
go run main.go
```

The server will start on port 8080. You can access it by navigating to `http://localhost:8080/courses` in your web browser.

## Looks like this

![Website](static/images/golang-website.png)


