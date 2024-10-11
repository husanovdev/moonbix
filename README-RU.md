[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_coding)

[![Static Badge](https://img.shields.io/badge/Telegram-Chat-yes?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/hidden_codding_chat)

[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/Binance_Moonbix_bot/start?startApp=ref_355876562&startapp=ref_355876562&utm_medium=web_share_copy)

# 🚀 АВТО ФАРМ ДЛЯ MOONBIX 🚀

> [!WARNING]
> Этот бот сейчас работает не стабильно.

> [!WARNING]
> Я не несу ответственности за ваш аккаунт. Пожалуйста, учитывайте потенциальные риски перед использованием этого бота.

## МОИ ДРУГИЕ БОТЫ

### 💩 [Boinkers](https://github.com/YarmolenkoD/boinkers)
### 🎨 [Notpixel](https://github.com/YarmolenkoD/notpixel)

## Рекомендация перед использованием

# 🔥🔥 Используйте PYTHON версии 3.10 🔥🔥

> 🇪🇳 README in english available [here](README-EN)

## Функционал  
|                   Функционал                   | Поддерживается |
|:----------------------------------------------:|:--------------:|
|                Многопоточность                 |       ✅        | 
|            Привязка прокси к сессии            |       ✅        | 
|          Поддержка pyrogram .session           |       ✅        |
| Авто-регистрация аккаунта по вашей реф. ссылке |       ✅        |
|                   Авто таски                   |       ✅        |
|                   Авто игры                    |       ✅        |


## [Настройки](https://github.com/YarmolenkoD/moonbix/blob/main/.env-example/)
|            Настройки            |                                      Описание                                       |
|:-------------------------------:|:-----------------------------------------------------------------------------------:|
|      **API_ID / API_HASH**      | Данные платформы, с которой будет запущена сессия Telegram (по умолчанию - android) |
|   **USE_RANDOM_DELAY_IN_RUN**   |                                 Имя говорит за себя                                 |
|     **RANDOM_DELAY_IN_RUN**     |            Рандомная задержка в секундах для ^^^ (по умолчанию - [5, 30]            |
| **RANDOM_DELAY_BETWEEN_CYCLES** |    Рандомная задержка в минутах между цыклами (по умолчанию - [20, 40, 60, 80])     |
|           **USE_REF**           |  Регистрировать ваши аккаунты по вашей реф. ссылке или нет (по умолчанию - False)   |
|           **REF_ID**            |       Ваш реферальный аргумент (идет после app/startapp? в вашей реф. ссылке)       |
|     **USE_PROXY_FROM_FILE**     |       Использовать ли прокси из файла `bot/config/proxies.txt` (True / False)       |
|      **ENABLE_AUTO_TASKS**      |             Включить ли автоматическое выполнение тасков (True / False)             |
|   **ENABLE_AUTO_PLAY_GAMES**    |              Включить ли автоматическое выполнение игр (True / False)               |
|       **MAX_GAME_POINTS**       |      Максимальное количетсво поинтов за одну игру (Рекомендуемое значение 200)      |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл run.bat на Windows или run.sh на Линукс

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **версии 3.10**

## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/YarmolenkoD/moonbix) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/YarmolenkoD/moonbix.git
cd moonbix
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/moonbix >>> python3 main.py --action (1/2)
# Or
~/moonbix >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/moonbix >>> python main.py --action (1/2)
# Или
~/moonbix >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```
