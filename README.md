# Lumen JWT

dev

```bash
# edit env
cp .env.example .env

# add APP_KEY
php -r "echo md5(uniqid()).\"\n\";"

# DB migrate
php artisan migrate

# serve service
php -S localhost:8000 -t public_html/api
```
