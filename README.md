# Symfony

Example [Symfony](https://symfony.com/) app. Symfony is a PHP framework and a set of reusable components for building web applications.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | `rm -rf var/cache` |
| Start command | leave empty |
| Application port | `8000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
composer install

# start the app
symfony server:start
```

Requires PHP 8.1 or later.
