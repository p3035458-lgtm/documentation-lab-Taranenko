### 4. `API_OVERVIEW.md`
# Технічна документація API (API Overview)
Документація описує базові REST API endpoint'и для управління подорожами, квитками та бронюваннями готелів.
Базовий URL: `https://api.travel-planner.example.com/v1`

### 1. Отримання списку подорожей
* **HTTP Метод:** `GET`
* **Path:** `/trips`
* **Опис:** Повертає список усіх збережених подорожей користувача.

**Приклад запиту:**
```http
GET /v1/trips HTTP/1.1
Host: api.travel-planner.example.com
Authorization: Bearer YOUR_TOKEN_HERE