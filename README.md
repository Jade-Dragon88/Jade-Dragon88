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

#### 2. "Контент-комбайн": Полная автоматизация WordPress-блога
- **Задача:** Автоматизировать весь цикл создания контента: от идеи до публикации SEO-оптимизированной статьи с уникальным изображением.
- **Решение:** Построен мультиагентный n8n-workflow, где **каждый AI-агент выполняет свою роль**:
  - **Исследователь (Perplexity API):** Собирает информацию по теме.
  - **Копирайтер (GPT-4o):** Пишет текст статьи.
  - **SEO-специалист (GPT-4o-mini):** Формирует title, meta-description и slug.
  - **Верстальщик (GPT-4o-mini):** Преобразует текст в готовый HTML для WordPress.
  - **Промпт-инженер и художник (Hugging Face API):** Генерируют уникальное изображение для поста.
- **Стек:** `n8n`, `AI Agents`, `Perplexity API`, `GPT-4o`, `Hugging Face API`, `Wordpress API`.

#### 3. Система электронного учёта корпоративной техники
- **Задача:** Автоматизировать ручной процесс учёта и передачи ноутбуков между сотрудниками для экономии рабочего времени и устранения ошибок.
- **Решение:** Разработана веб-система с использованием `JavaScript` для фронтенда и `PowerShell` + `MS SQL` для бэкенда. Система построена на архитектуре MVC для удобства поддержки.
- **Результат:** Полное устранение ручных ошибок учёта и создание удобной для масштабирования системы.

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
