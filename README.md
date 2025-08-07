# Kittygram

## Описание проекта

Kittygram — это простой, но мощный проект на Django, который демонстрирует основы работы с REST API. Этот проект был создан для изучения принципов взаимодействия между бэкендом и фронтендом через API, а также для освоения создания REST API-сервисов

## Возможности

- **REST API**: Реализован полноценный REST API для работы с данными о котиках.
- **Интеграция с фронтендом**: Позволяет легко взаимодействовать с клиентскими приложениями.

## Технологии

- **Django**: Основной фреймворк для разработки бэкенда.
- **Django REST Framework**: Используется для создания RESTful API.

## Документация API

### 1. /api/cats/

#### GET
##### Description:

Получение информации о всех котах

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Номер страницы в наборе результатов с разбивкой на страницы | No | integer |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  

#### POST
##### Description:

Добавление информации о новом коте

##### Parameters:

No parametrs

##### Responses

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 2. /api/cats/{id}/

#### GET
##### Description:

Получение информации об определенном коте

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого кота | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PUT
##### Description:

Обновление информации об определенном коте

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого кота | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PATCH
##### Description:

Частичное обновление информации об определенном коте

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого кота | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### DELETE
##### Description:

Удаление информации об определенном коте

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого кота | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 204 |  |

### 3. /api/achievements/

#### GET
##### Description:

Получение информации о всех дрстижениях 

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### POST
##### Description:

Добавление нового достижения

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 4. /api/achievements/{id}/

#### GET
##### Description:

Получение информации об определенном достижении

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее это достижение | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PUT
##### Description:

Обновление информации об определенном достижении

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее это достижение | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PATCH
##### Description:

Частисное обновление информации об определенном достижении

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее это достижение | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### DELETE
##### Description:

Удаление информации об определенном достижении

##### Parameters

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее это достижение | Yes | string |

##### Responses

| Code | Description |
| ---- | ----------- |
| 204 |  |

### 5. /api/users/

#### GET
##### Description:

Получение информации о всех пользователях

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| page | query | Номер страницы в наборе результатов с разбивкой на страницы | No | integer |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### POST
##### Description:

Добавление нового пользователя

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 6. /api/users/me/

#### GET
##### Description:

Получение информации о своем профиле

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PUT
##### Description:

Обновление информации о своем профиле

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PATCH
##### Description:

Частичное обновление информации о своем профиле

##### Parameters:

No parametrs

##### Responses

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### DELETE
##### Description:

Удаление информации о своем профиле

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 204 |  |

### 7. /api/users/{id}/

#### GET
##### Description:

Получение информации о определенном пользователе

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого пользователя | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PUT
##### Description:

Обновление информации о определенном пользователе

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого пользователя | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### PATCH
##### Description:

Частичное обновление информации о определенном пользователе

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого пользователя | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 200 |  |

#### DELETE
##### Description:

Удалаение информации о определенном пользователе

##### Parameters:

| Name | Located in | Description | Required | Schema |
| ---- | ---------- | ----------- | -------- | ---- |
| id | path | Уникальное целочисленное значение, идентифицирующее этого пользователя | Yes | string |

##### Responses:

| Code | Description |
| ---- | ----------- |
| 204 |  |

### 9. /api/users/activation/

#### POST
##### Description:

Активация учетной записи пользователя

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 10. /api/users/resend_activation/

#### POST
##### Description:

Повторная отправка письма активации

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 11. /api/users/reset_password/

#### POST
##### Description:

Запрос на сброс пароля

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 12. /api/users/reset_password_confirm/

#### POST
##### Description:

Подтверждение сброса пароля

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### /api/users/reset_username/

#### POST
##### Description:

Запрос на сброс имени пользователя

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 13. /api/users/reset_username_confirm/

#### POST
##### Description:

Подтверждение сброса пароля

##### Parameters:

No parametrs

##### Responses

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 14. /api/users/set_password/

#### POST
##### Description:

Смена пароля

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 15. /api/users/set_username/

#### POST
##### Description:

Смена имени пользователя

##### Parameters:

No parametrs

##### Responses

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 15. /api/token/login/

#### POST
##### Description:

Получение токена аутентификации пользователя

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |

### 16. /api/token/logout/

#### POST
##### Description:

Выход пользователя из системы (удаления токена аутентификации пользователя)

##### Parameters:

No parametrs

##### Responses:

| Code | Description |
| ---- | ----------- |
| 201 |  |
