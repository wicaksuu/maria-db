# Panduan Deploy MariaDB di Rancher Fleet pada Dua Cluster Kubernetes

Panduan ini akan membantu Anda untuk melakukan deploy MariaDB menggunakan Rancher Fleet pada dua cluster Kubernetes.

## Prasyarat

1. Rancher telah terpasang dan dikonfigurasi pada kedua cluster Kubernetes.
2. Fleet telah terpasang dan dikonfigurasi pada Rancher.
3. Akses ke kedua cluster Kubernetes melalui kubectl.

## Langkah-langkah

### 1. Buat Namespace

Buat namespace `mariadb` pada kedua cluster Kubernetes.
