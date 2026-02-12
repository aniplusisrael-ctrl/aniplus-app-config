# AniPlus App Access Control

קובץ בקרת גישה לאפליקציית AniPlus.

## שימוש:
- `isAppEnabled: true/false` - האם האפליקציה פעילה
- `message` - הודעה למשתמשים
- `minVersion` - גרסה מינימלית נדרשת

## דוגמאות:

### אפליקציה פעילה:
```json
{
  "isAppEnabled": true,
  "message": "האפליקציה פעילה"
}
```

### אפליקציה בתחזוקה:
```json
{
  "isAppEnabled": false,
  "message": "האפליקציה בתחזוקה. נחזור בקרוב!"
}
```

### דרישת עדכון:
```json
{
  "isAppEnabled": true,
  "minVersion": "1.1.0",
  "message": "אנא עדכן לגרסה החדשה"
}
```

## עדכון אחרון:
13/02/2024 - האפליקציה פעילה