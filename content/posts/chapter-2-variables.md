---
author: "דוד אבן חיים"
date: "2021-05-18"
image: chapter-2-variables.jpg
isFeatured: false
summary: "משתנה - לא מפחיד כמו שהיה בתיכון"
time: 7
title: "פרק 2: משתנים"
---

# משתנים

אז במתמטיקה בתיכון למדנו על המשתנה x והוא יכל להחזיק כמות בלתי מוגבלת של ערכים (מספריים) גם ב js יש משתנים כמו בכל שפת תכנות אחרת.

אז איך מגדירים?

```js
let myName;
```

באמצעות המילה השמורה
**_let_**
הגדרנו משתנה ״השם שלי״, שימו לב שסיימנו את השורה עם
**( ; )**

כרגע יצרנו משתנה ללא ערך.
אפשר להקצאות לו ערך באמצעות =

```js
myName= ‘David’;
```

עכשיו למשתנה שלנו יש ערך, המחרוזת ‘David’ !  
כרגע למדנו על משתנה, שכפי ששמו מציין יכול להשתנות תמיד.  
יש לנו עוד דרך להגדיר "משתנה" שמוגדר באמצעות
**const**
, בא מהמילה Constant, שזה קבוע.
אז משתנה שלא יכול להשתנות, למה? יש ערכים שצריך להצהיר שהם לא אמורים להשתנות.

דוגמא:
const secondsInMinute = 60;
מס' השניות בדקה לא יישתנה לעולם ולכן נגדיר אותו בתור קבוע.

לערך קבוע יש כמה חוקים:
-חייב להיות מאותחל עם ערך!

אם ננסה לעשות:
const secondsInMinute ;
נקבל שגיאה!

-**אי אפשר לשנות אותו במשך הקוד! ולכן: שימוש בקבועים כשאפשר יהיה תכנות בטוח יותר!**

#### מוסכמות בשפה

אז בשפת תכנות כמו בכל שפה גם יש מוסכמות על המון דברים, כרגע נעבור על כמה חשובים :

1. **_משתנה שמוגדר_**
   יתחיל באות קטנה וכאשר שמו מכיל כמה מילים כל מילה חדשה תתחיל באות גדולה:

```js
let myName = ‘David’;
let myAge = 23
let myFavoriteSport = ‘Football’
```

2. **_משתנה קבוע_**
   ייכתב באותיות גדולות, כאשר ההפרדה בין מילים תהיה באמצעות

   ```js
   const SECONDS_IN_MINUTE = 60;
   ```

   אי אפשר לעשות רווח בין מילים כאשר מגדירים משתנה ולכן משתמשים בקו תחתון ( \_ )

3. **_שמות משתנים_**
   צריכים להיות כמה שיותר ברורים! אני אמשיך ואדגיש זאת לאורך הבלוג.