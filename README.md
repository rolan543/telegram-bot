Для того чтобы запустить мой телеграмм бот, для начала вам нужно в Visual Studio Code, создать новую папку Venv.В ней создать 2 файла таких как:(Config.py, Main.py).Установить cвои библиотеки Telebot а также библиотеку OpenAi.
После все этого вам требуется , взять мой код , скопировать и перекинуть в Visual Studio , затем поменять API ключи у Телеграмм и OpenAi.
Далее вам нужно сохранить эти ключи.
Сохранить весь код нажатием клавиш Cntl+S.
Открыть в Телеграмме наш бот.
И пользоваться для своих задач.
Наш бот может ответить на любой ваш вопрос!
Далее вам нужно сохранить ваш код Main.py,потом надо запустить ваш код написав в терминале \venv\Scripts\python.exe main.py и тогда у вас запустится бот в телеграме.
OpenAiKey = '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'
TgKey = '6819872169:AAF6kGp87bmp0jiaUL1MVW2anNz7lDwjTnM' вот это надо вставить в Config.py
openai.api_key = OpenAiKey
bot = telebot.TeleBot(TgKey) это пример билиотеки Telebot и OpenAi,но вместо этого у вас должны стоят свои ключи.
После этого у вас должен запустится бот в телеграме которому вы можете задавать любые вопросы.
Надо устоновить билиотеке Install Telebot b Install OpenAi


