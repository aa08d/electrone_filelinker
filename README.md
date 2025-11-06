# How to use:
1. 
```
docker-compose run --rm certbot certonly --webroot --webroot-path=/var/www/certbot -d yourdomain.com -d www.yourdomain.com --email your-email@example.com --agree-tos --no-eff-email
```

2.
```
docker-compose up -d
```
