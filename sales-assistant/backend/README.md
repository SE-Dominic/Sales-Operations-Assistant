# Sales-Operations-Assistant

## Quick Start

### Prerequisites
- Java 17+
- PostgreSQL 14+
- Maven 3.8

### Setup

1. Clone repo:
```bash
git clone https://github.com/YOUR_USERNAME/lead-qualifier-api.git
cd lead-qualifier-api
```

## API Endpoints

- `POST /api/upload` — Upload CSV of prospects
- `GET /api/prospects` — List prospects with pagination
- `GET /api/results/{prospectId}` — Get qualification result
- `POST /api/prospects/{prospectId}/mark-contacted` — Mark as contacted
- `GET /api/stats` — Dashboard statistics

## Built With
- Spring Boot 4.1.0
- PostreSQL
- AI API (to be determined)
- Spring Data JPA