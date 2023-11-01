**University**: [ITMO University](https://itmo.ru/ru/) \
**Faculty**: [FICT](https://fict.itmo.ru) \
**Course**: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) \
**Year**: 2023/2024 \
**Group**: K4113C \
**Author**: PROVOTOROV ALEKSANDR VLADIMIROVICH \
**Lab**: Lab1 \
**Date of create**: 01.11.2023 \
**Date of finished**:  
1. Узнать статус контейнера: **minikube status**
2. Начать работу (в 1 раз скачивает k8s): **minikube start**
3. Применить манифест к кластеру: **kubectl apply -f .\myfirst.yaml**    
4. Создание службы типа NodePort: **minikube kubectl -- expose pod vault --type=NodePort --port=8200**
5. После создания сервиса, можно получать доступ к порту: **minikube kubectl -- port-forward service/vault 8200:8200**
6. Для вывода логов и получения токена (в конце логов): **kubectl logs vault**
7. Доступ получен ![скрин сайта](access%20gained.png)
8. Схема: [схема контейнера и сервиса в кластере](https://drive.google.com/file/d/1V_8QA6-J6dAF9exZOUe2bj_7G_C2uckO/view?usp=sharing)