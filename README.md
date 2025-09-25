<h1 align="center">
  Овчинников Олег | Low-Code и AI-автоматизация (n8n)
</h1>

<h3 align="center">
  Специалист по созданию интеллектуальных систем на базе n8n, AI и Telegram-ботов.<br>Более 1 года опыта в коммерческой разработке и автоматизации.
</h3>

<div>
  <span>
    <div align="right">
      <a href="https://t.me/Nn_Ovchinnikov_Oleg">
        <img src="https://img.shields.io/badge/Ovchinnikov-blue?logo=telegram&logoColor=white&style=flat">
      </a>
      <a href="https://nn.hh.ru/resume/fd4ab6cfff06090a860039ed1f4d5a324c7945">
        <img src="https://img.shields.io/badge/HH-Ovchinnikov-red?labelColor=red&logoColor=white&style=flat">
      </a>
      <a href="https://www.linkedin.com/in/oleg-ovchinnikov-2bab08202/">
        <img src="https://img.shields.io/badge/Ovchinnikov-blue?logo=linkedin&logoColor=white&style=flat">
      </a>
    </div>
  </span>
</div>

---

<span>
  <img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/>
</span>
<span>
  <b>Рад вас видеть! Немного о себе:</b>
</span>
<p> </p>
<p>
Я — разработчик автоматизации, который помогает людям решать их задачи с помощью современных технологий. Моя философия — каждая автоматизация должна приносить измеримый результат, будь то экономия времени, сокращение издержек или создание нового продукта.
<br><br>
Убеждён в эффективности гибридного подхода: сочетание скорости Low-Code платформ (<b>n8n</b>) с гибкостью кастомной разработки (<b>JavaScript, Python</b>) и мощью AI-моделей (<b>GPT-4, YandexGPT, Perplexity</b>) позволяет создавать решения качественно нового уровня.
</p>

---

### :hammer_and_wrench: Ключевые компетенции и стек:

<table border="0" width="100%">
  <tbody border="0">
    <tr border="0" >
      <td border="0">
        <div>
          <br>
          <strong>Платформы и языки:</strong><br>
          <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/n8n.svg" title="n8n" alt="n8n" width="50" height="50"/>&nbsp;
          <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="50" height="50"/>&nbsp;
          <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="50" height="50"/>&nbsp;
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/powershell/powershell-original.svg" title="PowerShell" alt="PowerShell" width="50" height="50"/>&nbsp;
          <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="SQL" alt="SQL" width="50" height="50"/>&nbsp;
        </div>
        <div>
          <br><br>
          <strong>AI, Интеграции и Инфраструктура:</strong><br>
          <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/openai.svg" title="OpenAI" alt="OpenAI" width="50" height="50"/>&nbsp;
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-original.svg" title="Google & Yandex AI" alt="Google & Yandex AI" width="50" height="50"/>&nbsp;
          <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/telegram.svg" title="Telegram Bots" alt="Telegram Bots" width="50" height="50"/>&nbsp;
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/supabase/supabase-original.svg" title="Supabase" alt="Supabase" width="50" height="50"/>&nbsp;
          <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain.svg" title="Firebase" alt="Firebase" width="50" height="50"/>&nbsp;
        </div>
        <div>
          <br><br>
          <strong>Инструменты:</strong><br>
          <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="git" alt="git" width="50" height="50"/>&nbsp;
          <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original-wordmark.svg" title="github" alt="github" width="50" height="50"/>&nbsp;
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postman/postman-original.svg" title="Postman" alt="Postman" width="50" height="50"/>&nbsp;
          <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original-wordmark.svg" title="vscode" alt="vscode" width="50" height="50"/>&nbsp;
        </div>
      </td>
      <td border="0" bordercolor="white">
        <div>
          <img height="195px" align="right" alt="GitHub Languages" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Jade-Dragon88&layout=compact&theme=gruvbox_light&card_width=345&size_weight=0.5&count_weight=0.5" />
        </div>
      </td>
    </tr>
  </tbody>
</table>

---

### 🚀 Портфолио: Примеры проектов

