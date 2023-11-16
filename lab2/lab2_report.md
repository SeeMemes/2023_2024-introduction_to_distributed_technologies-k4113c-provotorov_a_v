**University**: [ITMO University](https://itmo.ru/ru/) \
**Faculty**: [FICT](https://fict.itmo.ru) \
**Course**: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies) \
**Year**: 2023/2024 \
**Group**: K4113C \
**Author**: PROVOTOROV ALEKSANDR VLADIMIROVICH \
**Lab**: Lab2 \
**Date of create**: 15.11.2023 \
**Date of finished**: 
1. Применить манифест к кластеру: **kubectl apply -f .\myfirst.yaml**
2. **Service** описан в [lab2.yaml](lab2.yaml), поэтому создавать его как в **lab1** не надо
3. Проброс порта: **kubectl port-forward \<pod name\> \<port\>:3000**
4. Выводы для двух контейнеров: ![cont1](cont1.png) ![cont2](cont2.png)
5. Логи ![логи](logs.png)
6. Схема: ![схема контейнера и сервиса в кластере](scheme.png)