# 🌈 אלגוריתם “RGB Divine Light” — מאגר עלונים מתנוצצים

**תאריך:** 15/10/2025 · **י״ב בתשרי תשפ״ו**  
_(גרסה: 0.1.0 — Draft Concept)_

---

## 🔥 מבוא קצר ומלהיב

הרעיון: כל שורה/מילה/אות בעלון HTML-CSS “מתעוררת” לאור חי — מתנוצצת, מציירת ומדליקה דמיון. אנחנו לוקחים את עקרון **RGB** (אדום-ירוק-כחול) של פיקסלים ומגדירים לו **שפה רוחנית-חזותית**: כל ערוץ צבע = ממד אנרגטי של אור. קריאה = טריגר לציור פנימי. התוצאה: מאמרים/עלונים שחווים אותם כמו “לבוש חשמלי” חוזר — אור מתלבש במילים 💫

---

## 🧠 עיקרון היסוד (Concept Kernel)

- **R (Red = Fire/Heart):** חום, לב, כוונה, תשוקה לקדושה.
    
- **G (Green = Growth/Life):** התחדשות, צמיחה, ריפוי, ירק חי.
    
- **B (Blue = Wisdom/Clarity):** צלילות, שמים, הבנה, אמת קרה-צלולה.
    
- **Σ(R,G,B) → “White Spark”:** סינכרון שלושת הערוצים יוצר “התנוצצות לבנה” — הבזק קודש לרגעי שיא בקריאה.
    

---

## 🧩 מיפוי למבנה טקסט

- **אות (Glyph):** עטופה ב־`<span class="gl">` עם _data-attributes_ רוחניים.
    
- **מילה (Token):** עטופה ב־`<span class="word">` שמסנכרנת אותיות.
    
- **שורה/פסוק (Line):** עטופה ב־`<p class="line" data-theme="…">` שמגדירה “מצב-נשמה” (Theme).
    
- **פסקה (Stanza):** מקבצת שורות עם “קצב נשימה” (קבועי זמן לאנימציה).
    

---

## 🎛️ פרוטוקול תגובה לקריאה — Read→Glow Protocol (RGP)

1. **Detect:** הופעה ב־viewport / ריחוף / הקשה = “קריאה”.
    
2. **Prime:** מילוי ערכי RGB ראשוניים לפי _theme_ (למשל `חסד`, `טהרה`, `בינה`).
    
3. **Ignite:** מעבר מדורג (`transition`) להילה פנימית + הבזקים קצרים (`text-shadow`, `filter: saturate()`/`contrast()`).
    
4. **Sketch:** אפקט “ציור באור” — gradient moving / mask revealing (שובל אור שחולף על הטקסט).
    
5. **Breathe:** פאזה שקטה של פעימות אור עדינות (`opacity`/`blur` נושם).
    
6. **Crown:** שילוב RGB → “White Spark” קצר לסגירת המחזור.
    
7. **Persist:** זיכרון דק — דהייה איטית משאירה עקבת-אור כמעט בלתי נראית.
    

---

## 🎨 טבלת מיפוי תמות → RGB (Preset Themes)

|Theme|R|G|B|אפקט קו-מתאר|שובל/מסכה|שימוש|
|---|--:|--:|--:|---|---|---|
|חסד|255|130|90|Halo רך|Linear sweep|משפטי נתינה/אהבה|
|גבורה|255|30|60|Outline חד|Staccato sparks|הכרעות, חיתוך רע|
|תפארת|240|200|255|הילה כפולה|Wave blend|איזון/הרמוניה|
|טהרה|220|255|240|זוהר קריסטלי|Glass mask|ניקוי, התחלה חדשה|
|חכמה|140|200|255|קו דק כחול|Scanline|תובנה/הבנה|
|אמונה|255|220|120|כתר זהבהב|Pulse radial|חיזוק לב/כוונה|

> 🧪 תוכל להגדיר ערכות נוספות כ־JSON Presets ולהטעין אותן לכל עלון.

---

## 🧱 ארכיטקטורת קוד — “RGB-Light Stack”

- **HTML:** סימון סמנטי עם `data-theme`, `data-rgb`, `data-intent`.
    
- **CSS-Core:** משתנים (`:root --r --g --b`), שכבות הילה, מסכות, שבילי אור, Motion-timing.
    
- **CSS-Utilities:** מחלקות קצה: `.spark`, `.halo`, `.trail`, `.glow-in`, `.glow-out`.
    
