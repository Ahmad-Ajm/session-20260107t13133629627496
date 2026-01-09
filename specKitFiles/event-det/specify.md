# Specify – Event Details Page

## API
GET /api/events/{id}

### Response
```
{
  "id": "string",
  "title": "string",
  "description": "string",
  "date": "YYYY-MM-DD",
  "time": "HH:MM",
  "location": "string",
  "organizer": "string",
  "externalRegistrationUrl": "string | null"
}
```

## UI
- عرض عمودي بسيط
- زر تسجيل خارجي بارز
- دعم RTL بالكامل
