# Домашнее задание к занятию «Что такое DevOps. СI/СD»

# Михалёв Сергей
### Задание 1

**Что нужно сделать:**

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins [golang](https://golang.org/doc/install).
3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).
3. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```.

### Скриншоты: 

* настройки проекта:
  * Build Steps
    
  <img src="img/First_task_img_1.png" alt="Build Steps" width="500" height="auto">
- результаты выполнения сборки:
  * Console output
    
  <img src="img/First_task_img_4.png" alt="Dasboard" width="500" height="auto">
  
  * Dasboard
    
  <img src="img/First_task_img_2.png" alt="Dasboard" width="500" height="auto">

  * Nexus repository<br>
  <img src="img/First_task_img_3.png" alt="Nexus repository" width="500" height="auto">

---

### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

### Скриншоты: 

* настройки проекта:
  * Build Steps
    
  <img src="img/Seconf_task_img_1.png" alt="Build Steps" width="500" height="auto">
- результаты выполнения сборки:
  * Console output
    
  <img src="img/Seconf_task_img_2.png" alt="Dasboard" width="500" height="auto">
  
  * Dasboard
    
  <img src="img/Seconf_task_img_3.png" alt="Dasboard" width="500" height="auto">

  * Nexus repository<br>
  <img src="img/Seconf_task_img_4.png" alt="Nexus repository" width="500" height="auto">

---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
1. Загрузите файл в репозиторий с помощью jenkins.

### Скриншоты: 

* настройки проекта:
  * Build Steps
    
  <img src="img/Third_task_img_1.png" alt="Build Steps" width="500" height="auto">
- результаты выполнения сборки:
  * Console output
    
  <img src="img/Third_task_img_2.png" alt="Dasboard" width="500" height="auto">
  
  * Dasboard
    
  <img src="img/Third_task_img_3.png" alt="Dasboard" width="500" height="auto">

  * Nexus repository<br>
  <img src="img/Third_task_img_4.png" alt="Nexus repository" width="500" height="auto">

---
