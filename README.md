# Домашнее задание к занятию "Защита хоста" - Пергунов Д.В


### Задание 1

1. Создали нового пользователя cryptouser:

```
sudo adduser cryptouser
Adding user `cryptouser' ...
Adding new group `cryptouser' (1001) ...
Adding new user `cryptouser' (1001) with group `cryptouser (1001)' ...
Creating home directory `/home/cryptouser' ...
Copying files from `/etc/skel' ...
New password: 
Retype new password: 
passwd: password updated successfully
Changing the user information for cryptouser
Enter the new value, or press ENTER for the default
        Full Name []: cryptouser
        Room Number []: 
        Work Phone []: 
        Home Phone []: 
        Other []: 
Is the information correct? [Y/n] Y
Adding new user `cryptouser' to supplemental / extra groups `users' ...
Adding user `cryptouser' to group `users' ...
```
2. Создали нового пользователя cryptouser:
Вошли под учетной записью cryptouser, создали 5 пустых файлов (1 2 3 4 5)
Каталог до выполнения шифрования:  
![image](https://github.com/user-attachments/assets/1c267117-b903-47fd-a0db-b7e39446c84c)  
Зашифровали каталог пользователя cryptouser  
![image](https://github.com/user-attachments/assets/bee160be-ae4a-461b-aa52-159d5586bb4c)  
Каталог после выполнения шифрования:  
![image](https://github.com/user-attachments/assets/dd0e375d-934d-4b18-af30-bea31dd1e9bb)  

### Задание 2

1. Luks изначально был установлен  
2. Создали пустой раздел sbd1  
![image](https://github.com/user-attachments/assets/00f43f99-0bc8-418b-9358-d048c3b5fc67)  
3. Инициализировали LUKS  
![image](https://github.com/user-attachments/assets/d4001e46-709c-4eae-8fd4-93ca92f8dbec)  
4. Открыли зашифрованный раздел  
![image](https://github.com/user-attachments/assets/0ce6791c-9b02-4650-8c07-a1ff19d62d5a)  
5. Создали файловую систему  
![image](https://github.com/user-attachments/assets/ab32e914-dc0c-480a-b4a4-44c97961d1d0)  
![image](https://github.com/user-attachments/assets/60aa850f-2f47-4ae6-949d-6525c64c1ac3)  
6. Смонтировали зашированный раздел  
![image](https://github.com/user-attachments/assets/75d1f61b-2304-4a06-94e8-d3d957554691)  







