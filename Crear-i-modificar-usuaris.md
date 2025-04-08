# 1.- Crear i modificar usuaris
Fer tot des de webmin

- Has de crear dos usuaris bakalao_X i techno_X on (X és el vostre cognom).
  
- Els usuaris et passaran el hash de la seva contrasenya, no la contrasenya real. (podeu fer servir openssl).

- Cada usuari tindrà un directori a home igual al seu nom d'usuari.

- Utilitzaran bash com a shell.
  
- Els usuaris estaran dins del grup que tingui el seu mateix nom i dins del grup usuaris_empresa.

- L'usuari techno no podrà fer login després del dia 31-03-2025.
  
- Comproveu que els usuaris poden iniciar sessió.

- Canvia la data del sistema (utilitzant webmin) i comprova que techno no pot iniciar sessió si estem a dia 01-04-2025.

#### Primer creem el Grup usuaris_empresa

  ![image](https://github.com/user-attachments/assets/4d7eb951-e0be-486e-beef-5fcac45b41e6)

#### Creem el hash

  ![image](https://github.com/user-attachments/assets/fcfdf307-d255-4dc9-99bc-31234dd1af62)


#### Creem el usuari bakalao_pedret

  ![image](https://github.com/user-attachments/assets/6833d97d-f3a5-43ba-bb27-001bf09ca1b5)


  ![image](https://github.com/user-attachments/assets/4cf2830f-006a-415f-8e74-145a0322d366)

#### Creem el usuari techno_pedret

