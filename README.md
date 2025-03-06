# training-ansible
Creación de la máquina linux usando terraform : 

![image](https://github.com/user-attachments/assets/47b3e281-ada2-4a31-bcfa-99f6d8a6e8c0)
ip : 172.203.147.245
password: Passfabiana12@

Para emepzar con el laboratorio se debía instalar ansible
inicialmente no hay roles en install_docker así que se hace la instalación necesaria , con los comandos 

mkdir -p playbooks/roles/docker_install/{tasks,handlers,templates,files,vars,defaults}
touch playbooks/roles/docker_install/tasks/main.yml
y se edita el main.yml 

![image](https://github.com/user-attachments/assets/df0e8ce7-6e4f-4e16-b922-c5a59b2d77b5)

Entonces verificamos el install rol quedando : ![image](https://github.com/user-attachments/assets/f83d3c36-1ee4-4438-bebf-bdee622b59ef)
se edita el hosts.ini , reemplazando la ip de la maquina creada anteriormente , el usuario y la contraseña 

![image](https://github.com/user-attachments/assets/25244761-820c-45e2-b426-dcb1a2246497)

