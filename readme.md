Задача 1

https://hub.docker.com/repository/docker/sergey1199/custom-nginx/general


Задача 2

<img width="1362" height="619" alt="Задача 2" src="https://github.com/user-attachments/assets/22af7ed4-865a-4b29-801f-f4e3ec12584f" />


Задача 3

<img width="1389" height="985" alt="Задача 3 4" src="https://github.com/user-attachments/assets/5d73e71d-00d7-4f99-bbc9-e49042c0ab6c" />
<img width="1514" height="1028" alt="Задача 3 3" src="https://github.com/user-attachments/assets/f502fe63-1390-4b20-96a8-e9911633c37e" />
<img width="1840" height="1032" alt="Задача 3 2" src="https://github.com/user-attachments/assets/386e7a70-bc7f-433d-9fcd-2c1e3bfa275c" />
<img width="1423" height="633" alt="Задача 3 1" src="https://github.com/user-attachments/assets/41d2a41a-cfb5-4e5f-a1e4-2e777fdc5605" />


Задача 4

<img width="1562" height="1024" alt="Задача 4(1)" src="https://github.com/user-attachments/assets/5cea0268-8c9c-4758-b83b-d12c7994a479" />

<img width="941" height="181" alt="Задача 4(2)" src="https://github.com/user-attachments/assets/be5afabe-3146-435a-9c38-e73a3ae3f463" />



Задача 5

<img width="1579" height="1018" alt="Задача 5(1)" src="https://github.com/user-attachments/assets/7a375179-defe-4dc7-a05e-a4cf7fcac81d" />
<img width="1376" height="1025" alt="Задача 5(2)" src="https://github.com/user-attachments/assets/32c1a42e-25cf-4b75-8e28-70f848b1d9c5" />
<img width="1818" height="686" alt="Задача 5(3)" src="https://github.com/user-attachments/assets/34dd1d99-e4b9-40f5-8f12-55a7cff54a8b" />
<img width="713" height="870" alt="Задача 5 Portainer" src="https://github.com/user-attachments/assets/3a24048f-2357-420e-b8d0-947931d8f6b9" />


[compose.yaml](https://github.com/user-attachments/files/24141849/compose.yaml)
include:
  - docker-compose.yaml

version: "3"
services:
  portainer:
    network_mode: host
    image: portainer/portainer-ce:latest
    volumes:
      - /var/run/docker.sock:/var/run/docker.sock
