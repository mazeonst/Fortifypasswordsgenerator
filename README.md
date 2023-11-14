# Fortify
<p align="center">
Fortify
</p>
Профессиональный генератор паролей, включающий в себя множество опций для генерации пароля
# Возможности Fortify Pass 
1. Генерация сразу нескольких паролей. 
2. Генерация пароля заданной пользователем длины. 
3. Интеграция в пароль своих фраз, слов. 
4. Использование разных опций для генерации пароля, таких как: 
1. Добавление цифр в пароль. 
2. Добавление специальных символов в пароль. 
3. Возможность выбора генерации символов разного регистра. 
Так же "FortifyPass" умеет шифровать пароль, благодаря такой библиотеке, как "cryptography.fernet" 
1. При запуске программы автоматически загружается ключ шифрования в файл "encryption_key.key" 
ВНИМАНИЕ! КЛЮЧ ШИФРОВАНИЯ ВАЖНО СОХРАНИТЬ В ОТДЕЛЬНЫЙ ИСТОЧНИК ИНАЧЕ ЕСТЬ ВЕРОЯТНОСТЬ ПОТЕРИ ВСЕХ ЗАШИФРОВАННЫХ ДАННЫХ! 
2. В окне "пароль и данные" есть кнопка "зашифровать" после нажатия которой, пароль шифруется и записывается в файл "passwords.txt". 
3. На главном экране программы имеется кнопка "Расшифровать" после ее нажатия открывается окно "Расшифровать пароль" в котором благодаря ранее сохраненному ключу шифрования вы можете расшифровать данные