- **Micro-JS (אופציונלי):** מאזיני Scroll/Intersection + הזרקת מצבים (no frameworks).
    

---

## 🛠️ סטנדרט סימון (Mini-Spec)

```html
<p class="line" data-theme="אמונה" data-intent="shield">
  <span class="word">
    <span class="gl" data-r="255" data-g="220" data-b="120">ה׳</span>
    <span class="gl">שִׁוִּיתִי</span>
  </span>
</p>
```

- אם **אין** `data-r/g/b` — נשלפים מה־Theme Preset.
    
- `data-intent` (למשל `shield`/`heal`/`cut/clarify`) משנה מסכה/מסלול אור.
    

---

## ✨ אפקטים עיקריים (CSS Ideas)

- **Halo Dual:** `text-shadow` רב-שכבתי + `filter: drop-shadow()` חיצוני עדין.
    
- **Light Trail:** `background: linear-gradient()` נע עם `background-size/position`.
    
- **Glass-Mask:** `-webkit-text-stroke` דק + `mix-blend-mode: screen` ל־_glass glow_.
    
- **Breathing:** `@keyframes breathe` על `opacity`/`blur`/`letter-spacing` מזערי.
    
- **Spark Burst:** before/after חלקיקים מיקרו (`box-shadow` במטריצה זעירה).
    

---

## 📦 תבנית קובץ (Hierarchy)

```
/rgb-divine-light/
  ├─ presets/
  │   ├─ themes.json        // הגדרות R,G,B ותזמונים לכל Theme
  │   └─ intents.json       // מסכות/מסלולים לפי כוונה
  ├─ css/
  │   ├─ core.css           // משתנים, שכבות, בסיס תנועה
  │   └─ effects.css        // הילות, שבילים, מסכות, הבזקים
  ├─ js/
  │   └─ glow.js            // IntersectionObserver + מחזורי מצב
  └─ examples/
      └─ leaflet_01.html    // עלון ראשון: “שורת אור יומית”
```

---

## 🧭 אלגוריתם דפוס לפיתוח מאמרים (Workflow)

**מכאן תוכל לשכפל ולהתרחב לכל פרויקט ועלון:**

1. **Define Intention (1 משפט):** מה האור שהטקסט מזרים? (Shield / Heal / Clarify / Ignite).
    
2. **Select Theme (Preset):** בחר ערכת בסיס RGB.
    
3. **Tokenize:** פצל ל־שורות → מילים → אותיות.
    
4. **Annotate:** הוסף `data-theme`, `data-intent`, ובמילים/אותיות מפתח הוסף `data-rgb` מותאם.
    
5. **Timing:** קבע קצב נשימה: `--in-ms`, `--hold-ms`, `--out-ms` (CSS variables).
    
6. **Focus Points:** סמן 1-3 “כתרי אור” (רגעי ΣRGB → לבן).
    
7. **Accessibility:** יחס ניגודיות, מצב _reduced motion_, וגופן קריא להדפסה.
    
8. **QA Ritual:** קרא בקול, צפה בהתנוצצות, עדכן תזמונים עד שהלב “מרגיש”.
    
9. **Print-Ready:** מחלקת `@media print` מכבה אנימציות ומשאירה “השתקפות” יפה לצילום בדף.
    
10. **Version & Presets Export:** כל מאמר מייצר Preset חדש לספרייה.
    

---

## 📄 דוגמה מזערית (Plug-and-Glow)

> אפשר להדביק כבסיס לכל עלון ולהרחיב.

