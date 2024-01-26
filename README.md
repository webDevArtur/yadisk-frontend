# Yandex Disk Document Management App
Командная задача на CaseLab2023, Работа с API Яндекс Диска.

## Ссылка на проект

https://yadisk-deploy-uc3d.vercel.app/

## О проекте

Это приложение разработано для управления документами на Яндекс Диске. Пользователи могут просматривать, перемещать и удалять документы, а также организовывать их в категории. Приложение взаимодействует с API Яндекс Диска, используя OAuth токен для авторизации.

## Шаги настройки

### Шаг 1: Получение OAuth токена

1. Создайте аккаунт на Яндекс Диске, если у вас его еще нет.
2. Авторизуйтесь на Яндекс Диске и перейдите на страницу Полигон.
3. Нажмите кнопку "Получить OAuth-токен" для получения токена.
4. Используйте полученный токен для запросов к API Яндекс Диска.

### Шаг 2: Создание структуры папок

1. Создайте на Яндекс Диске папку "CaseLabDocuments".
2. Внутри "CaseLabDocuments" создайте папки, представляющие категории документов (например, "бухгалтерия", "университет").
3. Загрузите в созданные папки несколько документов в формате png.

### Шаг 3: Создание React приложения

1. Разработайте React приложение с следующими возможностями:
   - Просмотр списка всех документов.
   - Просмотр списка всех категорий.
   - Просмотр списка документов в конкретной категории.
   - Просмотр конкретного документа.
   - Перемещение документа из одной категории в другую.
   - Удаление документа.
   - Сохранение изменений при обновлении страницы.

2. Взаимодействуйте с сервером Яндекс Диска, используя полученный OAuth токен.

## Технологии

- Фреймворк: [React](https://reactjs.org/)
- Взаимодействие с API: [Яндекс Диск API](https://yandex.ru/dev/disk/rest/)
- Авторизация: OAuth токен

## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш-локальный-путь/yandex-disk-doc-app.git
   npm install
   npm start


![image](https://github.com/webDevArtur/CaseLab_yadisk-frontend/assets/141954990/88bc2e66-5cf9-4202-97b0-ccec83dbb726)

