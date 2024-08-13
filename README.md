<div align="center">

| ![Telegram BOT](https://telegra.ph/file/eda00c9261d1969f63f48.png) | ![Terminal](https://telegra.ph/file/687fcda6eadd686c4bfa1.png) |
|:---:|:---:|

# 🐹 Hamster Kombat Key Gen /// HPV /// V1.55 🔑

**Бесплатный генератор неограниченного количества ключей для игр таких как `Bike Ride 3D`, `Chain Cube 2048`, `My Clone Army`, и `Train Miner` в Hamster Kombat! Все возможные ограничения зависят только от вашего оборудования и количества используемых прокси для генерации ключей!**

# <br><br>Доступны два способа генерации ключей: через Telegram бота или через терминал!
**Telegram** — для взаимодействия с генератором через Telegram, необходимо указать токен вашего бота в конфигурационном файле. Более подробно описано ниже. Этот способ удобнее, но позволяет генерировать только один ключ на каждую игру за одну генерацию; самих генераций может быть сколько угодно! (скрин 1)<br>
**Терминал** — для взаимодействия достаточно запустить скрипт и выбрать желаемое количество ключей. Ключи будут сгенерированы и отображены в терминале, а также сохранены в файле '[HPV] Keys.txt'. Этот способ ограничен только возможностями железа и количеством используемых прокси. Чем их больше, тем больше ключей можно получить за одну генерацию, но максимальное количество ключей на одну игру — 50, то есть всего 200 ключей. Скрипт автоматически подставляет максимальное оптимальное количество сгенерированных ключей за раз в зависимости от доступных прокси. Чем больше прокси, тем меньше ограничение на количество ключей за одну генерацию! (скрин 2)

**<br><br><h3>Данный скрипт предназначен исключительно для образовательных целей! Пользуйтесь им ответственно и избегайте злоупотреблений! Вы полностью несете ответственность за всевозможные последствия его использования, включая риск блокировки аккаунта в боте Hamster Kombat!</h3>**
***
</div>

# <br><br>🧬 Предварительная настройка
- **Linux и Android ([Termux](https://github.com/termux/termux-app/releases))**
  - ```
    apt update && apt upgrade -y
    ```
  - ```
    apt install -y python git
    ```
  - ```
    git clone https://github.com/A-KTO-Tbl/Hamster_Kombat_Key_Gen
    ```
  - ```
    pip3 install -r Hamster_Kombat_Key_Gen/Core/Tools/HPV_Requirements.txt
    ```
- **Windows**
  - Для начала нужно установить [Python](https://www.python.org/downloads/release/python-3103/) (не рекомендуется версию выше 3.10.3) по данному [видеоролику](https://www.youtube.com/watch?v=swZA4EJnsG0) и [Git](https://git-scm.com/download/win);
  - Создаём папку в любом месте, например на рабочем столе. После чего открываем её;
  - В верхней части проводника жмём по пути ***([СКРИНШОТ](https://telegra.ph/file/f4695bbc6a7c4e142c758.jpg))***, и вписываем "*CMD*";
  - Запустится CMD в текущей директории. Далее просто вводим следующие команды:
    - ```
      git clone https://github.com/A-KTO-Tbl/Hamster_Kombat_Key_Gen
      ```
    - ```
      pip install -r Hamster_Kombat_Key_Gen\Core\Tools\HPV_Requirements.txt
      ```

# <br><br>🌐 Настройка Proxy
- Чтобы добавить прокси, перейдите в раздел ***Core* > *Proxy*** и откройте файл ***HPV_Proxy.txt***. Далее просто введите свои прокси в формате одна строка — один прокси. Поддерживаются протоколы SOCKS5 и HTTPS. Пример добавления прокси можно найти в той же папке ***([СКРИНШОТ](https://telegra.ph/file/828b1caf4e50e522ffb9e.jpg))***.

# <br><br>⚙️ Настройка конфига
- Для взаимодействия с генератором через Telegram бота вам необходимо добавить свой токен. Для этого перейдите в `Core > Config` и откройте файл `HPV_Config.py`. Найдите переменную `TG_TOKEN`. Установите в этой переменной валидный токен вашего бота.

# <br><br>⚡️ Запуск
- **Linux и Android ([Termux](https://github.com/termux/termux-app/releases))**
  - Telegram:
    - ```
      cd Hamster_Kombat_Key_Gen && python3 HPV_Key_Gen_Bot.py
      ```
  - Терминал:
    - ```
      cd Hamster_Kombat_Key_Gen && python3 HPV_Key_Gen.py
      ```
- **Windows**
  - Telegram
    - Запустите `[HPV] Key_Gen_Bot.bat`
  - Терминал
    - Запустите `[HPV] Key_Gen.bat`

# <br><br>💎 Дополнительно
- **[Telegram канал](https://t.me/+nXUk0aZ0valjYmFi). Подписка на наш канал — это лучшая поддержка и мотивация для продолжения этого и других проектов! 💜**
- **[Владелец](https://t.me/A_KTO_Tbl)**
- **TON:** ```UQChditl95Hy_kMektYwzpW7Os9OCmyriJaAD0YMdxJREp1s```
- **Base /// BNB Chain /// ETH (EVM):** ```0x4E7Fecf762295CB696e862F4c3a30Ffc586DeDb2```
- **NEAR:** ```a_kto_tbl.near```
- **Tron:** ```TSGP8XnjJ9wFNamYs3k17bN13Vg8WZE55s```
- **Solana:** ```wWMvNzKZFPTr96eGz5hi6aymYsycwvWWrWgHwdXNYPQ```