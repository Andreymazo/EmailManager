# EmailManager
- git clone https://github.com/Andreymazo/EmailManager.git
- pip install -r requirements.txt

file .env:
    SECRET_KEY=
    DJANGO_SETTINGS_MODULE=config.settings
    PYTHONUNBUFFERED=1
    DB_NAME=
    DB_PASSWORD=
    DB_USER=
    DB_PORT=
    DB_HOST=
    BASE_URL=
    EMAIL_HOST_USER = 
    EMAIL_HOST_PASSWORD = 
    yandex_password = 

- python manage.py chek

mind 101 string in chek.py  (for msgnum in msgnums[0].split()[10:18]:)
slice messages you want to parse

![Screenshot from 2024-04-03 16-14-27](https://github.com/Andreymazo/EmailManager/assets/116811819/49181dcd-e60d-4fd5-b3e3-eb8a15365c5d)

From client side receive email from yandex,ru and mail.ru at a time. No code in the repo? just demo. Enjoy 1 min video:

[Screencast from 08.04.2024 02:59:58.webm](https://github.com/Andreymazo/EmailManager/assets/116811819/62fb2f19-c1e8-445b-8c14-5f5af584677e)


