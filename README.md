# מערכת ניהול לידים ומכירות

פרויקט React/Vite מוכן לפריסה ב-GitHub Pages.

## התקנה מקומית

```bash
npm install
npm run dev
```

## פריסה ל-GitHub Pages

1. צרי Repository חדש ב-GitHub.
2. העלי את כל הקבצים לתיקיית ה-Repository.
3. היכנסי ל-Settings > Pages.
4. תחת Build and deployment בחרי Source: GitHub Actions.
5. בצעי Push ל-branch בשם `main`.
6. חכי שה-Action יסתיים.
7. הקישור יופיע ב-Settings > Pages.

## חשוב

הגרסה הזו היא Frontend סטטי. הנתונים נשמרים ב-localStorage של הדפדפן בלבד.
כלומר: שינוי שמבוצע בטלפון אחד לא מסתנכרן אוטומטית לטלפון אחר.

כדי להפוך את זה למערכת צוות אמיתית צריך להוסיף:
- בסיס נתונים כמו Supabase / Firebase
- התחברות משתמשים
- הרשאות
- API לסנכרון לידים ומשימות
