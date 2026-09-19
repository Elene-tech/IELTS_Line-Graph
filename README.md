# Module 1 · Line Graphs — інструкція з розміщення

Крок 1 — GitHub (5 хв)
1. Зайди на github.com → увійди → натисни «New repository».
2. Назва: `ielts-line-graphs` (будь-яка, без пробілів). Постав галочку «Public». Створи.
3. Натисни «uploading an existing file» → перетягни ВСІ файли з папки модуля
   (5 HTML-файлів + папку assets з 7 картинками) → «Commit changes».

Крок 2 — Vercel (3 хв)
1. Зайди на vercel.com → увійди через GitHub (кнопка «Continue with GitHub»).
2. «Add New…» → «Project» → знайди репозиторій `ielts-line-graphs» → «Import».
3. Нічого не змінюй у налаштуваннях → «Deploy». Через 30 секунд сайт готовий.
4. Vercel покаже посилання виду: https://ielts-line-graphs-xxx.vercel.app
   Перевір у браузері: відкрий, наприклад,
   https://ielts-line-graphs-xxx.vercel.app/01-overview-trainer.html

Крок 3 — Kwiga (2 хв)
1. У уроці Kwiga додай блок «HTML-код» (або «Код/iframe»).
2. Встав код (підстав своє посилання):

<iframe src="https://ТВОЄ-ПОСИЛАННЯ.vercel.app/01-overview-trainer.html"
        width="100%" height="900" style="border:none;border-radius:12px;"
        loading="lazy"></iframe>

3. Порядок уроців на платформі:
   1) Твоє відео (12–15 хв)
   2) 01-overview-trainer.html
   3) 02-grouping-trainer.html
   4) 03-parts-trainer.html
   5) 04-final-tasks.html
   6) 05-vocabulary.html (тримати відкритою під час письма)

Як оновити файл
- Зайди в репозиторій на GitHub → відкрий файл → олівець (Edit) → встав новий
  код → «Commit changes». Vercel оновить сайт сам за ~1 хвилину. Нічого більше
  робити не треба — iframe на Kwiga підтягне нову версію автоматично.

Англійська версія (на потім)
- У кожному HTML-файлі текст інтерфейсу зібраний у блоці `const UI = {...}` на
  початку <script> + статичні підписи в HTML. Для EN-версії: скопіюй репозиторій,
  переклади ці рядки — код не чіпаєш.
