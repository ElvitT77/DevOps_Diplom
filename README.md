# Дипломная работа курса "DevOps-инженер с нуля"

Дипломная работа включает 3 репозитория:

1) [Ansible](https://github.com/ElvitT77/devops-diploma-ansible)
2) [APP](https://github.com/ElvitT77/devops-diploma-app)
3) [Terraform](https://github.com/ElvitT77/devops-diploma-terraform)

Для начала создается сервисный аккаунт Terraform:

<img width="974" height="375" alt="изображение" src="https://github.com/user-attachments/assets/d6c44027-c51f-4567-bc9d-f85fc0856495" />

Далее проверка:

<img width="974" height="256" alt="изображение" src="https://github.com/user-attachments/assets/49d3de74-4296-4e24-bec0-4736ec09dc1b" />

Следом узнаем id папки:

<img width="974" height="101" alt="изображение" src="https://github.com/user-attachments/assets/4e2c0180-f453-40ed-b246-3f45bb5a3832" />

Даем сервисному аккаунту роль:

<img width="974" height="318" alt="изображение" src="https://github.com/user-attachments/assets/eec37fe1-9f3b-4c1b-9a9f-0807836e48bd" />

Пользователю необходимо разрешить получать IAM-токены сервисного аккаунта:

<img width="974" height="116" alt="изображение" src="https://github.com/user-attachments/assets/4239cafe-a933-44e7-a775-302f813b2f14" />

Далее производится подготовка S3 backend. Создается статический ключ для S3:

<img width="974" height="381" alt="изображение" src="https://github.com/user-attachments/assets/5bc2d351-d617-4292-9cb1-a86501b7e7ed" />

Создаем Object Storage bucket:

<img width="650" height="558" alt="изображение" src="https://github.com/user-attachments/assets/86152b8c-eec5-4262-be2b-42a649da9270" />

## Terraform-проект:

<img width="974" height="156" alt="изображение" src="https://github.com/user-attachments/assets/842b11dd-48ed-489d-a8e5-9c34a060b75c" />

Создаем variables.tf
Создаем network.tf
Создаем security.tf
Создаем vm.tf
Создаем outputs.tf
Создаем provider.tf
Создаем backend.tf

Инициализируем Terraform:

<img width="974" height="171" alt="изображение" src="https://github.com/user-attachments/assets/6a8d2506-afec-41bd-8d89-4215585a2ee8" />

Terraform init:

<img width="974" height="264" alt="изображение" src="https://github.com/user-attachments/assets/ed8d3e44-dffc-4d14-9b8c-675f69fc7707" />
 
Проверка:

<img width="974" height="145" alt="изображение" src="https://github.com/user-attachments/assets/49dab0a9-d48d-4a4b-896b-b5ed3bccc255" />

Terraform plan:

<img width="974" height="234" alt="изображение" src="https://github.com/user-attachments/assets/bf145875-058c-4e30-86d2-ba89b7321049" />
 
Terraform apply:

<img width="974" height="567" alt="изображение" src="https://github.com/user-attachments/assets/a55c8a25-1b2f-4ab8-937d-74311fd63844" />

Проверка remote state:

<img width="974" height="264" alt="изображение" src="https://github.com/user-attachments/assets/ca509da1-3d25-4326-92f7-d066cf258c59" />

Проверка SSH:

<img width="974" height="93" alt="изображение" src="https://github.com/user-attachments/assets/7eaa64da-0605-4ff8-ae53-1e80c1ae00dc" />

<img width="761" height="134" alt="изображение" src="https://github.com/user-attachments/assets/36c0d7c3-18a8-4f14-b641-1fdc15860db7" />

## Ansible:

<img width="974" height="129" alt="изображение" src="https://github.com/user-attachments/assets/47dbf520-36ac-4ba5-a089-236fa45f6a37" />

Создаем ansible.cfg
Создаем inventory.ini

Проверка ansible:

<img width="974" height="410" alt="изображение" src="https://github.com/user-attachments/assets/1a9195ce-b909-4d33-8c81-936f4471b182" />

Создаем install-docker.yml 

Запускаем ansible:

<img width="974" height="63" alt="изображение" src="https://github.com/user-attachments/assets/8e80fca8-ca28-49c2-bec7-649be5f92e5e" />

Проверка Docker на ВМ:

<img width="974" height="318" alt="изображение" src="https://github.com/user-attachments/assets/ec1055eb-609c-4f56-a319-85427dd99b15" />

Создаем index.html
Создаем Dockerfile
Создаем .dockerignore
Создаем compose.yaml

Проверка локально:

<img width="974" height="190" alt="изображение" src="https://github.com/user-attachments/assets/9ad5a848-9019-4456-9b30-b0b2fdabf6b3" />

<img width="974" height="629" alt="изображение" src="https://github.com/user-attachments/assets/69965d79-5f2d-4280-902e-21c457b4f5fb" />

<img width="974" height="611" alt="изображение" src="https://github.com/user-attachments/assets/7db4324a-fca6-41ec-bbc8-b8a3ad72f7e5" />

Docker hub:

<img width="974" height="1133" alt="изображение" src="https://github.com/user-attachments/assets/318887d2-5424-4779-95bf-5ef087157782" />

<img width="974" height="416" alt="изображение" src="https://github.com/user-attachments/assets/b3ea624e-7c04-48b5-820a-386f9f4ccb7a" />

Подготовка compose.yaml:

<img width="974" height="80" alt="изображение" src="https://github.com/user-attachments/assets/27e4e5b9-4286-4de1-b9c1-8583e1017b53" />

Проверка:

<img width="974" height="591" alt="изображение" src="https://github.com/user-attachments/assets/82810ce2-d5af-4ca5-aead-f9a7c1e7e490" />

<img width="974" height="360" alt="изображение" src="https://github.com/user-attachments/assets/706b8760-a389-4c8d-ab07-28cc8c675639" />

<img width="974" height="642" alt="изображение" src="https://github.com/user-attachments/assets/4d975e1e-fc68-41b8-84c7-445f491e7806" />

<img width="974" height="384" alt="изображение" src="https://github.com/user-attachments/assets/9b2c2068-2263-4a40-a868-e45de894957b" />

<img width="974" height="394" alt="изображение" src="https://github.com/user-attachments/assets/7ed6606f-09cd-4d28-bd70-f1b70ce97772" />

<img width="974" height="299" alt="изображение" src="https://github.com/user-attachments/assets/62a50913-6646-48de-883b-62dd22291a37" />

## Версия 2:

<img width="974" height="696" alt="изображение" src="https://github.com/user-attachments/assets/4446722c-d3bb-4235-9d45-a517ac73bfda" />

Проверка на ВМ:

<img width="974" height="172" alt="изображение" src="https://github.com/user-attachments/assets/fe14da8c-9e35-4c66-a51e-497385e15836" />

<img width="974" height="109" alt="изображение" src="https://github.com/user-attachments/assets/3519e686-8557-4f68-93e5-8164e7735829" />

Проверка Terraform:

<img width="974" height="216" alt="изображение" src="https://github.com/user-attachments/assets/462fcf8b-bdd6-4d24-b964-12a4e1c0f295" />

<img width="974" height="244" alt="изображение" src="https://github.com/user-attachments/assets/8bd8a337-f0a2-4427-a1e4-979946e1559f" />

<img width="974" height="581" alt="изображение" src="https://github.com/user-attachments/assets/c3caeee7-b7fc-4ccb-a558-07cf4a25d7b3" />

<img width="974" height="63" alt="изображение" src="https://github.com/user-attachments/assets/b346f6b3-faaa-4d47-9c6f-e827800892da" />

<img width="974" height="367" alt="изображение" src="https://github.com/user-attachments/assets/692632b6-9e4e-49c3-9ff4-17db5088854e" />

При повторном запуске:
Terraform apply -> Получение IP ВМ -> Прописывание IP в inventory.ini
Запуск

<img width="974" height="558" alt="изображение" src="https://github.com/user-attachments/assets/6962a271-2966-4dd7-af18-c3d6fb2185e3" />

После обновляется secrets на GitHub
