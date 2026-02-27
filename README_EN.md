<div align="center">
  <strong>English</strong> | <a href="README.md">简体中文</a>
</div>

---
<div align="center">

# IndexDoc Open-Source Toolkit & Enterprise Solutions

</div>

IndexDoc is an open-source document toolkit and enterprise-grade AI document product suite built by **Hangzhou Zhiyuanshu Information Technology Co., Ltd.** It focuses on three core values: **efficiency, process simplification, and privacy & security**. It provides open-source tools for office and development scenarios, as well as industry-specific enterprise AI solutions, helping individuals, teams, and organizations eliminate repetitive work and fully improve productivity.

## About Us

📌 Author: Hangzhou Zhiyuanshu Information Technology Co., Ltd.

📧 Email: indexdoc@qq.com

🌐 Official Website: https://www.indexdoc.com/

We specialize in AI-driven document automation and enterprise knowledge management. We are committed to deeply integrating AI technology with professional services to deliver efficient, secure, and customizable solutions for office, development, legal, academic, government, and other fields.
Our core advantages: **AI + professional team dual-driven**, **end-to-end data security**, **efficient response and delivery**, balancing efficiency and quality to meet diverse user needs.

<div align="center">

## Core Open-Source Modules (Free on GitHub)

</div>

The following modules are open-source, free to use, modify, and distribute. Each can be deployed independently or combined to fit various scenarios, helping developers quickly solve practical pain points.

## Table of Contents

