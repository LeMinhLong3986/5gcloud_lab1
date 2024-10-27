# Nginx Kubernetes Deployment

## Mô tả
Triển khai Nginx trên Kubernetes với 2 bản sao và Service kiểu NodePort để truy cập từ bên ngoài.

## Cách thực hiện

1. Khởi động minikube:
   ```bash
   minikube start
2. Triển khai Deployment:
   ```bash
   kubectl apply -f manifests/nginx-deployment.yaml
3. Triển khai Service:
   ```bash
   kubectl apply -f manifests/nginx-deployment.yaml
4. Truy cập vào Service
   ```bash
   minikube service nginx-service
5. Truy cập vào trang web ở đường dẫn URL dưới dòng "Starting tunnel for service nginx-service" trong Terminal
