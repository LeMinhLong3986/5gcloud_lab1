# Nginx Kubernetes Deployment

## Mô tả
Triển khai Nginx trên Kubernetes với 2 bản sao và Service kiểu NodePort để truy cập từ bên ngoài.

## Cách thực hiện

1. Triển khai Deployment:
   ```bash
   kubectl apply -f manifests/nginx-deployment.yaml
