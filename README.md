# 🌈 GloWin — מערכת אור חי למילים

<img width="1536" height="1024" alt="Neon _GloWin_ in Cosmic Glow" src="https://github.com/user-attachments/assets/bad66b95-c12b-4907-b549-ffa7de601ccc" />


<div align="center">

![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)
![Status](https://img.shields.io/badge/status-alpha-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**תאריך לועזי:** 15/10/2025  
**תאריך עברי:** י״ב בתשרי תשפ״ו

</div>

---

## 🌐 אתר הפרויקט

**🎉 חדש!** עמוד ראשי מרהיב ב-GitHub Pages:  
**[https://AnLoMinus.GitHub.io/GloWin](https://AnLoMinus.GitHub.io/GloWin)** ← לחץ לצפייה!

---

## 🎯 מהו GloWin?

**GloWin** היא מערכת ייחודית להחייאת טקסט עם אור דינמי ונושם. כל מילה ואות הופכת למקור אור חי שנושם, מתנוצץ ומתקשר ישירות אל הנשמה.

הפרויקט משלב **Glow** (הילה חיצונית) + **Flow** (זרימה פנימית) ליצירת חוויית קריאה רוחנית־חזותית מרהיבה.

---

## ✨ תכונות מרכזיות

### 🎨 RGB Divine Light

- **6 ערכות Theme רוחניות**: חסד, גבורה, תפארת, טהרה, חכמה, אמונה
- כל Theme מבוסס על צבעי RGB עם משמעות רוחנית עמוקה
- אפשרות להרחבה והתאמה אישית

### 💫 מחזור Glow Cycle

1. **Detect** — זיהוי כניסת הקורא לשורה
2. **Prime** — טעינת צבעי Theme
3. **Ignite** — התנוצצות התחלתית
4. **Breathe** — נשימת אור מתמשכת
5. **Crown** — הבזק לבן בשיא
6. **Fade** — דעיכה רכה לזיכרון אור

### 🪄 Intent Modes

- **Ignite** — הדלקה והתלהבות
- **Shield** — הגנה ומעטה
- **Heal** — ריפוי וזרימה
- **Cleanse** — טיהור והארה
- **Flow** — זרימה מתמשכת
- **Crown** — הרמה והכתרה

### 🎭 אפקטים ויזואליים

- **Halo** — הילה עגולה סביב אותיות
- **Trail** — שובל אור עוקב
- **Glass** — מסיכת זכוכית מטושטשת
- **Spark** — ניצוצות פנימיים
- **Breathe** — נשימת אור קבועה

---

## 📂 מבנה הפרויקט

```
glowin/
├─ 🌐 index.html             # עמוד ראשי (GitHub Pages)
├─ 🎨 style.css              # עיצוב landing page
├─ ⚡ script.js              # מנוע לעמוד הראשי
├─ presets/
│  └─ themes.json          # ערכות אור מוגדרות מראש
├─ css/
│  ├─ core.css             # משתנים, טיפוגרפיה, בסיס
│  ├─ effects.css          # אפקטי אור ואנימציות
│  └─ performance.css      # 🆕 אופטימיזציות ביצועים
├─ js/
│  ├─ glow.js              # מנוע Glow - הפעלה דינמית
│  └─ glow-optimized.js    # 🆕 מנוע ממוטב (60 FPS)
├─ leaflets/
│  ├─ leaflet_01.html      # עלון 01 - שִׁוִּיתִי ה׳ (מקורי)
│  └─ leaflet_02.html      # 🆕 עלון 02 - שְׁמַע יִשְׂרָאֵל
├─ docs/
│  ├─ GLOWIN_GUIDE.md      # מדריך מפורט למפתחים
│  ├─ GLOWIN_ALGORITHM.md  # 🆕 אלגוריתם יצירת עלון (10 שלבים)
│  └─ PERFORMANCE_QA.md    # 🆕 מדריך ביצועים (60 FPS)
├─ test-1.html             # דוגמה מתקדמת ראשונית
└─ README.md               # קובץ זה
```

---

## 🚀 איך להתחיל?

> 💡 **טיפ:** לא בטוח מאיפה להתחיל? ראה [INDEX.md](INDEX.md) למפת תיעוד מלאה!

### ⚡ התחלה מהירה (3 דקות)

ראה [QUICKSTART.md](QUICKSTART.md) להנחיות מפורטות.

### התקנה

1. **שכפל את הפרויקט**

```bash
git clone https://github.com/AnLoMinus/GloWin.git
cd GloWin
```

2. **פתח עלון דוגמה**

```bash
# פתח את הקובץ בדפדפן
open leaflets/leaflet_01.html
```

3. **התאם אישית**

- ערוך את `presets/themes.json` להוספת Themes חדשים
- ערוך את `css/effects.css` לאפקטים מותאמים
- צור עלון חדש על בסיס `leaflet_01.html`

---

## 📖 שימוש בסיסי

### יצירת עלון חדש

```html
<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>עלון GloWin חדש</title>
  
  <!-- טען CSS -->
  <link rel="stylesheet" href="../css/core.css">
  <link rel="stylesheet" href="../css/effects.css">
</head>
<body>

  <div class="leaflet-container">
    <!-- תוכן עם Theme ו-Intent -->
    <div class="line" data-theme="אמונה" data-intent="ignite">
      <span class="word">
        <span class="gl">ש</span><span class="gl">ל</span><span class="gl">ו</span><span class="gl">ם</span>
      </span>
    </div>
  </div>

  <!-- טען JS -->
  <script src="../js/glow.js"></script>
</body>
</html>
```

### בחירת Theme

השתמש ב-attribute `data-theme`:

```html
<!-- חסד - אדום חם -->
<div data-theme="חסד">...</div>

<!-- חכמה - כחול צלול -->
<div data-theme="חכמה">...</div>

<!-- תפארת - סגול מאוזן -->
<div data-theme="תפארת">...</div>
```

### בחירת Intent

השתמש ב-attribute `data-intent`:

```html
<!-- הדלקה מהירה -->
<div data-intent="ignite">...</div>

<!-- נשימה איטית -->
<div data-intent="flow">...</div>

<!-- פעימת הגנה -->
<div data-intent="shield">...</div>
```

---

## 🎨 Themes זמינים

| Theme | צבע | משמעות רוחנית | RGB |
|-------|------|----------------|-----|
| **חסד** | 🔴 אדום-כתום | נתינה, אהבה, חמימות | `255, 130, 90` |
| **גבורה** | 🔴 אדום-עמוק | הגנה, דין, חיתוך | `255, 30, 60` |
| **תפארת** | 🟣 סגול-ורוד | איזון, הרמוניה, יופי | `240, 200, 255` |
| **טהרה** | 🟢 ירוק-תכלת | טיהור, ריענון, צלילות | `220, 255, 240` |
| **חכמה** | 🔵 כחול-בהיר | תובנה, צלילות, ראייה | `140, 200, 255` |
| **אמונה** | 🟡 זהב-צהוב | ביטחון, כתר, חיזוק | `255, 220, 120` |

---

## ⚙️ התאמה אישית מתקדמת

### יצירת Theme חדש

ערוך את `presets/themes.json`:

```json
{
  "themes": {
    "שמחה": {
      "name": "שמחה",
      "rgb": { "r": 255, "g": 200, "b": 50 },
      "meaning": "אור וחדווה",
      "intentRecommendations": ["ignite", "flow"]
    }
  }
}
```

### שינוי Theme דינמי ב-JavaScript

```javascript
// שנה Theme בזמן ריצה
window.setGlowTheme('חכמה');

// הפעל Glow על אלמנט ספציפי
window.glowElement('.my-element');

// גישה ישירה למנוע
window.glowin.changeTheme('תפארת');
```

---

## 🧪 דוגמאות שימוש

### 1. פסוק תהילים עם אפקט Ignite

```html
<div data-theme="אמונה" data-intent="ignite">
  <div class="line">
    <span class="word">
      <span class="gl halo">ה</span><span class="gl halo">׳</span>
    </span>
    <span class="word">
      <span class="gl">א</span><span class="gl">ו</span><span class="gl">ר</span><span class="gl">י</span>
    </span>
  </div>
</div>
```

### 2. טקסט עם Halo וSpark

```html
<span class="gl halo spark">מ</span>
<span class="gl halo spark">ש</span>
<span class="gl halo spark">ה</span>
```

### 3. שורה עם Glass Effect

```html
<div class="line" data-theme="טהרה">
  <span class="gl glass">ט</span>
  <span class="gl glass">ה</span>
  <span class="gl glass">ר</span>
</div>
```

---

## 🧭 מפת דרכים (Roadmap)

### ✅ גרסה 0.1.0 — יסודות (הושלם 15/10/2025)

- [x] תשתית בסיסית HTML/CSS/JS
- [x] 6 Themes ראשוניים
- [x] מנוע Glow דינמי
- [x] עלון דוגמה ראשון (שִׁוִּיתִי ה׳)

### 🔄 גרסה 0.1.1 (בפיתוח)

- [x] עלון 02 - שְׁמַע יִשְׂרָאֵל
- [x] GLOWIN_ALGORITHM.md - אלגוריתם מפורט
- [x] עדכון מיתוג ל-GloWin
- [x] ⚡ **PERFORMANCE_QA.md** - פתרון בעיית lag + התחממות
- [x] **glow-optimized.js** - מנוע ל-60 FPS
- [x] **performance.css** - CSS ממוטב
- [x] 🌐 **Landing Page** - index.html + style.css + script.js ← 🎉 **חדש!**
- [ ] TEMPLATE.html רשמי להעתקה
- [ ] עוד 3 עלונים נוספים

### 🔄 גרסה 0.2.0 (מתוכנן)

- [ ] הרחבה ל-10 Themes נוספים
- [ ] אפקטים מתקדמים (Burst, Ripple)
- [ ] מערכת Presets חכמה
- [ ] תמיכה בטקסט דו-כיווני

### 🎯 גרסה 0.3.0 (עתידית)

- [ ] מחולל עלונים אוטומטי
- [ ] ממשק גרפי לעריכה
- [ ] ייצוא PDF עם Glow סטטי
- [ ] תמיכה בהדפסה מתקדמת

### 🌟 גרסה 1.0.0 (יעד)

- [ ] אתר Glowin מלא
- [ ] גלריית עלונים
- [ ] מאגר Themes קהילתי
- [ ] API פתוח לשימוש חיצוני

---

## 🤝 תרומה לפרויקט

Glowin הוא פרויקט קוד פתוח! נשמח לתרומות:

1. **Fork** את הפרויקט
2. צור **Branch** חדש: `git checkout -b feature/amazing-glow`
3. **Commit** את השינויים: `git commit -m 'Add amazing glow effect'`
4. **Push** ל-Branch: `git push origin feature/amazing-glow`
5. פתח **Pull Request**

### רעיונות לתרומה

- 💡 Theme חדש עם משמעות רוחנית
- ✨ אפקט חזותי ייחודי
- 📝 עלון מעוצב
- 🐛 תיקון באגים
- 📖 שיפור תיעוד

---

## 📚 קישורים ומשאבים

### תיעוד

- 📖 **מדריך מפתח**: [GLOWIN_GUIDE.md](docs/GLOWIN_GUIDE.md)
- 🧭 **אלגוריתם יצירה**: [GLOWIN_ALGORITHM.md](docs/GLOWIN_ALGORITHM.md)
- ⚡ **ביצועים ו-QA**: [PERFORMANCE_QA.md](docs/PERFORMANCE_QA.md) ← 🆕 **חובה לקרוא!**
- 🎨 **Themes**: [themes.json](presets/themes.json)

### עלונים לדוגמה

- 📄 **Leaflet 01**: [שִׁוִּיתִי ה׳ לְנֶגְדִּי תָמִיד](leaflets/leaflet_01.html)
- 📄 **Leaflet 02**: [שְׁמַע יִשְׂרָאֵל](leaflets/leaflet_02.html) ← 🆕

### קישורים חיצוניים

- 🌐 **אתר הפרויקט**: [AnLoMinus.GitHub.io/GloWin](https://AnLoMinus.GitHub.io/GloWin) ← 🎉 **חדש!**
- 💻 **GitHub Repository**: [github.com/AnLoMinus/GloWin](https://github.com/AnLoMinus/GloWin)
- 👤 **AnLoMinus**: [anlominus.github.io](https://anlominus.github.io)

---

## 🏷️ האשטגים

`#GloWin` `#GlowFlow` `#SparkReading` `#HolyPixels` `#AnLoMinus` `#OpenTorahAI` `#MysticUI` `#CreativeHalacha` `#DivineLight` `#RGBLight`

---

## 📜 קרדיטים

### ייזום ופיתוח

**AnLoMinus** (משה לאון יעקובוב)  
🔗 [GitHub](https://github.com/AnLoMinus)  
📧 [צור קשר](mailto:anlominus@gmail.com)

### תודות מיוחדות

- לכל העוסקים באור התורה והחכמה
- לקהילת המפתחים הפתוחה
- לכל מי שתורם ומשתף בפרויקט

---

## 📄 רישיון

פרויקט זה מופץ תחת רישיון **MIT License**.  
ניתן לשימוש חופשי, שינוי והפצה עם ציון מקור.

---

## 💌 צור קשר

יש לך שאלות? רעיונות? רוצה לשתף פעולה?

- 💬 פתח [Issue](https://github.com/AnLoMinus/GloWin/issues) ב-GitHub
- 📧 שלח מייל: <anlominus@gmail.com>
- 🌐 בקר באתר (בקרוב)

---

<div align="center">

**🌈 נוצר באהבה, אור ותודעה גבוהה ✨**

**GloWin** — שם המיתוג: Glo (זוהר) + Win (ניצחון/חלון)

תאריך יצירה: י״ב בתשרי תשפ״ו (15/10/2025)

</div>