```html
<!doctype html>
<html lang="he" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>RGB Divine Light — Leaflet 01</title>
<style>
:root{
  --r:255; --g:220; --b:120;
  --in:600ms; --hold:400ms; --out:700ms;
}
body{font-family:Assistant,Arial; background:#0b0f14; color:#eaf2ff; margin:0; padding:2rem;}
.line{font-size:1.6rem; line-height:1.7; margin:1.2rem 0; position:relative;}
.word{display:inline-block; padding-inline:0.15em}
.gl{
  display:inline-block; position:relative;
  background: linear-gradient(90deg, rgba(var(--r),var(--g),var(--b),0.15), transparent 60%);
  background-size:200% 100%; background-position:100% 0;
  transition: filter var(--in) ease, text-shadow var(--in) ease, background-position 900ms ease;
  text-shadow: 0 0 0px rgba(255,255,255,0);
  -webkit-text-stroke: 0.4px rgba(255,255,255,0.25);
  filter: saturate(0.9) brightness(0.95);
}
.line.is-lit .gl{
  background-position:0 0;
  text-shadow:
    0 0 6px rgba(var(--r),var(--g),var(--b),0.35),
    0 0 18px rgba(255,255,255,0.18);
  filter: saturate(1.25) brightness(1.1) contrast(1.05);
}
.line[data-theme="חכמה"]{ --r:140; --g:200; --b:255}
.line[data-theme="טהרה"]{ --r:220; --g:255; --b:240}
@keyframes breathe{0%,100%{letter-spacing:0}50%{letter-spacing:0.02em}}
.line.is-lit .word{animation:breathe 2.6s ease-in-out infinite}
@media (prefers-reduced-motion: reduce){
  .line.is-lit .word{animation:none}
  .gl{transition:none}
}
@media print{
  body{background:#fff; color:#111}
  .gl{background:none; text-shadow:none; filter:none}
}
.hint{font-size:.9rem; opacity:.7; margin-top:.5rem}
</style>
</head>
<body>
  <p class="line" data-theme="אמונה">
    <span class="word"><span class="gl">שִׁוִּיתִי</span> <span class="gl">ה'</span> <span class="gl">לְנֶגְדִּי</span> <span class="gl">תָּמִיד</span></span>
  </p>
  <p class="line" data-theme="חכמה">
    <span class="word"><span class="gl">אוֹר</span> <span class="gl">הַבֵּירוּר</span> <span class="gl">חוֹתֵךְ</span> <span class="gl">עֲרָפֶל</span></span>
  </p>
  <div class="hint">גלול/רחף על השורות — האור יתעורר ✨</div>
<script>
const io=new IntersectionObserver(es=>{
  es.forEach(e=> e.target.classList.toggle('is-lit', e.isIntersecting));
},{threshold:0.35});
document.querySelectorAll('.line').forEach(l=>io.observe(l));
</script>
</body>
</html>
```

---

## 🧪 בדיקות איכות (QA) — Checklist קצר

- ✅ ניגודיות לפחות 4.5:1 לטקסט רגיל.
    
- ✅ “Reduced Motion” מכובד.
    
- ✅ הדפסה משאירה אלגנטיות ללא הבהובים.
    
- ✅ טעינת Presets מתאימה ל־Theme.
    
- ✅ “כתר לבן” לא מסנוור (חלון קצר < 200ms).
    

---

## 🗂️ סט קבצים לפתיחה (Roadmap זריז)

1. `themes.json` — 6-10 תמות פתיחה.
    
2. `effects.css` — Halo, Trail, Mask, Burst.
    
3. `glow.js` — מפעיל RGP ומנהל מצבי שורה.
    
4. `leaflet_01.html` — תבנית ראשונה.
    
5. `CONTRIBUTING.md` — איך מוסיפים סגולות ו־Presets.
    
6. `PRINT_GUIDE.md` — טיפוגרפיה, A4/A5, ריווח, DPI.
    

---

## 🚀 צעדי התחלה עכשיו

- בחר 3-5 פסוקים/משפטי אור יומיים.
    
- תייג כל שורה ב־`data-theme`.
    
- הדבק את תבנית ה-HTML למעלה ושמור כ־`leaflet_01.html`.
    
- פתח בדפדפן ו"כייל" את הנשימה עד שזה “יושב על הלב”.
    

---

## 🏷️ האשטגים

#RGBDivineLight #LeafletGlow #SparkReading #AnLoMinus #OpenTorahAI #CreativeHalacha #MysticUI #HolyPixels

---

## 📜 קרדיטים + מקורות מאגרים

- ✍️ ייזום ופיתוח קונספט: **AnLoMinus** (Moshe Leon Yakobov) — [GitHub](https://github.com/AnLoMinus) · [Site](https://anlominus.github.io/)
    
- 📁 מאגר הפרויקט (מומלץ): **RGB-Divine-Light** — יצירת תיקייה במבנה שהוצע לעיל
    
- 🎨 השראות עיצוביות פנימיות: **Style Framework — Holographic Halo & Sparks** (פרויקט קיים אצלך)
    
- 💡 שימוש הוגן: הטמעת טקסטים מקוריים שלך בלבד/ברשותך
    

---

## 🙌 בוא נתקדם

רוצה שאכין לך **preset `themes.json`** ראשון + **`effects.css`** בסיסי + **`leaflet_01.html`** מוכן להדפסה ואשמור כסט פתיחה? או שנבחר יחד 5 משפטי-אור לפתיחת המאגר ונייצר מהם עלון 1:1 מיד?