# Docker: создание и управление контейнерами
## Цель работы: 
### Изучение работы с программным обеспечением Docker для автоматизации развертывания и управления приложениями в средах с поддержкой контейнеризации.
## Ход работы: 
1. Установил Docker
2. Создал рабочую директорию
 <img width="375" height="20" alt="image" src="https://github.com/user-attachments/assets/a9419dc0-6933-4fe0-94da-8e19e2be1775" />
3. В этой же директории создали Dockerfile, и другие файлы
<img width="545" height="293" alt="image" src="https://github.com/user-attachments/assets/80b519e8-60cb-499e-aa6c-21393d49c98d" />
4. Создали образ Docker на основе созданного Dockerfil, запустили контейнер
<img width="931" height="553" alt="image" src="https://github.com/user-attachments/assets/3522339b-8c95-4ad2-9fc4-1498b7003ee3" />
5. Открыли веб-браузер и перешли по адресу http://localhost:1234/
<img width="422" height="86" alt="image" src="https://github.com/user-attachments/assets/02253a50-9470-42b0-a46d-d24843f234f0" />
6. В той же директории создали файл docker-compose.yml для развертывания этого приложения вместе с базой данных PostgreSQL, предусмотреd проброс порта 1234, а также возможность расширения или подключения сторонних сервисов при необходимости
<img width="653" height="558" alt="image" src="https://github.com/user-attachments/assets/e15f7872-c3a0-47f2-9468-5bb427253375" />
7. Далее запускаем стек через docker-copmose <img width="819" height="224" alt="image" src="https://github.com/user-attachments/assets/60c0e60a-f6b5-46ce-afea-5cd8d4497fe4" />