- [1. indexdoc-batch-generator (Batch Document Assistant)](https://github.com/indexdoc/indexdoc-batch-generator)
- [2. indexdoc-model-to-code (Code Generator / CodeAsst)](https://github.com/indexdoc/indexdoc-model-to-code)
- [3. indexdoc-ai-offline (Local Document AI Assistant)](https://github.com/indexdoc/indexdoc-ai-offline)
- [4. indexdoc-legal-assistant (Judicial Document Assistant)](https://github.com/indexdoc/indexdoc-legal-assistant)
- [5. indexdoc-editor (Markdown Editor)](https://github.com/indexdoc/indexdoc-editor)
- [6. indexdoc-converter (Document Converter)](https://github.com/indexdoc/indexdoc-converter)
- [7. indexdoc-vector (Vector Database)](https://github.com/indexdoc/indexdoc-vector)

### 1. indexdoc-batch-generator (Batch Document Assistant)
A template-driven, high-efficiency batch document generation tool built to solve **repetitive editing and inconsistent formatting**. Generate standardized professional documents in one click, eliminating tedious copy-paste work.

#### Core Advantages
- **High Efficiency**: Automates the full document generation workflow without manual replacement.
- **Eliminate Repetition**: Frees you from repeated document editing.
- **Reduce Human Errors**: Unified templates and rules avoid mistakes and ensure consistency.
- **Wide Application**: Supports legal documents, contracts, reports, notices, and more.

#### Core Functions
Supports uploading Excel data files and Word templates. Define filenames and fields in Excel; mark placeholders like `{column_name}` in Word. With simple configuration, click to generate all required documents in bulk.

### 2. indexdoc-model-to-code (Code Generator / CodeAsst)
CodeAsst is a high-efficiency code generator for teams and individuals, based on the philosophy:
**Data Model + Template = Code**. It enables batch, standardized code output to reduce repetitive work.

#### Core Features
- **Multi-data Source Support**: Imports PowerDesigner PDM, extracts models from Oracle, MySQL, SQL Server, PostgreSQL, or uses XML.
- **Flexible Template Syntax**: Velocity-like (Freemarker-compatible) for easy customization.
- **Batch Generation**: One template set outputs a complete project’s code and config files.
- **Broadly Applicable**: Ideal for model-first development.

#### Tool Value
The data model is the foundation of most systems. With CodeAsst, you can generate nearly all basic CRUD code in batches and quickly build multiple project demos to reduce development costs.

### 3. indexdoc-ai-offline (Local Document AI Assistant)
A lightweight, efficient, privacy-first local document AI tool that focuses on **local Q&A and information extraction** without uploading files to third-party platforms.

#### Core Advantages
- **Natural Interaction**: Ask questions in daily conversation.
- **Accurate Q&A**: Strong semantic understanding for precise answers.
- **In-depth Analysis**: Extracts key info and summarizes complex documents.
- **Privacy & Security**: All files processed locally, no cloud upload.
- **Knowledge Management**: Structured knowledge organization for individuals and teams.

#### Core Functions
Supports PDF, TXT, DOCX, etc. You can select single files or folders; the AI answers only based on selected content. Saves chat history for review. Clean interface, no complex configuration.

### 4. indexdoc-legal-assistant (Judicial Document Assistant)
A document tool designed for legal professionals to simplify judgment document production and improve efficiency and standardization for courts and law firms.

#### Core Workflow
Upload **indictment** and **court transcript** (PDF, DOCX supported) → Auto-generate judgment draft → Manual editing supported → Preview and export final version.

### 5. indexdoc-editor (Markdown Editor)
A lightweight, clean Markdown editor for developers and office users. Supports full Markdown syntax for documentation, notes, READMEs, etc.
Will continue iterating with export, shortcut customization, and more features.

### 6. indexdoc-converter (Document Converter)
indexdoc-converter is a Python-based library that converts mainstream office and web files to Markdown efficiently.

Supported formats:
- Word: `.docx`
- Excel-like: `.xlsx`, `.xls`, `.ods`, `.csv`, `.tsv`
- Web: `.html`, `.mhtml`, `.htm`, URLs
- PPT: `.pptx`

Available on PyPI and installable via `pip`.

### 7. indexdoc-vector (Vector Database)
indexdoc-vector is a lightweight, thread-safe, memory-mapped vector storage library with efficient cosine similarity search and vector management. Available on PyPI via `pip`.

- **Memory-mapped I/O**: Based on `numpy.memmap`, supports TB-level vectors with low memory usage
- **Thread-safe**: Built-in fair reentrant RWLock for high concurrency
- **Efficient Search**: Full-library cosine similarity and ID-range search
- **Vector Management**: Add, delete, compress, statistics
- **Minimal Dependencies**: Only NumPy required, no complex deployment

<div align="center">

## Enterprise-Grade AI Products & Services

</div>

In addition to open-source tools, we provide comprehensive enterprise AI document products and customized services for individuals, SMEs, and large organizations with industry-specific solutions.

### I. Personal AI Workbench
Runs fully locally with free trial. Hybrid architecture:
**Local storage + Local parsing + Cloud dialogue computing**, balancing performance and security.

Includes:
- Access to mainstream AI platforms
- Enhanced local document AI assistant
- Enhanced Markdown editor
- AI legal assistant for legal documents
- Paper assistant for rewriting and reducing AI traces
- Multi-account assistant for higher efficiency

✅ OS Support: Windows now; Linux, macOS, and Chinese OSes (Kylin, UOS, NeoKylin) coming soon.

✅ Extended: Connectable to enterprise knowledge bases with multi-level permission management for departments, roles, users, directories, and documents.

### II. AI Mirror Self
Trained offline from daily behavior data, an exclusive AI model that replicates your thinking, habits, and knowledge to act as your personalized AI mirror.

#### Core Functions
1. **Personalized Model Training**: Local data processing, continuous learning.
2. **Intelligent Dialogue**: Imitates your tone and logic for natural communication.
3. **Task Automation**: Handles emails, scheduling, document sorting, etc.
4. **Privacy & Security**: All processing local with enterprise encryption.

#### Technical Advantages
- Advanced deep learning & transfer learning
- Privacy-by-design: local only, end-to-end encryption
- Optimized for smooth performance on standard hardware
- Adaptive continuous learning

### III. AI Document Tools
An AI-powered document processing suite upgrading interaction and batch processing for individuals and enterprises.

#### Core Modules
1. **Chat with Documents**
   - Natural conversational interaction
   - Accurate Q&A and key information extraction
   - In-depth analysis and logic summarization
   - Structured enterprise knowledge management

2. **Batch Document Assistant (Enterprise Enhanced)**
Upgraded from open-source version with enterprise templates and complex field rules for high-volume, high-standard document production.

### IV. Efficiency Toolkit
Practical tools to optimize office workflows, lightweight and ready to use.

- **Multi-Account Assistant**: Log into multiple social/office accounts safely
- **Markdown Editor (Enhanced)**: AI grammar check, formatting, real-time preview
- **Local File Search**: AI semantic search with fast positioning
- **Document Comparer**: Highlights differences in PDF, DOCX, etc.
- **Archive Extractor**: AI content preview and selective extraction

### V. Document Services
AI-driven professional document customization and optimization for academic, legal, education, tech, and other fields, combining AI generation and expert review.

#### Full-Scenario Document Services
- **Paper Assistance**: Topic, literature, framework, charts
- **Paper Rewriting**: Reduce similarity while preserving meaning
- **Technical Documentation**: Whitepapers, manuals with professional terminology
- **Lesson Planning**: Syllabi, materials, exercises
- **Indictment Writing**: AI-assisted element extraction and legal matching
- **AI Trace Removal**: Polishes to human-like natural writing

#### Service Advantages
- **AI + Professional Team**: Efficiency + quality control
- **Full-process data security**: Encrypted transmission and local processing
- **Fast response**: Simple tasks in ~30 minutes

### VI. Enterprise-Grade AI Products (Industry Custom Solutions)
Customized AI products with private deployment and permission control to support digital transformation.

#### Core Products
1. **Enterprise AI Knowledge Base**: Private deployment, permission control, knowledge accumulation, smart recommendation.
2. **Judicial Document Assistant (Enterprise Enhanced)**: OCR, case retrieval, key-point extraction for legal institutions.
3. **AI Document Assistant**: Auto-generates contracts, reports, emails with templates and proofreading.
4. **Government Document AI Manager**: Policy library, official templates, format validation.

#### Enterprise Value
- Improve team efficiency by **40%+**
- Reduce annual costs by **¥200,000–500,000** for SMEs
- Protect knowledge assets from turnover loss

### VII. AI Product Customization Services
Full-cycle customization from requirement analysis, model training to system deployment, building tailored AI solutions deeply integrated with business processes.

#### Our Customization Capabilities
- **Industry-specific AI models**: Finance, healthcare, manufacturing, etc.
- **Enterprise system integration**: OA, CRM, ERP, no full reconstruction
- **Private deployment & security**: Local servers, encryption, role-based access
- **Multi-platform support**: Web, iOS/Android, Windows/macOS

#### Custom Solution Process
1. Requirement analysis and scenario definition
2. Model training, development, and demo verification
3. Deployment, testing, training, and continuous iteration

## Future Roadmap

### Open-Source Roadmap
Continuously optimize the 7 core open-source modules, fix issues, add features based on feedback, improve documentation and community support. Global developers are welcome to contribute.

### Enterprise Solution Roadmap
Expand industry coverage, enhance customization, optimize multi-platform adaptation, and deepen AI integration to deliver more efficient, secure, and tailored intelligent solutions.

## Contribution & Contact
Developers are welcome to Star, Fork, contribute code, and share suggestions to improve IndexDoc!

📧 Open-source inquiries / Enterprise cooperation: indexdoc@qq.com

🌐 More enterprise products & services: https://www.indexdoc.com/
