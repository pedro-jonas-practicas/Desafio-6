#Este repositorio contiene el desarrollo del Desafío 6 con Ansible.
<p>
El playbook `main.yml` instala un servidor web apache desde cero en nuestro nodo, configurando la página de inicio y cambiando el correo del administrador webmaster.
</p>

Primero posicionarnos en nuestro controlador Ansible en la ruta deseada y ejecutar:

```
git clone https://github.com/pedro-jonas-practicas/Desafio-6.git
```

Luego de haber modificado la IP de nuestro nodo servidor, ejecutar el playbook:
```
ansible-playbook -i inventory.ini main.yml
```
En caso de error, verificar la conexion ssh entre controlador y nodo.
