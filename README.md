# cloud_network2
## Задание 1
Создал бакет  [bucket.tf](bucket.tf)  
<img width="1244" alt="Снимок экрана 2024-10-17 в 01 13 02" src="https://github.com/user-attachments/assets/2a9f7201-0d15-44ab-8b98-0f7b3dffdf72">  

Далее создал ВМ  
```
terraform init
terraform apply
Plan: 10 to add, 0 to change, 0 to destroy.
Apply complete! Resources: 10 added, 0 changed, 0 destroyed.

Outputs:

bucket_domain_name = "http://skillpropil-netology-bucket.storage.yandexcloud.net/lol.jpg"
external_load_balancer_ip = "84.201.180.247
```
Часть 2.Доступ к картинке   
<img width="946" alt="Снимок экрана 2024-10-17 в 00 41 15" src="https://github.com/user-attachments/assets/b3975e83-8b7d-44c7-8716-5a63fbe55799">  

Часть 3. Сетевой балансировщик  
<img width="1253" alt="Снимок экрана 2024-10-17 в 00 48 52" src="https://github.com/user-attachments/assets/e4331175-d37d-43e2-b962-26a84db15d26">  

Далее после удаления ВМ она восстановилась. Первый скрин - удаление ВМ. Второй - спустя 5 минут.  

<img width="1254" alt="Снимок экрана 2024-10-17 в 00 49 26" src="https://github.com/user-attachments/assets/9e3e243e-36d9-4683-b5e9-f3c04146d09e">  

<img width="1247" alt="Снимок экрана 2024-10-17 в 01 22 27" src="https://github.com/user-attachments/assets/fcd0153d-6b5e-49e9-b211-fe2251f2f375">
