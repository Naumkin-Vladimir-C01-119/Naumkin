1. Генерация SSH ключа
Откройте Терминал. Вставьте в него следующий код, подставив в кавычки свой адрес электронной почты на GitHub.
ssh-keygen -t ed25519 -C "your_email@example.com"

2. Добавление ключа на github
В настройках пользователя в разделе SSH and GPG keys нажать на кнопку Add ssh key

3. Клонирование репозитория
Команда для терминала
git clone git@github.com:Naumkin-Vladimir-C01-119/Naumkin.git