# GameForge

**An offline, single-file game design whiteboard and Kanban board.**
Arabic by default with a full right-to-left layout, plus a one-click English toggle. It has a dark retro green-screen theme that is easy on the eyes at night, and it doesn't depend on anything external.

[العربية ↓](#بالعربية)

![GameForge whiteboard](docs/screenshots/whiteboard-en.png)

## Features

- **Infinite whiteboard** with 10 tools on a floating bottom toolbar: select, pan, freehand pen, sticky note, shape, text, image, table, checklist, stamp.
- **Editable objects.** Drag, resize, multi-select, recolor, duplicate and reorder anything, then double-click to edit it.
- **Images.** Upload, paste from the clipboard (Ctrl+V), or drag and drop onto the board.
- **Copy and paste objects** (Ctrl+C / Ctrl+X / Ctrl+V) with full undo and redo.
- **Kanban task board** with five stages (Backlog → To do → In progress → Review → Done). You can create, edit and delete tasks, drag them between columns, and set priority, discipline, assignee and due date. Search and filters are included.
- **Board → tasks.** Turn any sticky note, shape or checklist into tasks with one click.
- **Local saving.** Everything autosaves in your browser (IndexedDB with a localStorage fallback). Export and import your project as JSON for backups.
- **Starter project.** *Echoes of the Oasis* (أصداء الواحة) is a sample game design doc with a vision, core loop, creature table, MVP checklist and production tasks.
- **Private.** No accounts, no servers, no tracking. Your data never leaves your device.

![Kanban board](docs/screenshots/kanban-en.png)

## Getting started

**Use it online.** Open the GitHub Pages link for this repository (see *Deploy* below).

**Use it offline.** Download `index.html` and open it in any modern browser. That's all you need; there is no build step and nothing to install.

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`, and save.
4. After about a minute, the app is live at `https://<your-username>.github.io/<repo-name>/`.

## Keyboard shortcuts

| Key | Action | Key | Action |
|---|---|---|---|
| `V` | Select | `Shift + C` | Center board content |
| `H` / hold `Space` | Pan | `Ctrl + C / X / V` | Copy / cut / paste |
| `P` | Pen | `Ctrl + D` | Duplicate |
| `N` | Sticky note | `Ctrl + Z` / `Ctrl + Shift + Z` | Undo / redo |
| `R` | Shape | `Delete` | Delete selection |
| `T` | Text | `Ctrl + A` | Select all |
| `I` | Image | Arrow keys | Nudge (hold `Shift` for ×10) |
| `B` | Table | `Enter` / `Esc` | Edit / stop editing |
| `L` | Checklist | `Ctrl + Wheel`, `+` / `−`, `0` | Zoom |
| `S` | Stamp | `G` | Switch whiteboard / tasks |
| `?` | Show all shortcuts | | |

Shortcuts work on any keyboard layout, including Arabic, and they are ignored while you type in a field.

## Your data

Projects are stored in **your browser on your device**. Clearing site data, or opening the file in a different browser, will show a fresh project. Use **⋯ → Export project (JSON)** regularly to back up, and **Import project** to restore or move to another computer.

> When you open `index.html` directly from disk, some browsers keep separate storage for local files. For the most reliable saving, use the GitHub Pages link or always open the file from the same location.

## Browser support

Recent versions of Chrome, Edge, Firefox and Safari on desktop. Touch devices can view and pan, but the app is designed for a mouse and keyboard.

## Project structure

```
index.html              The whole app (HTML + CSS + JS in one file)
docs/screenshots/       Images used in this README
README.md
LICENSE
```

## License

[MIT](LICENSE). You are free to use, modify and share it.

---

<div dir="rtl">

## بالعربية

**GameForge** سبورة تصميم ألعاب ولوحة مهام (Kanban) في ملف واحد يعمل دون إنترنت.
الواجهة عربية افتراضياً مع دعم كامل للاتجاه من اليمين إلى اليسار، وزر للتبديل إلى الإنجليزية. التصميم داكن بطابع الشاشات الخضراء القديمة، مريح للعين ليلاً.

![السبورة](docs/screenshots/whiteboard-ar.png)

### المزايا

- **سبورة لا نهائية** فيها ١٠ أدوات على شريط عائم أسفل الشاشة: تحديد، تحريك، قلم حر، ملاحظة لاصقة، شكل، نص، صورة، جدول، قائمة مهام، ختم.
- **عناصر قابلة للتحرير**: سحب وتغيير حجم وتحديد متعدد وتلوين وتكرار وترتيب. انقر مرتين على أي عنصر لتحريره.
- **الصور**: ارفعها، أو الصقها بـ Ctrl+V، أو اسحبها وأفلتها على السبورة.
- **نسخ العناصر ولصقها** مع تراجع وإعادة كاملين.
- **لوحة مهام** بخمس مراحل: إنشاء وتعديل وحذف ونقل بالسحب، مع الأولوية والتخصص والمسؤول وتاريخ التسليم، وبحث وتصفية.
- **من السبورة إلى المهام**: حوّل أي ملاحظة أو شكل أو قائمة إلى مهام بنقرة واحدة.
- **حفظ تلقائي** في المتصفح على جهازك، مع تصدير المشروع واستيراده بصيغة JSON للنسخ الاحتياطي.
- **مشروع بداية** جاهز: «أصداء الواحة».
- **خصوصية تامة**: لا حسابات ولا خوادم، وبياناتك لا تغادر جهازك.

![لوحة المهام](docs/screenshots/kanban-ar.png)

### طريقة الاستخدام

- **عبر الإنترنت**: افتح رابط GitHub Pages الخاص بالمستودع.
- **دون إنترنت**: نزّل ملف `index.html` وافتحه في أي متصفح حديث، فلا يحتاج إلى أي تثبيت.

### النشر على GitHub Pages

١. ارفع المستودع إلى GitHub.
٢. افتح **Settings ← Pages**.
٣. من **Build and deployment** اختر **Deploy from a branch**، ثم الفرع `main` والمجلد `/ (root)`، واحفظ.
٤. بعد دقيقة تقريباً سيعمل التطبيق على الرابط `https://<اسم-المستخدم>.github.io/<اسم-المستودع>/`.

### بياناتك

تُحفظ المشاريع في متصفحك على جهازك فقط. إذا مسحت بيانات الموقع أو فتحت الملف في متصفح آخر فسيظهر مشروع جديد، لذلك صدّر مشروعك بانتظام من **⋯ ← تصدير المشروع (JSON)**.

### الترخيص

[MIT](LICENSE): مسموح لك استخدامه وتعديله ومشاركته بحرية.

</div>
