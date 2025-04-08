# De UBUNTU a WINDOWS

### Creació impressora Ubuntu

*IMPORTANT* En cas de no tenir instal·lat el Samba o el CUPS s'ha de fer un update i instal·lar els programes.

*COMENÇEM*

1. Primer de tot anirem a *localhost:631* obert des de FireFox i allà crearem una impressora seguint els passos següents.

2. Fem click al apartat de *ADMINISTRATION*

![image](https://github.com/user-attachments/assets/35ef9de1-637e-4103-be30-80c0c7304029)

3. Iniciem sessió com administrador, en aquest cas amb l'usuari isard.

![image](https://github.com/user-attachments/assets/b8f94fad-0797-4676-862d-a04c960a3963)

4. Afegim la configuració següent al apartat de *SERVER*.

![image](https://github.com/user-attachments/assets/7c3786bf-2855-4da2-a485-0f0e094ea20c)

5. Començem amb la creació de la impressora, en aquest cas volem la PDF Creator.

![image](https://github.com/user-attachments/assets/37ef5090-9913-4d1d-8bdb-d4c22cba0db7)

6. Posem el nom que volguem a la impressora, nosaltres hem posat *imp_comp* i SOBRETOT marquem la casella de "Share this printer".

![image](https://github.com/user-attachments/assets/a8705cdf-3d54-46e0-946e-5710c1c9f5c6)

7. Afegim el controlador *Generic*.

![image](https://github.com/user-attachments/assets/1f5ad29c-e548-4ffe-8416-aa79796f55c5)

8. Amb el model *Generic PDF Printer*.

![image](https://github.com/user-attachments/assets/fa67f794-146e-45e8-b200-94bde963323d)

9. Li donem a "Add printer" i ja queda afegida la impressora.

![image](https://github.com/user-attachments/assets/cefe931f-2b74-4afe-899d-a5414725cc86)

10. Connexió de la impressora amb windows

# De WINDOWS a UBUNTU

### Creació de la impressora a Windows

1. Obrim la configuració de Ubuntu i anem a l'apartat d'impressores, fem click al botó de *Afegeix una impressora*.

![image](https://github.com/user-attachments/assets/f15b11ca-0d58-4b33-8c6c-b624b94a2503)

2. Posem la comanda *smb://192.168.3.10/* i fem click a desbloqueja.

![image](https://github.com/user-attachments/assets/8783955e-4445-457a-9352-e4d18307f6ad)

3. Posem l'usuari administrador, en aquest cas l'isard.

![image](https://github.com/user-attachments/assets/f7b39da1-7d32-4285-ba67-45cc2faa068b)

4. Seleccionem l'impressora a la que volem accedir, la nostra és *PrinterW*.

![image](https://github.com/user-attachments/assets/ae0a5a3e-2b26-4328-9ab9-bb4a4722afe5)

5. Amb els seus controladors, que nosaltres hem posat, són *Generic* i *Generic Braille embosser,1.0*

![image](https://github.com/user-attachments/assets/71d90da4-1e36-43d7-b88f-6d108321892c)

6. La impressora queda afegida correctament!!

![image](https://github.com/user-attachments/assets/fff6f4d8-2c37-4739-a5b6-cb9e6ff5fe0c)


























