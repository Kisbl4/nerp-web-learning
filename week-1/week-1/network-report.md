# Разбор сайта (https://admin.nerpvpn.net/login) 25.10.2026

Запросов при загрузке: 167, вес - 7,9 MB
С Disable cache: 164, вес - 7,9 MB

| #   | метод  | адрес                                                         | статус | тип                             | размер | зачем                   |
| --- | ------ | ------------------------------------------------------------- | ------ | ------------------------------- | ------ | ----------------------- |
| 1   | POST   | https://admin.nerpvpn.net/api/auth/refresh                    | 502    | text/html                       | 0.4kB  | аутентификация          |
| 2   | GET    | https://admin.nerpvpn.net/api/shifts/now                      | 200    | application/json; charset=utf-8 | 0.8kB  | те, кто сейчас на смене |
| 3   | PATCH  | https://admin.nerpvpn.net/api/admin/management/22/role        | 200    | application/json; charset=utf-8 | 0,3 kB | поменять роль           |
| 4   | DELETE | https://admin.nerpvpn.net/api/admin/promo-codes/39            | 200    | application/json; charset=utf-8 | 0.3kB  | удалить промокод        |
| 5   | PUT    | https://admin.nerpvpn.net/api/admin/management/22/permissions | 200    | application/json; charset=utf-8 | 0.3kB  | изменить права админа   |

## Сайт устанавливает cookies: `Next-Locale`, `__ddg10_`, `__ddg1_`, `__ddg8_`, `__ddg9_`, `access_token`; флаг HttpOnly установлен у `__ddg1_` и `access_token`
