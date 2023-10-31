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
  * [Build Steps ](https://drive.google.com/file/d/1OEZdP7H8iZYoTJAoXJbM58pUEKujEHSg/view?usp=sharing)
- результаты выполнения сборки:
  * [Dasboard](https://drive.google.com/file/d/1OPBwzds_44eg2m1VIvPuPzNBmhDNQzHP/view?usp=sharing)
  * [Nexus repository](https://drive.google.com/file/d/1OYpwaoRuHMblfpf-aaShVHDB4SmSgjbB/view?usp=sharing)

---

### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
1. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---
