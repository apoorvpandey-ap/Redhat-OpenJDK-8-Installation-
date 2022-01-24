# Redhat-OpenJDK-8-Installation-                                                                 
## video link  https://youtu.be/6mKsNMrwWb0


# List

- [ ] 1.  Download WinSCP 
- [ ] 2.  Set Environment 
- [ ] 3.  Integrate your Linux login Id, Password in WinSCP for connection
- [ ] 4.  Write a batch file 
- [ ] 5.  Run Script
### 1.  Download WinSCP
==>  [ Link ](https://github.com/apoorvpandey-ap/WinSCP/issues/1)

### 2.  Set Environment Variables 
==> 
![image](https://user-images.githubusercontent.com/66588814/150748252-9fdf76ba-e473-47f8-8365-785838c3c3a1.png)

### 3.  Integrate your Linux login Id, Password in WinSCP for connection
==> 
![image](https://user-images.githubusercontent.com/66588814/150748459-50437dc1-bd25-4f9a-8ab7-c9e847e6d06a.png)
Fill this with your credential 

### 4.  Write a batch script 
==>  For that, I have created two file 
1. bat
2. txt
bat file call txt file in this case 


1. save this file in .bat format

`WinSCP.exe /console /script=local2remote.txt  `
==> ex- script=local2remote.txt ===> file name

2. save this file in .txt format

```
open vdoxx@rupesh
synchronize remote "D:\test\Folder C\send_this_file_to_Other_drive" "/C:/backup/mysql test/"

```
  ex -synchronize remote "From" "To"

open vdoxx@rupesh ==> FTP address name given is WinSCP


### 5.  Run Script

Run the script 
