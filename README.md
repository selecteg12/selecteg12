<div align="center">

<h1>Hi, I'm Egor</h1>

<p><strong>Data Analytics · Machine Learning · AI Applications</strong></p>
<p>Applied Mathematics & Informatics student · Moscow · Open to internships</p>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="SQL and PostgreSQL" />
  <img src="https://img.shields.io/badge/Machine_Learning-F7931E?style=flat-square&amp;logo=scikitlearn&amp;logoColor=white" alt="Machine learning" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/AI_Applications-7C3AED?style=flat-square" alt="AI applications" />
</p>

</div>

## About me

I'm a fourth-year Applied Mathematics and Informatics student. My projects cover search and ranking, product analytics, and applications that connect AI to useful tools.

I'm looking for internships in **data analytics, ML, or applied AI**. I'm also interested in **technical project management** and **AI-assisted prototyping**.

I use AI coding tools to develop prototypes, review generated code, test behaviour, and iterate on features. My focus is understanding the data, evaluating results, and making the application useful.

[Machine learning](#machine-learning) · [Data analytics](#data-analytics) · [AI and automation](#ai-and-automation) · [Applications and project delivery](#applications-and-project-delivery)

## Technologies used in my projects

| Area | Technologies and methods |
| --- | --- |
| Data analysis | Python, SQL, PostgreSQL, pandas, NumPy, Matplotlib, Seaborn, DataLens |
| Statistics | A/B testing, conversion analysis, confidence intervals, hypothesis testing |
| Search and ML | scikit-learn, LightGBM LambdaRank, TF-IDF, BM25, Recall@K |
| Computer vision | TensorFlow/Keras, CNNs, PyTorch, OpenCV, MediaPipe, facial landmarks, FastAPI |
| AI applications | LLM APIs, tool calling, Node.js, Telegraf, Supabase |
| Application development | JavaScript, TypeScript, React, Next.js, Tailwind CSS, Electron |
| Development workflow | Git, GitHub, Vercel, automated tests, AI-assisted development |

## Machine learning

| Project | Problem and approach | Results and scope |
| --- | --- | --- |
| [Avito search and ranking](https://github.com/selecteg12/bootcamp_av) | Retrieve relevant service listings with TF-IDF and BM25, then rerank candidates using LightGBM LambdaRank. | Reported platform Recall@50: **0.602930**. Local validation Recall@50: **0.5768** on unseen queries and **0.5902** on historical queries. |
| [Mogzilla](https://github.com/selecteg12/mogzilla) | Experimental portrait-scoring app with neural inference, 478 facial landmarks, technical image checks, and an interactive measurement breakdown. | Python/FastAPI backend and React/TypeScript frontend. Evaluation limitations and dataset provenance are documented; scoring is experimental. The current revision is deployed on Vercel, with public API and browser-upload checks documented. [Live app](https://facemetrics-ai.vercel.app). |
| [cat/dog CNN](https://github.com/selecteg12/cat-dog-CNN) | Cat/dog image classification with a custom convolutional neural network trained from scratch in TensorFlow/Keras. Audits 25,000 images, removes exact duplicates, and uses disjoint train/validation/test splits. | **90.18% test accuracy** (3,380 / 3,748 images). Includes a Colab notebook, learning curves, per-class metrics, screenshots, a photo demo, and batch CSV inference. No pretrained weights. |

## Data analytics

| Project | Question | Work and deliverable |
| --- | --- | --- |
| [BitMotion A/B test](https://github.com/selecteg12/bitmotion-ab-test) | Does a redesigned store interface improve seven-day purchase conversion? | User-level analysis of **9,963 users**, experiment checks, uplift and confidence intervals. Observed uplift: **1.73 percentage points**; the two-sided 95% confidence interval includes zero. Includes a reproducible script and saved results. |
| [Event ticket sales](https://github.com/selecteg12/event-ticket-sales-analysis) | How do demand, devices, regions, and ticket partners differ? | PostgreSQL queries, Python analysis, and a [DataLens dashboard](https://datalens.yandex/l4t1anvif4bm5?tab=mg). The source extract contains **290,849 orders**, with **214,408** in the processed Python sample; SQL and Python use different data slices. |
| [Real estate analysis](https://github.com/selecteg12/real-estate-analysis) | How do apartment characteristics, listing duration, and seasonal activity vary? | PostgreSQL queries using CTEs, window functions and percentiles, plus a [DataLens dashboard](https://datalens.yandex/ngd6s7nfao0u7). Listing removal is not treated as proof of a sale. |

## AI and automation

| Project | What it does | Technical focus |
| --- | --- | --- |
| [Planner AI Assistant](https://github.com/selecteg12/planner-ai-assistant) | Telegram interface for reading and updating tasks, events, habits, ideas, and reminders in a planner. | LLM tool calling, validated operations, account linking, deletion confirmation, persistent state, scheduled reminders, and automated tests. |

The assistant and the [Planner web app](https://github.com/selecteg12/planner-app) use the same Supabase data.

## Applications and project delivery

| Project | Product | Delivery artifacts |
| --- | --- | --- |
| [Planner](https://github.com/selecteg12/planner-app) | A personal planning web app with tasks, calendar, habits, and productivity statistics. | Next.js, React, Supabase and PostgreSQL. A separate Telegram AI integration is available in the assistant repository. |
| [English Buddy](https://github.com/selecteg12/english-buddy) | Windows companion for looking up selected English words and saving vocabulary, with a bundled English–Russian dictionary. | Electron, React, TypeScript and a C# Windows UI Automation helper. [Windows release](https://github.com/selecteg12/english-buddy/releases/tag/v0.1.3), [changelog](https://github.com/selecteg12/english-buddy/blob/codex/initial-release/CHANGELOG.md), and [verification report](https://github.com/selecteg12/english-buddy/blob/codex/initial-release/VERIFICATION.md). |

<details>
<summary>Learning resources</summary>

- [AI for Beginners](https://github.com/selecteg12/AI-For-Beginners) — personal study fork of Microsoft's curriculum.
- [ML for Beginners](https://github.com/selecteg12/ML-For-Beginners) — personal study fork of Microsoft's curriculum.

These are learning resources, with attribution to the original authors.

</details>

<!-- Before publishing, add your preferred public email, Telegram, and/or CV link here. -->

