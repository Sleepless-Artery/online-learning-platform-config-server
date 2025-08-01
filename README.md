# Online learning platform config server
## Описание
Микросервис платформы онлайн-обучения, отвечающий за подключение к git-репозиторию с конфигурациями микросервисов
## Использование
Клонируйте репозиторий:
```bash
git clone https://github.com/Sleepless-Artery/online-learning-platform-config-server
```
В каталоге, в который склонировали настоящий репозиторий, создайте файл .env, скопируйте в него содержимое файла .env.example и замените значения переменных окружения на нужные

Для успешной работы приложения нужно сгенерировать персональный токен доступа (personal access token). Это можно сделать в разделе settings -> developer settings -> personal access tokens

Перейдите по следующим ссылкам и выполните описанные шаги:
- [Репозиторий конфигураций микросервисов](https://github.com/Sleepless-Artery/online-learning-platform-configs)
- [Репозиторий инфраструктуры приложения](https://github.com/Sleepless-Artery/online-learning-platform-infra)
## Требования
- Java 17+
- Maven 3.9.x
- Docker CLI
- Аккаунт GitHub
## Технологии
- Java
- Spring Boot
- Spring Cloud
- YML
- Maven
- Docker
- Git
