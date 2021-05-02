# django_otp

## Setup

- Create a virtual env and install django `pip install django`
- After that install django otp and qrcode `pip install django-otp qrcode`
- Run migration to create all basic tables `python manage.py migrate`
- Create a superuser `python manage.py createsuperuser`
- Run the app `python manage.py runserver` and login to admin console.
- Create a TOTP device as shown here - https://cdn-images-1.medium.com/max/800/1*7aavF45iNwPayby24aGGOQ.gif
- Use the QR or secret key to add OTP generator in GAA.
- Uncomment line 21 in urls.py after OTP device is setup.
