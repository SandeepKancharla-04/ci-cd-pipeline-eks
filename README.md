# CI/CD Pipeline to Amazon EKS

This project demonstrates a GitHub Actions pipeline to:
•⁠  ⁠Build Docker images
•⁠  ⁠Push to ECR
•⁠  ⁠Deploy to EKS

## Tools Used:
•⁠  ⁠GitHub Actions
•⁠  ⁠Amazon EKS
•⁠  ⁠Docker
•⁠  ⁠kubectl

## Folder Structure:
•⁠  ⁠⁠ .github/workflows/eks-deploy.yml ⁠: CI/CD Pipeline
•⁠  ⁠⁠ k8s/ ⁠: Kubernetes manifests
•⁠  ⁠⁠ Dockerfile ⁠: Sample app container

## Steps to Use:
1.⁠ ⁠Set up AWS credentials in GitHub Secrets.
2.⁠ ⁠Modify ⁠ eks-deploy.yml ⁠ for your cluster name and region.
3.⁠ ⁠Commit and push code.

Deploy fast. Deploy often.
