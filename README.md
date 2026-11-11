# Arabic RTL Landing Page — صفحة هبوط عربية في ملف واحد

**[Live demo — المعاينة الحية](https://a7aadly1987-hub.github.io/arabic-landing-page/)**

[![Preview](preview/desktop.png)](https://a7aadly1987-hub.github.io/arabic-landing-page/)

صفحة هبوط عربية (RTL) كاملة في ملف `index.html` واحد: بدون مكتبات، بدون خطوات بناء، وبدون صور خارجية. افتح الملف في المتصفح وسيعمل مباشرة.

A complete Arabic (RTL) business landing page in a single `index.html`: no frameworks, no build step, no external images. Open the file and it works.

> **ملاحظة:** «نَسَق» اسم استوديو افتراضي للعرض فقط. الأرقام والشهادات وبيانات التواصل والمشاريع كلها محتوى تجريبي يُستبدل ببيانات صاحب الموقع.
>
> **Note:** "Nasaq" is a fictional studio used for the demo. All numbers, testimonials, contact details and projects are placeholder content.

## المزايا — Features

- عشرة أقسام: شريط تنقل ثابت، Hero، من نحن مع عدّادات متحركة، الخدمات، لماذا نحن، معرض الأعمال، آراء العملاء، أسئلة شائعة (أكورديون)، نموذج تواصل، تذييل
- وضع فاتح وداكن مع حفظ الاختيار
- متجاوب مع الموبايل والتابلت والديسكتوب، مع قائمة همبرغر
- حركات ظهور عند التمرير عبر `IntersectionObserver`، مع احترام `prefers-reduced-motion`
- نموذج تواصل بتحقق من المدخلات (اسم، إيميل أو هاتف، رسالة)
- إمكانية وصول: HTML دلالي، تنقل كامل بلوحة المفاتيح، `aria` وحالات focus واضحة
- كل الرسومات SVG مضمّنة وأشكال CSS
- وسوم SEO و Open Graph و favicon مضمّن

Ten sections, light/dark theme with persistence, fully responsive, scroll-reveal animations, validated contact form, keyboard accessible, inline SVG only, vanilla HTML/CSS/JS.

## التخصيص — Customize

1. **الألوان:** عدّل المتغيرات في `:root` أعلى الـ CSS (`--primary`, `--accent` …) وقيم الوضع الداكن تحتها.
2. **النصوص:** كل قسم يبدأ بتعليق مرقّم مثل `<!-- 4) الخدمات -->`.
3. **بيانات التواصل:** ابحث عن تعليق «بيانات التواصل» وغيّر الهاتف والإيميل ورقم واتساب.
4. **النموذج:** لا يرسل لأي خادم؛ اربطه بخدمتك في المكان المعلَّم داخل دالة الإرسال.

## Author

Ahmed Hendawy — [DIMA Digital Studio](https://github.com/a7aadly1987-hub)

## License

MIT
