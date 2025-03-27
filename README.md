Link Video : https://drive.google.com/drive/folders/1S57YgFgH2Wiu9Zc9nXTdgYP836MoOQPQ?usp=drive_link

Penerapan Project Kubernetes

- jalan kan minikube : minikube start
- untuk memastikan kubernetes sudah berjalan ketik perintah kubectl cluster info
- lalu buat file deployment YAML
- terapkan deployment ke dalam kubernetes dengan mengetik perintah kubectl apply -f namaskrip.yml
- lalu cek status pod dengan mengetik perintah kubectl get pods <- kode ini akan menampilkan beberapa cluster yang berhasil running
- selanjut nya buat skrip service sesuai dengan project sebegai conton membuat file service.yml di dalam direktori k8s kubernetes
- jika service sudah di buat terapkan skrip dengan mengetik perintah kubectl apply -f namaskrip-service.yaml
- lalu cek service yang berjalan dengan mengetik perintah kubectl get svc
- setelah itu untuk mendapatkan url service ketik perintah minikube service product-service --url
- jika ingin melihat LOGS untuk masing masing cluster ketik perintah kubectl logs -f <nama-pod>
- jika ingin menghapus deployment ketik perintah kubectl delete deployment nama-service

Eureka Server – Service Discovery untuk komunikasi antar layanan
✅ API Gateway – Entry point untuk mengatur trafik request
✅ Product, Order, Payment & Customer Service – Modul independen dengan database masing-masing
✅ RabbitMQ – Event-driven communication antar layanan
✅ MySQL Database – Penyimpanan data terstruktur untuk tiap layanan
✅ Kubernetes Deployment – Semua layanan dikemas dalam container dan dideploy ke Kubernetes

Happy Ngoding ^_^