#### 1. AI-юрист: RAG-система для консультаций по законодательству
- **Задача:** Создать Telegram-бота, способного давать точные ответы на вопросы по нормативно-правовым актам Республики Беларусь, используя актуальные документы.
- **Решение:** Разработан сложный n8n-workflow с **RAG-архитектурой (Retrieval-Augmented Generation)**. Система автоматически классифицирует запрос пользователя, проводит веб-скрейпинг сайта `normativka.by`, скачивает и парсит PDF-документы, преобразует их в векторы (embeddings) и загружает в базу данных **Supabase**. Ответ генерируется на основе найденных данных, что обеспечивает его точность и релевантность.
- **Стек:** `n8n`, `YandexGPT`, `OpenAI Embeddings`, `Supabase (Vector Store)`, `JavaScript`, `Web Scraping`.
- **Сcылка:** [Normativka](https://github.com/Jade-Dragon88/Normativka)

#### 2. "ChiefCook": Интеллектуальный кулинарный помощник с персонализированным поиском рецептов
- **Задача:** Создать Telegram-бота-шеф-повара, способного находить рецепты по названию блюда или доступным ингредиентам, с учетом особенностей русской кухни и разговорной лексики пользователей.
- **Решение:** Разработан сложный n8n-workflow с **двухуровневой системой поиска**. Бот использует **алгоритм Левенштейна** для коррекции орфографических ошибок в названиях ингредиентов и **семантический поиск синонимов** через Perplexity AI. Система содержит **словарь из 480+ продуктов** с числовыми кодами для интеграции с API 1000.menu. Бот имеет яркую **персональность "Дядюшки Кока"** - морского повара с агрессивным юмором. Workflow автоматически парсит HTML-страницы рецептов, извлекает фото, ингредиенты и пошаговые инструкции, адаптивно генерирует до 10 кнопок выбора рецептов.
- **Стек:** `n8n`, `Perplexity AI`, `1000.menu API`, `Telegram Bot API`, `HTML Parsing`, `Levenshtein Algorithm`, `JavaScript`.
- **Сcылка:** [ChefCook](https://github.com/Jade-Dragon88/ChefCook_workflow)

#### 3. "Perplexity Assistant": Универсальный интеллектуальный помощник с оптимизированной обработкой ошибок
- **Задача:** Построить надежного Telegram-бота для ответов на любые вопросы с акцентом на российскую юрисдикцию, способного корректно обрабатывать ошибки и форматировать длинные ответы для мессенджера.
- **Решение:** Создан усовершенствованный n8n-workflow версии 2.0 с **революционной системой обработки ошибок**. Вместо множественных SET-узлов используется **универсальный обработчик ошибок** с автоматическим определением источника через `$prevNode.name`. Система включает **трехэтапную обработку текста**: очистка от технических блоков `<think>`, преобразование числовых ссылок в URL, разбивка на части до 4000 символов с нумерацией. Все ответы проходят через **двойную AI-обработку**: Perplexity для контента и YandexGPT для форматирования под Telegram MarkdownV2.
- **Стек:** `n8n`, `Perplexity AI (sonar-reasoning)`, `YandexGPT`, `Telegram Bot API`, `Error Handling`, `Text Processing`.
- **Сcылка:** [Perplexity Assistant](https://github.com/Jade-Dragon88/Perplexity_For_Vera)

#### 4. Система электронного учёта корпоративной техники
- **Задача:** Автоматизировать ручной процесс учёта и передачи ноутбуков между сотрудниками для экономии рабочего времени и устранения ошибок.
- **Решение:** Разработана веб-система с использованием `JavaScript` для фронтенда и `PowerShell` + `MS SQL` для бэкенда. Система построена на архитектуре MVC для удобства поддержки.
- **Результат:** Полное устранение ручных ошибок учёта и создание удобной для масштабирования системы.
- **Стек:** `JavaScript`, `PowerShell`, `SQL`, `HTML`, `CSS`

---

### 🚀 Мои репозитории:

<p align="center">
  <a href="https://github.com/Jade-Dragon88/Perplexity_For_Vera">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Jade-Dragon88&repo=Perplexity_For_Vera&theme=gruvbox_light" alt="Perplexity_For_Vera">
  </a>
  <a href="https://github.com/Jade-Dragon88/ChefCook_workflow">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Jade-Dragon88&repo=ChefCook_workflow&theme=gruvbox_light" alt="ChefCook_workflow">
  </a>
</p>

---

### ✍️ Моя активность:

![commits](./profile-3d-contrib/profile-green-animate.svg)
