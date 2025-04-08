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

#### Creem el hash de bakalao_pedret

  ![image](https://github.com/user-attachments/assets/fcfdf307-d255-4dc9-99bc-31234dd1af62)


#### Creem el usuari bakalao_pedret

  ![image](https://github.com/user-attachments/assets/6833d97d-f3a5-43ba-bb27-001bf09ca1b5)


  ![image](https://github.com/user-attachments/assets/4cf2830f-006a-415f-8e74-145a0322d366)

#### Creem el hash techno_pedret

  ![image](https://github.com/user-attachments/assets/d0ba1f0c-5285-4dd5-9346-9b5208ce7e4d)


#### Creem el usuari techno_pedret

  ![image](https://github.com/user-attachments/assets/8c3f000c-8632-469d-b846-aa38c82b4576)

  ![image](https://github.com/user-attachments/assets/629c4d4f-0968-4c55-8ad9-a343ecbe5454)

#### Comprovar que els usuaris poden iniciar sesió

  - bakalao_pedret
    
    ![image](https://github.com/user-attachments/assets/e3a86ba3-4588-4f22-86d0-f098f0c414fd)

  - techno_pedret

    ![image](https://github.com/user-attachments/assets/036654e1-724b-4299-93e2-9e03132ed553)

#### Canviar data systema i comprobar si techno_pedret si pot entrar

  - Posem aquest parametres en no perque ens deixi canviar l'horari

    ![image](https://github.com/user-attachments/assets/01d4edbe-23a7-4dfc-88b5-ca431d3da6a7)

  - Canvien a dia 1 de maig
    
    ![image](https://github.com/user-attachments/assets/d799cb1a-fa94-4074-b18a-a62f42030659)

  - Comprobem que no ens deixa entrar

    ![image](https://github.com/user-attachments/assets/2a583e7b-bbfc-4d22-bdf8-6d12254a6a13)
