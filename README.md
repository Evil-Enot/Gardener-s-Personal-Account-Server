# Сервер для личного кабинета садовода

Описание проекта на другом языке: [English](README.en.md)

В папке вы можете найти файл [ServerPersonalAccount](ServerPersonalAccount.txt), который содержит текстовую версию сервера.

Также в папке можно найти файл [Personal_Account_Gardener_API](Personal_Account_Gardener_API.cfe), являющийся расширением конфигурации 1С

## Как подключить расширение:

1. Нужно запустить 1С в режиме конфигурации:
​
<p align="center">
  <img src="/images/img1.png" alt="Запуск системы в режиме конфигурации"/>
</p>

2. Выберите профиль администратора (при желании и для удобства создайте новый профиль для взаимодействия с личным кабинетом):

<p align="center">
  <img src="/images/img2.png" alt="Выбор профиля"/>
</p>

3. При открытии конфигурации в настройке расширения конфигурации в меню: «Конфигурация -> Расширения конфигурации»:

<p align="center">
  <img src="/images/img3.png" alt="Расширение конфигурации"/>
</p>

4. Загрузите файл конфигурации, выбрав: «Конфигурация -> Загрузить конфигурацию из файла».

5. После загрузки откроется сама конфигурация:

<p align="center">
  <img src="/images/img4.png" alt="Меню конфигурации"/>
</p>

## Как опубликовать расширение на сервере:

1. Откройте меню «Публикация на веб-сервере»: «Администрирование -> Публикация на веб-сервере».
2. Затем в меню HTTP-сервисов установите флажок «Публиковать HTTP-сервисы расширения по умолчанию»:

<p align="center">
  <img src="/images/img5.png" alt="Публикация веб-сервера"/>
</p>

3.Осталось нажать на кнопку «Опубликовать», после чего можно начинать взаимодействие с сервисом