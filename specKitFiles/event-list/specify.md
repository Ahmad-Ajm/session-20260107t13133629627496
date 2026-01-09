# Specify – Browse Events List (FEAT-EVENT-LIST)

## Data Model (Event Summary)
- id: UUID
- title: string
- date: ISO date
- time: string
- location: string
- category: string
- organizerName: string
- coverImageUrl: string (optional)

## API
### GET /api/events
Returns list of upcoming and ongoing events

Response:
```
[{ id, title, date, time, location, category, organizerName, coverImageUrl }]
```

## UI
- قائمة عمودية
- كل عنصر يحتوي: صورة (اختياري)، اسم، تاريخ، مكان
- الضغط ينقل إلى صفحة التفاصيل

## Performance
- حجم الاستجابة أقل من 200KB
- صور مضغوطة