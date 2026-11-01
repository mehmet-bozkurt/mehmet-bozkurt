# Mehmet Bozkurt

[English](#english) · [Türkçe](#turkce)

<a id="english"></a>

**Software Architect · Technical Lead · Full-Stack Developer**

I design software systems, build developer tools, and explore practical ways to use AI in engineering.

My background spans backend development, software architecture, technical leadership, and end-to-end web applications. PHP and Laravel are at the core of my work, alongside modern JavaScript tools for the frontend.

Today, I’m bringing that experience into AI-assisted development: comparing coding models on real tasks, building verification workflows, and exploring the hardware and cost tradeoffs of local language models.

## Featured work

### [BenchForge](https://github.com/mehmet-bozkurt/BenchForge)

**Compare coding models. Inspect the results.**

A local evaluation environment that runs AI coding models against the same task and starting project through OpenCode. It brings automated checks, execution time, token usage, cost, and human evaluation into one comparison workflow.

- Validates outputs through lint, production build, static export, route checks, and browser smoke tests.
- Keeps separate workspaces for model runs and supports side-by-side output previews.
- Preserves first-attempt results while allowing failed runs to be retried and inspected.

`Laravel` · `SQLite` · `Node.js` · `OpenCode` · `Playwright`

*Early-stage, single-user tool for local use. Results are specific to the tasks and conditions tested.*

### [Local AI Feasibility Dashboard](https://github.com/mehmet-bozkurt/turkiye-local-llm-rehberi)

**Explore what it takes to run AI locally.**

An interactive research tool for comparing model requirements, hardware capacity, inference runtimes, and local-versus-cloud costs. Built from my research into the practical tradeoffs of running language models on personal hardware.

- Explores memory requirements and hardware options across different use cases.
- Compares inference runtimes and model deployment considerations.
- Includes interactive cost estimates, feasibility views, and a decision guide.

`React` · `TypeScript` · `Vite` · `Tailwind CSS` · `Recharts`

*Research tool with Turkish content. Data and estimates are approximate, not official benchmarks.*

## Engineering focus

- **Architecture & backend:** application boundaries, relational data models, APIs, authorization, and maintainable business systems.
- **Full-stack delivery:** connecting backend services, frontend interfaces, and operational requirements.
- **Developer tooling:** automating repetitive work and making development results easier to inspect.
- **AI-assisted engineering:** agent context, repeatable workflows, output verification, and model evaluation.

## Tools I work with

| Area | Technologies |
| --- | --- |
| Backend & data | PHP, Laravel, CodeIgniter, MySQL, MariaDB, Redis |
| Frontend | JavaScript, TypeScript, Vue.js, React, Next.js, Tailwind CSS |
| Infrastructure | Linux, Nginx, Docker, Cloudflare, Git, CI/CD |
| AI workflows & experimentation | OpenCode, Claude Code, Cursor, OpenRouter, MCP, Playwright |

## How I approach the work

I start with the problem, the data relationships, and the constraints. I care about how a system will be tested, maintained, and operated as much as how it is built.

When working with AI, I focus on preserving useful context and checking the resulting software. Tests, working outputs, execution time, and cost help me decide which approaches are useful in practice.

Outside web development, I’m interested in game development, 3D printing, and robotics prototyping.

---

<a id="turkce"></a>

## Türkçe

[English ↑](#english)

**Yazılım Mimarı · Teknik Lider · Full-Stack Geliştirici**

Yazılım sistemleri tasarlıyor, geliştirici araçları üretiyor ve yapay zekânın yazılım mühendisliğindeki pratik kullanım alanlarını araştırıyorum.

Geçmişim backend geliştirme, yazılım mimarisi, teknik liderlik ve uçtan uca web uygulaması geliştirmeyi kapsıyor. Çalışmalarımın merkezinde PHP ve Laravel; frontend tarafında ise modern JavaScript araçları yer alıyor.

Bugün bu deneyimi AI destekli geliştirmeye taşıyorum: kodlama modellerini gerçek görevlerle karşılaştırıyor, doğrulama süreçleri geliştiriyor ve yerel dil modellerinin donanım ve maliyet açısından getirdiği tercihleri inceliyorum.

## Öne çıkan çalışmalar

### [BenchForge](https://github.com/mehmet-bozkurt/BenchForge)

**Kodlama modellerini karşılaştır. Sonuçları incele.**

AI kodlama modellerini OpenCode üzerinden aynı görev ve başlangıç projesiyle çalıştıran, yerel bir değerlendirme ortamı. Otomatik kontrolleri, çalışma süresini, token kullanımını, maliyeti ve insan değerlendirmesini tek bir karşılaştırma sürecinde bir araya getiriyor.

- Üretilen çıktıları lint, production build, statik dışa aktarma, rota kontrolleri ve tarayıcı çalışma testleriyle doğrular.
- Her model için ayrı çalışma alanları tutar ve çıktıları yan yana incelemeyi sağlar.
- Başarısız çalışmaları yeniden denemeye ve incelemeye imkân verirken ilk teslimin sonuçlarını korur.

`Laravel` · `SQLite` · `Node.js` · `OpenCode` · `Playwright`

*Erken aşamada, tek kullanıcılı ve yerel kullanım için geliştirilen bir araç. Sonuçlar, denenen görevler ve çalışma koşullarıyla sınırlıdır.*

### [Türkiye Yerel LLM Rehberi](https://github.com/mehmet-bozkurt/turkiye-local-llm-rehberi)

**Yapay zekâyı yerelde çalıştırmak için neler gerektiğini keşfet.**

Model gereksinimlerini, donanım kapasitesini, model çalıştırma araçlarını ve yerel/bulut maliyetlerini karşılaştıran etkileşimli bir araştırma uygulaması. Dil modellerini kişisel donanımlarda çalıştırmanın pratik yönlerine ilişkin araştırmalarımdan doğdu.

- Farklı kullanım senaryolarında bellek gereksinimlerini ve donanım seçeneklerini inceler.
- Model çalıştırma araçlarını ve kurulum tercihlerini karşılaştırır.
- Etkileşimli maliyet tahminleri, fizibilite görünümleri ve bir karar rehberi sunar.

`React` · `TypeScript` · `Vite` · `Tailwind CSS` · `Recharts`

*Türkçe içerikli bir araştırma aracı. Veriler ve tahminler yaklaşıktır; resmî benchmark sonuçları değildir.*

## Odaklandığım alanlar

- **Mimari ve backend:** uygulama sınırları, ilişkisel veri modelleri, API'ler, yetkilendirme ve bakımı kolay iş uygulamaları.
- **Uçtan uca geliştirme:** backend servislerini, kullanıcı arayüzlerini ve operasyonel ihtiyaçları birlikte ele alma.
- **Geliştirici araçları:** tekrarlanan işleri otomatikleştirme ve geliştirme sonuçlarını daha kolay incelenebilir hale getirme.
- **AI destekli mühendislik:** ajan bağlamı, tekrarlanabilir iş akışları, çıktı doğrulama ve model değerlendirme.

## Kullandığım araçlar

| Alan | Teknolojiler |
| --- | --- |
| Backend ve veri | PHP, Laravel, CodeIgniter, MySQL, MariaDB, Redis |
| Frontend | JavaScript, TypeScript, Vue.js, React, Next.js, Tailwind CSS |
| Altyapı | Linux, Nginx, Docker, Cloudflare, Git, CI/CD |
| AI iş akışları ve denemeler | OpenCode, Claude Code, Cursor, OpenRouter, MCP, Playwright |

## Çalışmaya yaklaşımım

İşe problemi, veri ilişkilerini ve kısıtları anlamakla başlıyorum. Bir sistemin nasıl geliştirileceği kadar nasıl test edileceğini, bakımının yapılacağını ve işletileceğini de önemsiyorum.

Yapay zekâyla çalışırken yararlı bağlamı korumaya ve ortaya çıkan yazılımı doğrulamaya odaklanıyorum. Testler, çalışan çıktılar, süre ve maliyet; hangi yaklaşımların pratikte işe yaradığını değerlendirmeme yardımcı oluyor.

Web geliştirmenin dışında oyun geliştirme, 3D baskı ve robotik prototiplemeyle ilgileniyorum.

[Başa dön ↑](#mehmet-bozkurt)
