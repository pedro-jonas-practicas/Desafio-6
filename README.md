# Desafio-6
En este repositorio se encuentra el desarrollo del TP 6 con Ansible.

Este playbook instala un servidor web apache desde cero, configurando la página de inicio y cambiando el correo del administrador
webmaster.

Primero posicionarnos en nuestro controlador Ansible en la ruta deseada:

git clone https://github.com/pedro-jonas-practicas/Desafio-6.git

Luego de haber modificado la IP de nuestro nodo servidor, ejecutar el playbook:

ansible-playbook -i inventory.ini main.yml


