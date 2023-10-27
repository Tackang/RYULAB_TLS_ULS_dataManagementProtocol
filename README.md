# [RyuLab]TLS_ULS_dataManagementProtocol

This page explains how to manage Riegl TLS and ULS dataset  
https://docs.google.com/spreadsheets/d/1wb4QeWr6PL7wAuJscyQ-VGBiKfCVTcCDWBeLWDFpreo/edit#gid=0 

### 1. Upload field data to external HDD

<img src="https://github.com/Tackang/RYULAB_TLS_ULS_dataManagementProtocol/assets/121844577/008725d0-d1d2-4dcb-804b-cf0a4eb14373" width="300" height="400">  

  
 + #### HDD folder structure
```   
 📦TLS_ULS_riegl  
  ┣ 📂11GDK_TLSriegl  
  ┣ 📂12GDK_ULSriegl  
  ┣ 📂21TCK_TLSriegl  
  ┣ 📂22TCK_ULSriegl  
  ┣ 📂31HWK_TLSriegl  
  ┗ 📂32HWK_ULSriegl 
```
## 2. Process field data 
+ TLS  
  Process using RISCAN PRO 2.18
    
+ ULS  
  Process using POSPAC UAV 8.4 + RISPROCESS 1.9.3

For more detail, ask @Tackang @Yunsoo

## 3. Upload processed field data to server

+ #### Server folder path ( /esail3/Takcang/* )
```
📦esail3  
 ┗ 📂Tackang  
   ┣ 📂11GDK_TLSriegl  
   ┣ 📂12GDK_ULSriegl  
   ┣ 📂21TCK_TLSriegl  
   ┣ 📂22TCK_ULSriegl  
   ┣ 📂31HWK_TLSriegl  
   ┗ 📂32HWK_ULSriegl 
```


