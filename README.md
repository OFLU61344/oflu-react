1-Docker Sürümü Kontrol Etme: docker --version

2-Docker Bilgi Alma: docker info

3-Docker İmajları Listeleme: docker images

4-Docker İmaj İndirme: docker pull image_name

5-Docker İmaj Silme: docker rmi image_name

6-Çalışan Docker Konteynerları Listeleme: docker ps

7-Tüm Docker Konteynerları Listeleme: docker ps -a

8-Docker Konteynerı Oluşturma: docker run image_name

9-Arka Planda Çalışan Docker Konteynerı Oluşturma: docker run -d image_name

10-Docker Konteynerını Durdurma: docker stop container_id

11-Docker Konteynerını Başlatma: docker start container_id

12-Docker Konteynerını Silme: docker rm container_id

13-Docker Konteynerına Giriş Yapma: docker exec -it container_id /bin/bash

14-Docker Konteyner Logları: docker logs container_id

15-Docker Ağları Listeleme: docker network ls

16-Docker Ağı Oluşturma: docker network create network_name

17-Docker Ağı İnceleme: docker network inspect network_name

18-Docker Ağına Bağlanma: docker network connect network_name container_id

19-Docker Ağından Ayırma: docker network disconnect network_name container_id

20-Docker İmajını Adlandırma: docker tag image_id new_image_name:new_tag

21-Docker İmajını Push Etme: docker push image_name

22-Docker İmajını Kaydetme: docker save -o save_path/image_name.tar image_name

23-Docker İmajını Yükleme: docker load -i save_path/image_name.tar

24-Docker Port Yönlendirme: docker run -p host_port:container_port image_name

25-Docker İmajını Güncelleme: docker-compose up --build
