# Awesome Generative AI [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> Кураторский список современных проектов и сервисов генеративного искусственного интеллекта.

Генеративный искусственный интеллект - это технология, которая создает оригинальный контент, такой как изображения, звуки и тексты, используя алгоритмы машинного обучения, обученные на больших объемах данных. В отличие от других форм ИИ, он способен создавать уникальные и ранее невиданные результаты, такие как фотореалистичные изображения, цифровое искусство, музыка и письменные произведения. Эти результаты часто имеют свой собственный уникальный стиль и могут быть даже трудно отличимы от работ, созданных человеком. Генеративный ИИ имеет широкий спектр применений в таких областях, как искусство, развлечения, маркетинг, академические исследования и компьютерные науки.

Вклад в этот список приветствуется. Перед отправкой ваших предложений, пожалуйста, ознакомьтесь с [Руководством по внесению вклада](CONTRIBUTING.md), чтобы убедиться, что ваши записи соответствуют критериям. Добавляйте ссылки через [pull requests](https://github.com/steven2358/awesome-generative-ai/pulls) или создавайте [issue](https://github.com/steven2358/awesome-generative-ai/issues) для начала обсуждения. Больше проектов можно найти в [Списке открытий](DISCOVERIES.md), где мы представляем широкий спектр перспективных проектов генеративного ИИ.

## Содержание

- [Рекомендуемые материалы для чтения](#рекомендуемые-материалы-для-чтения) - Ключевые статьи и важные вехи в развитии генеративного ИИ
- [Текст](#текст) - Модели, чат-боты, поисковые системы и инструменты для работы с текстом
- [Программирование](#программирование) - ИИ-помощники для разработчиков и инструменты для работы с кодом
- [Агенты](#агенты) - Автономные ИИ-агенты и пользовательские ассистенты
- [Изображения](#изображения) - Генерация и редактирование изображений с помощью ИИ
- [Видео](#видео) - Создание и редактирование видео, аватары и анимация
- [Аудио](#аудио) - Преобразование текста в речь, распознавание речи и генерация музыки
- [Другое](#другое) - Различные инструменты и сервисы, не вошедшие в другие категории
- [Обучающие ресурсы](#обучающие-ресурсы) - Курсы, руководства и материалы для изучения генеративного ИИ
- [Дополнительные списки](#дополнительные-списки) - Другие полезные коллекции ресурсов по генеративному ИИ

## Рекомендуемые материалы для чтения

- [Как большие языковые модели преобразуют науку, общество и ИИ](https://hai.stanford.edu/news/how-large-language-models-will-transform-science-society-and-ai) - Статья, обобщающая возможности и ограничения модели GPT-3, а также её потенциальное влияние на общество. Авторы: Алекс Тамкин и Дип Гангули, 5 февраля 2021.
- [Генеративный ИИ: Новый творческий мир](https://www.sequoiacap.com/article/generative-ai-a-creative-new-world/) - Комплексное исследование индустрии генеративного ИИ, предлагающее историческую перспективу и глубокий анализ экосистемы отрасли. Авторы: Соня Хуанг, Пэт Грэди и GPT-3, 19 сентября 2022.
- [Презентация генеративного ИИ, новой одержимости Силиконовой долины](https://www.nytimes.com/2022/10/21/technology/generative-ai.html) - Статья о подъеме генеративного ИИ, особенно об успехе генератора изображений Stable Diffusion и связанных с ним спорах. New York Times, 21 октября 2022.
- [Новая творческая полоса ИИ вызывает золотую лихорадку в Силиконовой долине](https://www.wired.com/story/ais-new-creative-streak-sparks-a-silicon-valley-gold-rush/) - Статья о растущем ажиотаже и инвестициях в стартапы генеративного ИИ, с различными отраслями, исследующими его потенциальные применения. Wired, 27 октября 2022.
- [ChatGPT предвещает интеллектуальную революцию](https://www.wsj.com/articles/artificial-intelligence-generative-ai-chatgpt-kissinger-84512912) - Колонка Генри Киссинджера, Эрика Шмидта и Дэниела Хаттенлохера. Wall Street Journal, 24 февраля 2023.

### Важные вехи

- [OpenAI API](https://openai.com/blog/openai-api/) - Анонс OpenAI API для текстовых моделей общего назначения на основе GPT-3. Блог OpenAI, 11 июня 2020.
- [GitHub Copilot](https://github.blog/2021-06-29-introducing-github-copilot-ai-pair-programmer/) - Анонс Copilot, нового ИИ-напарника по программированию, который помогает писать лучший код. Блог GitHub, 29 июня 2021.
- [DALL·E 2](https://openai.com/blog/dall-e-2/) - Анонс выпуска DALL·E 2, продвинутой системы генерации изображений с улучшенным разрешением, расширенными возможностями создания изображений и различными мерами безопасности. Блог OpenAI, 6 апреля 2022.
- [Публичный релиз Stable Diffusion](https://stability.ai/blog/stable-diffusion-public-release) - Анонс публичного релиза Stable Diffusion, модели генерации изображений на основе ИИ, обученной на широком сканировании интернета и лицензированной под Creative ML OpenRAIL-M лицензией. Блог Stable Diffusion, 22 августа 2022.
- [ChatGPT](https://openai.com/blog/chatgpt/) - Анонс ChatGPT, разговорной модели, обученной отвечать на уточняющие вопросы, признавать ошибки, оспаривать неверные предпосылки и отклонять неуместные запросы. Блог OpenAI, 30 ноября 2022.
- [Поиск Bing](https://blogs.microsoft.com/blog/2023/02/07/reinventing-search-with-a-new-ai-powered-microsoft-bing-and-edge-your-copilot-for-the-web/) - Microsoft анонсирует новую версию своей поисковой системы Bing, работающую на модели OpenAI следующего поколения. Блог Microsoft, 7 февраля 2023.
- [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) - Llama LLM, базовая языковая модель с 65 миллиардами параметров от Meta. Meta, 23 февраля 2023. #opensource
- [GPT-4](https://openai.com/research/gpt-4) - Анонс GPT-4, большой мультимодальной модели. Блог OpenAI, 14 марта 2023.
- [DALL·E 3](https://openai.com/index/dall-e-3/) - Анонс генератора изображений DALL·E 3. Блог OpenAI, 20 сентября 2023.
- [Sora](https://openai.com/research/video-generation-models-as-world-simulators) - Презентация Sora, большой модели генерации видео. OpenAI, 15 февраля 2024.

---

## Текст

### Модели

- [OpenAI API](https://openai.com/api/) - API OpenAI предоставляет доступ к моделям GPT-3 и GPT-4, которые выполняют широкий спектр задач обработки естественного языка, и Codex, который переводит естественный язык в код.
- [Gopher](https://www.deepmind.com/blog/language-modelling-at-scale-gopher-ethical-considerations-and-retrieval) - Gopher от DeepMind - это языковая модель с 280 миллиардами параметров.
- [OPT](https://huggingface.co/facebook/opt-350m) - Open Pretrained Transformers (OPT) от Facebook - это набор предварительно обученных трансформеров только для декодирования. [Анонс](https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/). [Генерация текста OPT-175B](https://opt.alpa.ai/) размещена на Alpa.
- [Bloom](https://huggingface.co/docs/transformers/model_doc/bloom) - #opensource BLOOM от Hugging Face - это модель, похожая на GPT-3, которая была обучена на 46 различных языках и 13 языках программирования.
- [Llama](https://www.llama.com/) - #opensource Открытая языковая модель от Meta.
- [Claude](https://claude.ai/) - Общайтесь с Claude, ИИ-ассистентом от Anthropic.
- [Vicuna-13B](https://lmsys.org/blog/2023-03-30-vicuna/) - #opensource Открытый чат-бот, обученный путем тонкой настройки LLaMA на пользовательских беседах, собранных из ShareGPT.
- [Mistral](https://mistral.ai/en/models) - #opensource Передовые открытые LLM от Mistral AI.
- [Grok](https://grok.x.ai/) - #opensource LLM от xAI с [открытым исходным кодом](https://github.com/xai-org/grok-1) и открытыми весами.
- [Qwen](https://qwenlm.github.io/) - #opensource Серия LLM, независимо разработанных Alibaba Cloud.

### Чат-боты

- [ChatGPT](https://chatgpt.com/) - ChatGPT от OpenAI - это большая языковая модель, которая взаимодействует в разговорном стиле.
- [Copilot](https://copilot.microsoft.com/) - Повседневный ИИ-компаньон от Microsoft.
- [Gemini](https://gemini.google.com/) - Семейство мультимодальных больших языковых моделей, разработанных Google Deepmind.
- [Meta AI](https://www.meta.ai/) - ИИ-ассистент Meta для выполнения задач, создания ИИ-изображений, получения ответов. Построен на LLM Llama.
- [DeepSeek](https://www.deepseek.com/) - Передовые LLM для корпоративных, потребительских и научных приложений. #opensource
- [Character.AI](https://character.ai/) - Character.AI позволяет создавать персонажей и общаться с ними.
- [Pi](https://pi.ai) - Персонализированная ИИ-платформа, доступная как цифровой ассистент.
- [Qwen](https://chat.qwenlm.ai/) - Чат-бот Qwen с генерацией изображений, обработкой документов, интеграцией веб-поиска, пониманием видео и т.д.
- [Le Chat](https://chat.mistral.ai/) - Общайтесь с передовыми языковыми моделями Mistral AI.

### Пользовательские интерфейсы

- [LibreChat](https://librechat.ai/) - LibreChat - это бесплатный и открытый интерфейс чата для ИИ-ассистентов. [#opensource](https://github.com/danny-avila/LibreChat).
- [Chatbot UI](https://www.chatbotui.com/) - Открытый интерфейс ChatGPT. [#opensource](https://github.com/mckaywrigley/chatbot-ui).

### Поисковые системы

- [Perplexity AI](https://www.perplexity.ai/) - Инструменты поиска на базе ИИ.
- [Metaphor](https://metaphor.systems/) - Поиск на базе языковых моделей.
- [Phind](https://phind.com/) - Поисковая система на базе ИИ.
- [You.com](https://you.com/) - Поисковая система, построенная на ИИ, которая предоставляет пользователям персонализированный поиск, сохраняя их данные на 100% приватными.
- [Komo](https://komo.ai/) - Поисковая система на базе ИИ.

### Локальные поисковые системы

- [privateGPT](https://github.com/imartinez/privateGPT) - Задавайте вопросы своим документам без подключения к интернету, используя возможности LLM.
- [quivr](https://github.com/StanGirard/quivr) - Загрузите все свои файлы и общайтесь с ними, используя свой генеративный ИИ как вторую память, с помощью LLM и эмбеддингов.

### Помощники в написании

- [Jasper](https://www.jasper.ai/) - Создавайте контент быстрее с помощью искусственного интеллекта.
- [Compose AI](https://www.compose.ai/) - Compose AI - это бесплатное расширение для Chrome, которое сокращает время написания на 40% с помощью автодополнения на базе ИИ.
- [Rytr](https://rytr.me/) - Rytr - это ИИ-помощник в написании, который помогает создавать качественный контент.
- [wordtune](https://www.wordtune.com/) - Персональный помощник в написании.
- [HyperWrite](https://hyperwriteai.com/) - HyperWrite помогает писать с уверенностью и быстрее выполнять работу от идеи до финального черновика.
- [Moonbeam](https://www.gomoonbeam.com/) - Лучшие блоги за доли времени.
- [copy.ai](https://www.copy.ai/) - Пишите лучший маркетинговый текст и контент с помощью ИИ.
- [ChatSonic](https://writesonic.com/chat) - ИИ-помощник, который позволяет создавать текст и изображения.
- [Anyword](https://anyword.com/) - ИИ-помощник Anyword генерирует эффективный текст для всех.
- [Hypotenuse AI](https://www.hypotenuse.ai/) - Превратите несколько ключевых слов в оригинальные, проницательные статьи, описания продуктов и тексты для социальных сетей.
- [Lavender](https://www.lavender.ai/) - ИИ-помощник Lavender помогает получать больше ответов за меньшее время.
- [Lex](https://lex.page/) - Текстовый процессор со встроенным искусственным интеллектом, чтобы вы могли писать быстрее.
- [Jenni](https://jenni.ai/) - Jenni - это лучший помощник в написании, который экономит часы на генерации идей и написании.
- [LAIKA](https://www.writewithlaika.com/) - LAIKA обучает искусственный интеллект на вашем собственном письме, чтобы создать персонального творческого партнера.
- [QuillBot](https://quillbot.com) - Инструмент перефразирования на базе ИИ.
- [Postwise](https://postwise.ai/) - Пишите твиты, планируйте посты и увеличивайте количество подписчиков с помощью ИИ.
- [Copysmith](https://copysmith.ai/) - Решение для создания контента на базе ИИ для предприятий и электронной коммерции.

### Расширения ChatGPT

- [WebChatGPT](https://chrome.google.com/webstore/detail/webchatgpt-chatgpt-with-i/lpfemeioodjbpieminkklglpmhlngfcn) - Дополняйте ваши промпты ChatGPT релевантными результатами из интернета.
- [GPT for Sheets and Docs](https://workspace.google.com/marketplace/app/gpt_for_sheets_and_docs/677318054654) - Расширение ChatGPT для Google Sheets и Google Docs.
- [YouTube Summary with ChatGPT](https://chrome.google.com/webstore/detail/youtube-summary-with-chat/nmmicjeknamkfloonkhhcjmomieiodli) - Используйте ChatGPT для создания резюме видео на YouTube.
- [ChatGPT Prompt Genius](https://chrome.google.com/webstore/detail/chatgpt-prompt-genius/jjdnakkfjnnbbckhifcfchagnpofjffo) - Открывайте, делитесь, импортируйте и используйте лучшие промпты для ChatGPT и сохраняйте историю чата локально.
- [ChatGPT for Search Engines](https://chrome.google.com/webstore/detail/chatgpt-for-search-engine/feeonheemodpkdckaljcjogdncpiiban) - Отображает ответы ChatGPT рядом с результатами поиска Google, Bing и DuckDuckGo.
- [ShareGPT](https://sharegpt.com/) - Делитесь своими беседами с ChatGPT и исследуйте беседы, которыми поделились другие.
- [Merlin](https://merlin.foyer.work/) - Расширение ChatGPT Plus для всех веб-сайтов.
- [ChatGPT Writer](https://chatgptwriter.ai/) - Генерируйте целые электронные письма и сообщения с помощью ИИ ChatGPT.
- [ChatGPT for Jupyter](https://github.com/TiesdeKok/chat-gpt-jupyter-extension) - Добавляет различные вспомогательные функции в Jupyter Notebooks и Jupyter Lab, работающие на ChatGPT.
- [editGPT](https://www.editgpt.app/) - Легко проверяйте, редактируйте и отслеживайте изменения в вашем контенте в ChatGPT.
- [Forefront](https://www.forefront.ai/) - Лучший опыт использования ChatGPT.

### Продуктивность

- [ChatPDF](https://www.chatpdf.com/) - Общайтесь с любым PDF.
- [Mem](https://mem.ai/) - Mem - это первое в мире рабочее пространство на базе ИИ, персонализированное под вас. Усиливайте свою креативность, автоматизируйте рутину и оставайтесь организованными автоматически.
- [Taskade](https://www.taskade.com/) - Создавайте структурированные списки задач, заметок и интеллект-карты с помощью Taskade AI.
- [Notion AI](https://www.notion.so/product/ai) - Пишите лучшие, более эффективные заметки и документы.
- [Nekton AI](https://nekton.ai) - Автоматизируйте свои рабочие процессы с помощью ИИ. Описывайте свои рабочие процессы шаг за шагом простым языком.
- [Rewind](https://www.rewind.ai/) - Rewind - это персонализированный ИИ, работающий на основе всего, что вы видели, сказали или слышали.
- [NotebookLM](https://notebooklm.google/) - Онлайн-инструмент для исследований и заметок для работы с документами, работающий на Google Gemini.

### Помощники для встреч

- [Otter.ai](https://otter.ai/) - Помощник для встреч, который записывает аудио, пишет заметки, автоматически захватывает слайды и генерирует резюме.
- [Cogram](https://www.cogram.com/) - Cogram автоматически делает заметки на виртуальных встречах и определяет пункты действий.
- [Sybill](https://www.sybill.ai/) - Sybill генерирует резюме звонков по продажам, включая следующие шаги, болевые точки и области интереса, комбинируя транскрипт и инсайты на основе эмоций.
- [Loopin AI](https://www.loopinhq.com/) - Loopin - это совместное рабочее пространство для встреч, которое не только позволяет записывать, транскрибировать и резюмировать встречи с помощью ИИ, но и автоматически организовывать заметки поверх вашего календаря.
- [Fireflies.ai](https://fireflies.ai/) - Fireflies.ai помогает вашей команде транскрибировать, резюмировать, искать и анализировать голосовые разговоры.
- [Read AI](https://www.read.ai/) - ИИ-помощник для работы, делающий ваши встречи, электронные письма и сообщения более продуктивными с помощью резюме, обнаружения контента и рекомендаций.

### Академия

- [Elicit](https://elicit.org/) - Elicit использует языковые модели для автоматизации рабочих процессов исследований, таких как части обзора литературы.
- [genei](https://www.genei.io/) - Резюмируйте академические статьи за секунды и экономьте 80% времени на исследованиях.
- [Explainpaper](https://www.explainpaper.com/) - Лучший способ читать академические статьи. Загрузите статью, выделите непонятный текст, получите объяснение.
- [Galactica](https://galactica.org/) - Большая языковая модель для науки. Может резюмировать академическую литературу, решать математические задачи, генерировать статьи Wiki, писать научный код, аннотировать молекулы и белки и многое другое. [API модели](https://github.com/paperswithcode/galai).
- [Consensus](https://consensus.app/search/) - Consensus - это поисковая система, которая использует ИИ для поиска ответов в научных исследованиях.
- [Synthical](https://synthical.com) - Среда для совместных исследований на базе ИИ.
- [scite](https://scite.ai/) - Платформа для обнаружения и оценки научных статей.
- [SciSpace](https://typeset.io/) - ИИ-помощник для понимания научной литературы.
- [STORM](https://storm.genie.stanford.edu/) - Система курирования знаний на базе LLM, которая исследует тему и генерирует полный отчет с цитатами. [#opensource](https://github.com/stanford-oval/storm/)

### Таблицы лидеров
- [Chatbot Arena](https://lmarena.ai/) - Открытая платформа для краудсорсингового тестирования ИИ, размещенная исследователями из UC Berkeley SkyLab и LMArena.
- [Artificial Analysis](https://artificialanalysis.ai/) - Artificial Analysis предоставляет объективные тесты и информацию для выбора моделей ИИ и хостинг-провайдеров.
- [imgsys](https://imgsys.org/rankings) - Арена генеративных моделей изображений от fal.ai.

### Другие генераторы текста

- [EmailTriager](https://www.emailtriager.com/) - Используйте ИИ для автоматического составления ответов на электронные письма в фоновом режиме.
- [AI Poem Generator](https://www.aipoemgenerator.org) - Генератор стихов на базе ИИ пишет красивое рифмованное стихотворение на любую тему по текстовому запросу.

---

## Программирование

### Помощники по программированию

- [GitHub Copilot](https://github.com/features/copilot) - GitHub Copilot использует OpenAI Codex для предложения кода и целых функций в реальном времени прямо из вашего редактора.
- [OpenAI Codex](https://platform.openai.com/docs/guides/code/) - ИИ-система от OpenAI, которая переводит естественный язык в код.
- [Ghostwriter](https://blog.replit.com/ai) - ИИ-напарник по программированию от replit.
- [Amazon Q](https://aws.amazon.com/q/) - Помощник на базе генеративного ИИ от AWS, который помогает отвечать на вопросы, писать код и автоматизировать задачи.
- [tabnine](https://www.tabnine.com/) - Пишите код быстрее с автодополнением целых строк и функций.
- [Stenography](https://stenography.dev/) - Автоматическая документация кода.
- [Mintlify](https://mintlify.com/) - Писатель документации на базе ИИ.
- [Debuild](https://debuild.app/) - Инструмент с низким кодом на базе ИИ для веб-приложений.
- [AI2sql](https://www.ai2sql.io/) - С помощью AI2sql инженеры и не-инженеры могут легко писать эффективные, безошибочные SQL-запросы, не зная SQL.
- [CodiumAI](https://www.codium.ai/) - С помощью CodiumAI вы получаете нетривиальные тесты, предлагаемые прямо в вашей IDE, чтобы оставаться уверенным при отправке.
- [PR-Agent](https://github.com/Codium-ai/pr-agent) - Инструмент на базе ИИ для автоматического анализа PR, обратной связи, предложений и многого другого.
- [MutableAI](https://mutable.ai/) - Ускоренная разработка программного обеспечения с помощью ИИ.
- [TurboPilot](https://github.com/ravenscroftj/turbopilot) - Самодостаточный клон copilot, который использует библиотеку из llama.cpp для запуска модели Salesforce Codegen с 6 миллиардами параметров в 4 ГБ оперативной памяти.
- [GPT-Code UI](https://github.com/ricklamers/gpt-code-ui) - Открытая реализация интерпретатора кода ChatGPT от OpenAI. #opensource
- [MetaGPT](https://github.com/geekan/MetaGPT) - Фреймворк мульти-агентов: по одной строке требований возвращает PRD, дизайн, задачи, репозиторий
- [Open Interpreter](https://github.com/KillianLucas/open-interpreter) - Интерпретатор кода OpenAI в вашем терминале, работающий локально.
- [Continue](https://www.continue.dev/) - Открытый ИИ-помощник по коду. Подключайте любую модель и любой контекст для создания пользовательских автодополнений и чат-опыта внутри IDE. [#opensource](https://github.com/continuedev/continue)

### Инструменты разработчика

- [co:here](https://cohere.ai/) - Cohere предоставляет доступ к продвинутым большим языковым моделям и инструментам NLP.
- [Haystack](https://haystack.deepset.ai/) - Фреймворк для создания приложений NLP (например, агенты, семантический поиск, ответы на вопросы) с языковыми моделями.
- [LangChain](https://langchain.com/) - Фреймворк для разработки приложений на базе языковых моделей.
- [gpt4all](https://github.com/nomic-ai/gpt4all) - Чат-бот, обученный на огромной коллекции чистых данных ассистента, включая код, истории и диалоги.
- [LLM App](https://github.com/pathwaycom/llm-app) - Открытая Python-библиотека для создания конвейеров данных в реальном времени с поддержкой LLM.
- [LMQL](https://lmql.ai/) - LMQL - это язык запросов для больших языковых моделей.
- [LlamaIndex](https://www.llamaindex.ai/) - Фреймворк данных для создания приложений LLM поверх внешних данных.
- [Phoenix](https://phoenix.arize.com/) - Открытый инструмент для наблюдения за ML, который работает в вашей среде notebook, от Arize. Мониторинг и тонкая настройка моделей LLM, CV и табличных моделей.
- [Cursor](https://www.cursor.so/) - Cursor - это IDE будущего, созданная для парного программирования с мощным ИИ.
- [SymbolicAI](https://github.com/Xpitfire/symbolicai) - Нейро-символический фреймворк для создания приложений с LLM в основе.
- [Vanna.ai](https://vanna.ai/) - Открытый Python RAG фреймворк для генерации SQL и связанной функциональности. [#opensource](https://github.com/vanna-ai/vanna)
- [Portkey](https://portkey.ai/) - Полноценная платформа LLMOps для мониторинга, кэширования и управления LLM.
- [agenta](https://github.com/agenta-ai/agenta) - Открытая сквозная платформа LLMOps для инженерии промптов, оценки и развертывания. #opensource
- [Together AI](https://www.together.ai/) - Обучайте, тонко настраивайте и запускайте вывод на моделях ИИ быстро, с низкой стоимостью и в производственном масштабе.
- [Gitingest](https://gitingest.com/) - Превратите любой Git-репозиторий в простой текстовый дайджест его кодовой базы, чтобы его можно было загрузить в любой LLM. [#opensource](https://github.com/cyclotruc/gitingest)
- [Repomix](https://repomix.com/) - Упакуйте вашу кодовую базу в форматы, удобные для ИИ. [#opensource](https://github.com/yamadashy/repomix)
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Вывод модели LLaMA от Meta (и других) на чистом C/C++. #opensource
- [bitnet.cpp](https://github.com/microsoft/BitNet) - Официальный фреймворк вывода для 1-битных LLM от Microsoft. [#opensource](https://github.com/microsoft/BitNet)
- [OpenRouter](https://openrouter.ai/) - Унифицированный интерфейс для LLM. [#opensource](https://github.com/OpenRouterTeam)

### Песочницы
- [OpenAI Playground](https://platform.openai.com/playground) - Исследуйте ресурсы, учебные пособия, API-документацию и динамические примеры.
- [Google AI Studio](https://aistudio.google.com/) - Веб-инструмент для прототипирования с Gemini и экспериментальными моделями.
- [GitHub Models](https://github.com/marketplace/models) - Найдите и поэкспериментируйте с моделями ИИ для разработки приложения генеративного ИИ.

### Локальное развертывание LLM
- [Ollama](https://github.com/ollama/ollama) - Быстрое начало работы с большими языковыми моделями локально.
- [Open WebUI](https://github.com/open-webui/open-webui) - Расширяемая, многофункциональная и удобная самодостаточная платформа ИИ, разработанная для работы полностью офлайн. #opensource
- [Jan](https://jan.ai/) - Запускайте LLM, такие как Mistral или Llama2, локально и офлайн на вашем компьютере или подключайтесь к удаленным API ИИ. [#opensource](https://github.com/janhq/jan)
- [Msty](https://msty.app/) - Простой и мощный интерфейс для локальных и онлайн-моделей ИИ.
- [PyGPT](https://pygpt.net/) - Персональный настольный ИИ-ассистент с чатом, зрением, агентами, генерацией изображений, инструментами и командами, голосовым управлением и многим другим. #opensource
- [LLM](https://llm.datasette.io/) - Утилита CLI и Python-библиотека для взаимодействия с большими языковыми моделями, удаленными и локальными. [#opensource](https://github.com/simonw/llm)

---

## Агенты

### Автономные агенты

- [Auto-GPT](https://github.com/Torantulino/Auto-GPT) - Экспериментальная открытая попытка сделать GPT-4 полностью автономным.
- [babyagi](https://github.com/yoheinakajima/babyagi) - Система управления задачами на базе ИИ.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Собирайте, настраивайте и развертывайте автономных ИИ-агентов в вашем браузере.
- [GPT Engineer](https://github.com/AntonOsika/gpt-engineer) - Укажите, что вы хотите построить, ИИ попросит уточнений, а затем построит это.
- [GPT Prompt Engineer](https://github.com/mshumer/gpt-prompt-engineer) - Автоматическая инженерия промптов. Генерирует, тестирует и ранжирует промпты, чтобы найти лучшие.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Фреймворк мульти-агентов: по одной строке требований возвращает PRD, дизайн, задачи, репозиторий.
- [AutoGen](https://github.com/microsoft/autogen) - AutoGen - это фреймворк, который позволяет разрабатывать приложения LLM, используя несколько агентов, которые могут общаться друг с другом для решения задач.
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot) - Инструмент разработчика, который пишет масштабируемые приложения с нуля, пока разработчик контролирует реализацию.
- [Devin](https://devin.ai/) - Автономный ИИ-инженер программного обеспечения от Cognition Labs.
- [OpenDevin](https://github.com/OpenDevin/OpenDevin) - Автономный агент, разработанный для навигации по сложностям разработки программного обеспечения. #opensource
- [Davika](https://github.com/stitionai/devika) - Агентный ИИ-инженер программного обеспечения. #opensource

### Пользовательские ассистенты

- [Poe](https://poe.com/) - Poe предоставляет доступ к различным ботам.
- [GPT Builder](https://chat.openai.com/gpts/editor) - Ассистент для создания ассистентов на базе GPT.
- [GPTStore](https://gptstore.ai/) - Найдите полезные GPT. Поделитесь своими GPT.

---

## Изображения

### Модели

- [DALL·E 2](https://openai.com/dall-e-2/) - DALL·E 2 от OpenAI - это новая ИИ-система, которая может создавать реалистичные изображения и искусство из описания на естественном языке.
- [Stable Diffusion](https://huggingface.co/CompVis/stable-diffusion-v1-4) - Stable Diffusion от Stability AI - это современная модель преобразования текста в изображение, которая генерирует изображения из текста. #opensource
- [Midjourney](https://www.midjourney.com/) - Midjourney - это независимая исследовательская лаборатория, исследующая новые медиамысли и расширяющая воображаемые возможности человеческого вида.
- [Imagen](https://imagen.research.google/) - Imagen от Google - это модель диффузии текста в изображение с беспрецедентной степенью фотореализма и глубоким пониманием языка.
- [Make-A-Scene](https://ai.facebook.com/blog/greater-creative-control-for-ai-image-generation/) - Make-A-Scene от Meta - это мультимодальный метод генеративного ИИ, который дает творческий контроль в руки людей, позволяя им описывать и иллюстрировать свое видение как через текстовые описания, так и через свободные наброски.
- [DragGAN](https://github.com/XingangPan/DragGAN) - Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold.

### Сервисы

- [Craiyon](https://www.craiyon.com/) - Craiyon, ранее известный как DALL-E mini, - это модель ИИ, которая может рисовать изображения из любого текстового запроса.
- [DreamStudio](https://beta.dreamstudio.ai/) - DreamStudio - это удобный интерфейс для создания изображений с использованием модели генерации изображений Stable Diffusion.
- [Artbreeder](https://www.artbreeder.com/) - Artbreeder - это новый тип творческого инструмента, который расширяет возможности пользователей, делая сотрудничество и исследование более простым.
- [GauGAN2](http://gaugan.org/gaugan2/) - GauGAN2 - это мощный инструмент для создания фотореалистичного искусства с использованием комбинации слов и рисунков, поскольку он объединяет сегментационное картирование, инпаинтинг и генерацию изображений из текста в одной модели.
- [Magic Eraser](https://www.magiceraser.io/) - Удаляйте нежелательные элементы с изображений за секунды.
- [Imagine by Magic Studio](https://magicstudio.com/imagine) - Инструмент от Magic Studio, который позволяет вам выражать себя, просто описывая то, что у вас на уме.
- [Alpaca](https://www.getalpaca.io/) - Плагин Stable Diffusion для Photoshop.
- [Patience.ai](https://www.patience.ai/) - Patience.ai - это приложение для создания изображений с помощью Stable Diffusion, передового ИИ, разработанного Stability.AI.
- [GenShare](https://www.genshare.io/) - Создавайте искусство за секунды бесплатно. Владейте и делитесь тем, что создаете. Мультимедийная генеративная студия, демократизирующая дизайн и креативность.
- [Playground](https://playground.com/) - Playground - это бесплатный онлайн-создатель изображений на базе ИИ. Используйте его для создания искусства, постов в социальных сетях, презентаций, плакатов, видео, логотипов и многого другого.
- [Pixelz AI Art Generator](https://pixelz.ai/) - Pixelz AI Art Generator позволяет создавать невероятное искусство из текста. Доступны алгоритмы Stable Diffusion, CLIP Guided Diffusion и PXL·E realistic.
- [modyfi](https://www.modyfi.io/) - Редактор изображений, который вы всегда хотели. Креативные инструменты на базе ИИ в вашем браузере. Совместная работа в реальном времени.
- [Ponzu](https://www.ponzu.ai/) - Ponzu - это ваш бесплатный генератор логотипов на базе ИИ. Создавайте свой бренд с помощью креативно разработанных логотипов за секунды, используя только свое воображение.
- [PhotoRoom](https://www.photoroom.com/) - Создавайте фотографии продуктов и портреты, используя только свой телефон. Удаляйте фон, меняйте фон и демонстрируйте продукты.
- [Avatar AI](https://avatarai.me/) - Создавайте свои собственные аватары, сгенерированные ИИ.
- [ClipDrop](https://clipdrop.co/) - Создавайте профессиональные визуальные материалы без фотостудии, работает на базе [stability.ai](https://stability.ai/).
- [Lensa](https://prisma-ai.com/lensa) - Многофункциональное приложение для редактирования изображений, которое включает генерацию персонализированных аватаров с помощью Stable Diffusion.
- [RunDiffusion](https://rundiffusion.com/) - Облачное рабочее пространство для создания искусства, сгенерированного ИИ.
- [Ideogram](https://ideogram.ai/) - Платформа для создания изображений из текста, делающая креативное самовыражение более доступным.
- [Bing Image Creator](https://www.bing.com/images/create) - Генератор изображений из текста на базе DALLE·3 с функциями безопасности.
- [KREA](https://www.krea.ai/) - Создавайте высококачественные визуальные материалы с помощью ИИ, который знает о ваших стилях, концепциях или продуктах.
- [Nightcafe](https://creator.nightcafe.studio/) - NightCafe Creator - это приложение-генератор ИИ-искусства с несколькими методами генерации ИИ-искусства.
- [Leonardo AI](https://leonardo.ai/) - Создавайте визуальные ассеты производственного качества для ваших проектов с беспрецедентным качеством, скоростью и стилем.
- [Recraft](https://www.recraft.ai/) - Инструмент ИИ, который позволяет создателям легко генерировать и итерировать оригинальные изображения, векторную графику, иллюстрации, иконки и 3D-графику.
- [Reve Image](https://reve.art/) - Модель, обученная с нуля для превосходного следования промптам, эстетики и типографики.

### Графический дизайн

- [Brandmark](https://brandmark.io/) - Инструмент дизайна логотипов на базе ИИ.
- [Gamma](https://gamma.app/) - Создавайте красивые презентации и веб-страницы без форматирования и дизайнерской работы.
- [Microsoft Designer](https://designer.microsoft.com/) - Потрясающие дизайны в мгновение ока.

### Библиотеки изображений

- [Lexica](https://lexica.art/) - Поисковая система Stable Diffusion.
- [OpenArt](https://openart.ai/) - Поиск по 10M+ промптов и генерация ИИ-искусства через Stable Diffusion, DALL·E 2.
- [PromptHero](https://prompthero.com/) - Поиск промптов для моделей, таких как Stable Diffusion, ChatGPT, Midjourney и т.д.
- [PromptBase](https://promptbase.com/) - Поиск промптов от лучших инженеров промптов. Продавайте свои собственные промпты.

### Библиотеки моделей

- [Civitai](https://civitai.com/) - Инструмент обмена моделями ИИ, управляемый сообществом.
- [Stable Diffusion Models](https://rentry.org/sdmodels) - Полный список чекпоинтов Stable Diffusion на rentry.org.

### Ресурсы Stable Diffusion

- [Stable Horde](https://stablehorde.net/) - Распределенный кластер работников Stable Diffusion, созданный сообществом.
- [DiffusionDB](https://diffusiondb.com/) - Список всех публичных приложений, инструментов разработчика, руководств и плагинов для Stable Diffusion. [Версия Airtable](https://airtable.com/shr0HlBwbw3nZ8Ht3/tblxOCylXV8ynh7ti).
- [PublicPrompts](https://publicprompts.art/) - Коллекция бесплатных промптов для Stable Diffusion.
- [Stableboost](https://stableboost.ai/) - Stableboost - это Stable Diffusion WebUI, который позволяет быстро генерировать множество изображений, чтобы найти идеальные.
- [Hugging Face Diffusion Models Course](https://github.com/huggingface/diffusion-models-class) - Материалы на Python для онлайн-курса по моделям диффузии от [@huggingface](https://github.com/huggingface).

---

## Видео

- [Runway](https://runwayml.com/) - Волшебные инструменты ИИ, совместная работа в реальном времени, точное редактирование и многое другое. Ваш набор инструментов для создания контента следующего поколения.
- [Synthesia](https://www.synthesia.io/) - Создавайте видео из обычного текста за считанные минуты.
- [Rephrase AI](https://www.rephrase.ai/) - Технология Rephrase позволяет создавать гиперперсонализированные видео в масштабе, которые повышают вовлеченность и эффективность бизнеса.
- [Hour One](https://hourone.ai/) - Превращайте текст в видео с виртуальными ведущими автоматически.
- [Colossyan](https://www.colossyan.com/) - Создатель видео, ориентированный на обучение и развитие. Используйте ИИ-аватары для создания обучающих видео на нескольких языках.
- [Fliki](https://fliki.ai/) - Создавайте контент из текста в видео и текст в речь с помощью ИИ-голосов за считанные минуты.
- [Pictory](https://pictory.ai/) - Мощный ИИ Pictory позволяет создавать и редактировать видео профессионального качества с помощью текста.
- [Pika](https://pika.art/) - Платформа от идеи к видео, которая воплощает ваше творчество в движении.
- [Sora](https://openai.com/sora) - Модель ИИ, которая может создавать реалистичные и креативные сцены из текстовых инструкций.
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) - Модель ИИ, которая быстро создает высококачественные, реалистичные видео из текста и изображений.
- [Infinity AI](https://infinity.ai/) - Infinity - это базовая модель видео, которая позволяет создавать персонажей и оживлять их.
- [KLING AI](https://klingai.com/) - Инструменты для создания креативных изображений и видео.
- [Hailuo AI](https://hailuoai.video/) - Генератор видео из текста на базе ИИ.

### Аватары

- [D-ID](https://www.d-id.com/) - Создавайте и взаимодействуйте с говорящими аватарами одним нажатием кнопки.
- [HeyGen](https://app.heygen.com/) - Превращайте сценарии в говорящие видео с настраиваемыми ИИ-аватарами за считанные минуты.
- [RenderNet](https://rendernet.ai/) - RenderNet AI - это инструмент для генерации изображений и видео, предоставляющий контроль над дизайном персонажей, композицией и стилем.

### Анимация

- [Wonder Dynamics](https://wonderdynamics.com/) - Легко анимируйте, освещайте и компонуйте CG-персонажей в живые сцены.

---

## Аудио

### Преобразование текста в речь

- [Eleven Labs](https://beta.elevenlabs.io/) - Генератор ИИ-голосов.
- [Resemble AI](https://www.resemble.ai/) - Генератор ИИ-голосов и клонирование голоса для преобразования текста в речь.
- [WellSaid](https://wellsaidlabs.com/) - Преобразуйте текст в голос в реальном времени.
- [Play.ht](https://play.ht/) - Генератор ИИ-голосов. Создавайте реалистичное преобразование текста в речь онлайн с помощью ИИ. Преобразуйте текст в аудио.
- [podcast.ai](https://podcast.ai/) - Подкаст, полностью созданный искусственным интеллектом, работающий на базе ИИ-технологии преобразования текста в голос Play.ht.
- [VALL-E X](https://vallex-demo.github.io/) - Кросс-лингвальная нейронная кодек-языковая модель для кросс-лингвального синтеза речи.
- [TorToiSe](https://github.com/neonbjb/tortoise-tts) - Многоязычная система преобразования текста в речь, обученная с акцентом на качество. #opensource
- [Bark](https://github.com/suno-ai/bark) - Модель преобразования текста в аудио на основе трансформеров. #opensource

### Преобразование речи в текст

- [Whisper](https://openai.com/index/whisper/) - Надежное распознавание речи с помощью крупномасштабного слабого обучения. [#opensource](https://github.com/openai/whisper)
- [Wispr Flow](https://wisprflow.ai/) - Flow ускоряет написание с помощью бесшовного голосового ввода для любого приложения на вашем компьютере.
- [Vibe Transcribe](https://thewh1teagle.github.io/vibe/) - Комплексное решение для легкой транскрипции аудио и видео. [#opensource](https://github.com/thewh1teagle/vibe)
- [whisper.cpp](https://github.com/ggerganov/whisper.cpp) - Порт модели Whisper от OpenAI на C/C++. #opensource

### Музыка

- [Harmonai](https://www.harmonai.org/) - Мы - организация, управляемая сообществом, выпускающая инструменты генеративного аудио с открытым исходным кодом, чтобы сделать создание музыки более доступным и увлекательным для всех.
- [Mubert](https://mubert.com/) - Экосистема бесплатной музыки для создателей контента, брендов и разработчиков.
- [MusicLM](https://google-research.github.io/seanet/musiclm/examples/) - Модель от Google Research для генерации высококачественной музыки из текстовых описаний.
- [AudioCraft](https://audiocraft.metademolab.com/) - Единая кодовая база для генеративных аудио-потребностей от Meta. Включает MusicGen для музыки и AudioGen для звуков. #opensource
- [Stable Audio](https://stability.ai/stable-audio) - Stable Audio - первый продукт Stability AI для генерации музыки и звуковых эффектов.
- [AIVA](https://www.aiva.ai/) - Помощник по генерации музыки на базе ИИ. Выбирайте из более чем 250 стилей.
- [Suno AI](https://www.suno.ai/) - Каждый может создавать отличную музыку. Не нужны инструменты, только воображение. От вашей мысли к музыке.
- [Udio](https://www.udio.com/) - Открывайте, создавайте и делитесь музыкой со всем миром.

---

## Другое

- [Diagram](https://diagram.com/) - Волшебные новые способы проектирования продуктов.
- [PromptBase](https://promptbase.com/) - Маркетплейс для покупки и продажи качественных промптов для DALL·E, GPT-3, Midjourney, Stable Diffusion.
- [This Image Does Not Exist](https://thisimagedoesnotexist.com/) - Проверьте свою способность определять, создано ли изображение человеком или компьютером.
- [Have I Been Trained?](https://haveibeentrained.com/) - Проверьте, использовалось ли ваше изображение для обучения популярных моделей ИИ-искусства.
- [AI Dungeon](https://aidungeon.io/) - Текстовая приключенческая игра, которую вы направляете (и в которой играете главную роль), а ИИ оживляет её.
- [Clickable](https://www.clickable.so/) - Создавайте рекламу за секунды с помощью ИИ. Красивая, соответствующая бренду и высококонвертируемая реклама для всех маркетинговых каналов.
- [Scale Spellbook](https://scale.com/spellbook) - Создавайте, сравнивайте и развертывайте приложения на базе больших языковых моделей с помощью Scale Spellbook.
- [Scenario](https://www.scenario.com/) - Игровые ассеты, созданные с помощью ИИ.
- [Teleprompter](https://github.com/danielgross/teleprompter) - ИИ на устройстве для ваших встреч, который слушает вас и предлагает харизматичные цитаты.
- [FinChat](https://finchat.io/) - Используя ИИ, FinChat генерирует ответы на вопросы о публичных компаниях и инвесторах.
- [Morpher AI](https://morpher.com/ai) - Morpher AI предоставляет аналитику и анализ в реальном времени для любого рынка.
- [Whimsical AI](https://whimsical.com/ai) - Интеллект-карты, блок-схемы и визуальные инструменты на базе GPT для быстрой разработки идей и организации процессов.

---

## Обучающие ресурсы

- [Learn Prompting](https://learnprompting.org/) - Бесплатный курс с открытым исходным кодом по общению с искусственным интеллектом.
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - Руководство и ресурсы по инженерии промптов.
- [ChatGPT prompt engineering for developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) - Короткий курс от Исы Фулфорд (OpenAI) и Эндрю Нг (DeepLearning.AI).
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) - Примеры и руководства по использованию API OpenAI.
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) - Стратегии и тактики для получения лучших результатов от больших языковых моделей.
- [PromptPerfect](https://promptperfect.jina.ai/) - Инструмент для инженерии промптов.
- [Anthropic courses](https://github.com/anthropics/courses) - Образовательные курсы от Anthropic.
- [Build a Large Language Model (From Scratch)](https://www.manning.com/books/build-a-large-language-model-from-scratch) - Руководство по созданию собственной рабочей LLM, автор Себастьян Рашка.

---

## Дополнительные списки

- [Tools and Resources for AI Art](https://pharmapsychotic.com/tools.html) - Большой список Google Colab ноутбуков для генеративного ИИ, автор [@pharmapsychotic](https://twitter.com/pharmapsychotic).
- [The Generative AI Application Landscape](https://twitter.com/sonyatweetybird/status/1584580362339962880) - Инфографика, отображающая экосистему генеративного ИИ, автор [Sonya Huang](https://twitter.com/sonyatweetybird) из Sequioa Capital.
- [Startups - @builtwithgenai](https://airtable.com/shr6nfE9FOHp17IjG/tblL3ekHZfkm3p6YT) - Список Airtable от [@builtwithgenai](https://twitter.com/builtwithgenai).
- [The Generative AI Index](https://airtable.com/shrH4REIgddv8SzUo/tbl5dsXdD1P859QLO) - Список Airtable от [Scale Venture Partners](https://www.scalevp.com/generative-ai).
- [Generative AI for Games](https://twitter.com/gwertz/status/1593268767269670912) - Карта рынка компаний, работающих над генеративным ИИ для игр, от [a16z](https://a16z.com/).
- [Generative Deep Art](https://github.com/filipecalegario/awesome-generative-deep-art) - Кураторский список инструментов генеративного глубокого обучения, работ, моделей и т.д. для художественного использования, автор [@filipecalegario](https://github.com/filipecalegario).
- [GPT-3 Demo](https://gpt3demo.com/) - Витрина с примерами GPT-3, демо, приложениями, шоукейсом и вариантами использования NLP.
- [GPT-4 Demo](https://gpt4demo.com/) - Приложения и варианты использования GPT-4.
- [The Generative AI Landscape](https://github.com/ai-collection/ai-collection) - Коллекция замечательных приложений генеративного ИИ.
- [Molecular design](https://github.com/AspirinCode/papers-for-molecular-design-using-DL) - Список молекулярного дизайна с использованием генеративного ИИ и глубокого обучения.
- [Open LLMs](https://github.com/eugeneyan/open-llms) - Список открытых LLM, доступных для коммерческого использования.
