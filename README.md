# config-dev-vm
Esse repositório tem como objetivo orientar a criação de uma máquina virtual linux ubuntu com as instalações e configurações mínimas que uso em meus testes e desenvolvimentos.

Links para download:

  1.💻> Oracle Virtual Box: https://www.virtualbox.org/wiki/Downloads
  
  2.🐧> Ubuntu Desktop: https://ubuntu.com/desktop

### Instale o Oracle Virtual Box
1. Crie uma nova Máquina Virtual, seguindo as instruções das imagens

![image](https://github.com/user-attachments/assets/400480fa-f93a-468d-b8cb-4988e042b8e8)

2. Aqui, as configurações dependerão da sua máquina física, mas de modo geral 6gb de memória, 2 processadores e 40gb de disco são o suficiente
   
![image](https://github.com/user-attachments/assets/65952c46-a998-4132-ac3d-b669762857f2)
![image](https://github.com/user-attachments/assets/417d26b7-a402-4303-bb18-30fcad514d38)

3. Encontre sua VM no meunú do Virtual box e inicie sua execução, ao ligar selecione a primeira opção:

![image](https://github.com/user-attachments/assets/f0c75877-2639-41cb-a8fb-86dcc49b1f03)

4. Selecione o Idioma, teclado e demais opções conforme as imagens abaixo:

![image](https://github.com/user-attachments/assets/4f926a08-4cc2-41b1-ad4b-e84c0c074202)
![image](https://github.com/user-attachments/assets/077feaf9-018a-4c30-8cc5-48d52dfd47a3)
![image](https://github.com/user-attachments/assets/8de1b6c7-c263-488a-9c3e-672af0016e83)
![image](https://github.com/user-attachments/assets/5784817a-f726-43dd-aa6e-6dea2d37a9ed)
![image](https://github.com/user-attachments/assets/3c4d521f-9584-45fc-855f-c6220898ba78)
![image](https://github.com/user-attachments/assets/806c4a6e-ca80-4ed5-8355-9718cafc0a2a)
![image](https://github.com/user-attachments/assets/febdba05-4e62-48cf-92bd-7da2ea3e9b65)
![image](https://github.com/user-attachments/assets/8b250d8f-f97f-4c89-a040-6569c263dda8)
![image](https://github.com/user-attachments/assets/11be07e5-3bbd-4d43-8db0-1690cdd43e9a)
![image](https://github.com/user-attachments/assets/56f3816a-6480-4b15-b25b-903644c8e807)
![image](https://github.com/user-attachments/assets/c5732634-fd45-4a26-9bf0-9daa67922330)

5. Instale o Sistema Operacional, quando for sugerido reinicie a VM.
6. Dispositivos > Inserir imagem de CD dos Adicionais para convidado...

![image](https://github.com/user-attachments/assets/f0810356-c455-4622-841b-1c431f542015)

7. Nas configurações da VM no seu VirtualBox, vá em Geral > Avançado:

![image](https://github.com/user-attachments/assets/8c3782f6-4ef3-4e2e-99e9-68af4db64e3e)

### Configurando o S.O e aplicativos

1. Abra o terminal e execute a sequência de comandos a baixo:

sudo apt update
sudo apt upgrade
sudo apt install build-essential gcc make perl dkms curl tcl

2. Clique na imagem do CD, abra um terminal na pasta que foi aberta para você:

![image](https://github.com/user-attachments/assets/0d84e787-b3e5-4b89-81ef-7dbdf007aff3)

3. Nesse novo terminal digite o seguinte comando: sudo ./VboxLinuxAdditions.run
4. Instale o Python executando os seguintes comandos:

    sudo add-apt-repository ppa:deadsnakes/ppa 
    
    sudo apt install python3.10-venv python3.10-dev python3.10-distutils
    
    sudo apt update
    
    sudo apt install python3.10














