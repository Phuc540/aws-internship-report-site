# AWS Internship Report Site

A personal internship report website built with **Hugo** and the **FCJ Workshop template**, documenting my internship experience at **Amazon Web Services Vietnam Co., Ltd.** The site is automatically deployed to **GitHub Pages** via GitHub Actions CI/CD.

🌐 **Live Site:** [https://github.com/Phuc540/aws-internship-report-site](https://github.com/Phuc540/aws-internship-report-site)

---

## 👤 Author

| Field | Info |
|---|---|
| **Full Name** | Le Minh Phuc |
| **Email** | phucle76765@gmail.com |
| **Phone** | 0938747802 |
| **University** | Ho Chi Minh City University of Technology |
| **Major** | Information Technology |
| **Class** | 22DTHJA2 |
| **Company** | Amazon Web Services Vietnam Co., Ltd. |
| **Position** | Frontend Developer |
| **Project** | GreenLens Kids |
| **Duration** | 20/04/2026 – 10/07/2026 |

---

## 🛠️ Tech Stack

| Tool | Version / Details |
|---|---|
| **Static Site Generator** | [Hugo Extended](https://gohugo.io/) |
| **Theme** | [hugo-theme-learn](https://github.com/matcornic/hugo-theme-learn) / FCJ Workshop template |
| **Hosting** | GitHub Pages |
| **CI/CD** | GitHub Actions |
| **Languages** | English 🇺🇸 / Vietnamese 🇻🇳 (bilingual) |
| **Content Format** | Markdown |

---

## 📁 Project Structure

```txt
aws-internship-report-site/
│
├── .github/
│   └── workflows/
│       └── deploy-pages.yml                                # CI/CD: auto-build & deploy to GitHub Pages
│
├── archetypes/
│   └── default.md                                          # Default front-matter template for new pages
│
├── content/                                                # All site content (bilingual: .md & .vi.md)
│   ├── _index.md                                           # Homepage (English)
│   ├── _index.vi.md                                        # Homepage (Vietnamese)
│   │
│   ├── 1-Worklog/                                          # Weekly activity log (11 weeks)
│   │   ├── _index.md                                       # Worklog overview (English)
│   │   ├── _index.vi.md                                    # Worklog overview (Vietnamese)
│   │   ├── 1.1-Week1/
│   │   ├── 1.2-Week2/
│   │   ├── 1.3-Week3/
│   │   ├── 1.4-Week4/
│   │   ├── 1.5-Week5/
│   │   ├── 1.6-Week6/
│   │   ├── 1.7-Week7/
│   │   ├── 1.8-Week8/
│   │   ├── 1.9-Week9/
│   │   ├── 1.10-Week10/
│   │   ├── 1.11-Week11/
│   │   └── 1.12-Week12/
│   │
│   ├── 2-Proposal/                                         # Internship proposal / project plan
│   │
│   ├── 3-BlogsTranslated/                                  # Translated AWS blogs
│   │   ├── 3.1-Blog1/
│   │   ├── 3.2-Blog2/
│   │   └── 3.3-Blog3/
│   │
│   ├── 4-EventParticipated/                                # Events attended during internship
│   │   ├── _index.md                                       # Events overview (English)
│   │   ├── _index.vi.md                                    # Events overview (Vietnamese)
│   │   ├── 4.1-Event1/                                     # FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture
│   │   └── 4.2-Event2/                                     # Amazon Web Services (AWS): Enterprise Cloud Architectures and Industry Applications
│   │
│   ├── 5-Workshop/                                         # Technical workshop documentation
│   │   └── 5.1-GreenLens-project-development-process/
│   │
│   ├── 6-Self-evaluation/                                  # Intern self-assessment criteria table
│   └── 7-Feedback/                                         # Sharing and feedback section
│
├── layouts/
│   ├── partials/
│   │   ├── custom-footer.html                              # Custom footer override
│   │   ├── logo.html                                       # Custom logo partial
│   │   └── menu-footer.html                                # Menu footer partial
│   └── shortcodes/
│       ├── ghcontributors.html                             # GitHub contributors shortcode
│       ├── tab.html                                        # Tab shortcode
│       └── tabs.html                                       # Tabs container shortcode
│
├── static/
│   ├── AWS_Logo.svg                                        # AWS logo asset
│   ├── css/
│   │   ├── theme-mine.css                                  # Custom theme CSS
│   │   └── theme-workshop.css                              # Workshop theme CSS variant
│   ├── fonts/                                              # Custom fonts
│   └── images/
│       ├── Avatar.JPG                                      # Author profile picture
│       ├── favicon.png                                     # Site favicon
│       ├── favicon-16x16.png
│       ├── 2-Proposal/                                     # Images for Proposal section
│       ├── 4-EventParticipated/                            # Images for Events section
│       └── 5-Workshop/                                     # Images for Workshop section
│
├── themes/
│   └── hugo-theme-learn/                                   # Git submodule: FCJ Learn theme
│
├── config.toml                                             # Main Hugo site configuration
├── .gitmodules                                             # Git submodule reference (theme)
├── .gitignore                                              # Ignores public/, logs, editor files
└── README.md                                               # This file
```

---

## 📋 Report Contents

The site is organized into 7 main sections:

| # | Section | Description |
|---|---|---|
| 1 | **Worklog** | Weekly activity logs covering 12 weeks of internship |
| 2 | **Proposal** | Internship plan and project proposal |
| 3 | **Blogs Posted** | Three blog posts about AWS Cloud, AI, frontend development, API integration, and the GreenLens Kids project |
| 4 | **Events Participated** | Events and meetups attended during the internship period |
| 5 | **Workshop** | Step-by-step technical lab documentation |
| 6 | **Self-evaluation** | Self-assessment across professional and technical criteria |
| 7 | **Sharing & Feedback** | Personal reflections, lessons learned, and feedback |

---

## 🗓️ Worklog Summary

The worklog section summarizes my internship progress over 11 weeks. During this period, I learned AWS cloud fundamentals, practiced with AWS Skill Builder labs, and applied the knowledge to the **GreenLens Kids** project.

| Week | Main Focus |
|---|---|
| **Week 1** | Getting Started with AWS: Accounts, Console & CLI |
| **Week 2** | Core AWS Services in Practice: EC2, S3, IAM, VPC & CloudWatch |
| **Week 3** | Hands-on AWS & Kickstarting GreenLens Kids |
| **Week 4** | AWS Skill Builder Labs & Project Foundation Development |
| **Week 5** | Advanced AWS Architecture & Project Structure Setup |
| **Week 6** | Security Deep Dive & Initial UI / Backend Development |
| **Week 7** | Architecture Review & Core API Development |
| **Week 8** | Full Integration: Backend, Frontend & AI Camera Feature |
| **Week 9** | Mini Game System: API Completion & Frontend Integration |
| **Week 10** | Code Refactoring, Admin Dashboard & Personal Profile Page |
| **Week 11** | Final Polish, GitHub Pages Deployment & Project Wrap-up |

---

## 🧩 Project Contribution: GreenLens Kids

During the internship, I participated in the **GreenLens Kids** project as a **Frontend Developer**.

My main responsibilities included:

- Designing and improving UI screens using **Figma**
- Developing the **Character Creation** screen for children
- Integrating the **Child Profile Creation API**
- Building and improving the **AI Camera Result** interface
- Integrating mascot voice guidance
- Designing and integrating the **Daily Streak UI**
- Working with API responses, loading states, error handling, and client-side data storage
- Adjusting UI/UX for the **GreenLens Admin Dashboard**
- Testing user flows and fixing frontend issues based on feedback

Through these tasks, I improved my frontend development skills, UI/UX thinking, API integration ability, teamwork, and practical understanding of product development.

---

## 🎤 Events Participated

During the internship, I participated in two FCAJ community events:

| Event | Date | Main Topics |
|---|---|---|
| **FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture** | 13/06/2026 | DevOps, scalable AWS architecture, AWS community journey, Data Analytics, and MNC working culture |
| **Amazon Web Services (AWS): Enterprise Cloud Architectures and Industry Applications** | 04/07/2026 | Enterprise cloud architectures, industry applications, Vietnam’s cloud job market, Data Platform, personal development, and AI-ready fresher skills |

These events helped me gain broader perspectives on the IT industry, cloud computing, AWS architecture, DevOps, data analytics, enterprise applications, personal growth, and career preparation in the AI era.

---

## 🔬 Workshop

The workshop section documents the technical practice and project-related work completed during the internship. It focuses on applying AWS knowledge, frontend development, UI/UX design, and API integration to the **GreenLens Kids** project.

Main topics covered in the workshop include:

- Understanding the project idea and user flow of GreenLens Kids
- Preparing the required tools, project structure, and development environment
- Designing and improving UI/UX screens for children using Figma
- Building frontend interfaces and connecting them with backend APIs
- Handling API responses, loading states, error cases, and client-side data
- Testing feature flows and improving the user experience
- Reviewing the implementation and documenting the final results

This section helped me understand how technical knowledge, AWS learning, frontend development, and project documentation can be combined in a practical internship project.

---

## 🚀 Getting Started (Local Development)

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/)
- Git

### Clone & Run

```bash
# Clone with submodules because the theme is included as a Git submodule
git clone --recurse-submodules https://github.com/Phuc540/aws-internship-report-site
cd aws-internship-report-site

# Start local development server
hugo server -D
```

The site will be available at:

```txt
http://localhost:1313/aws-internship-report-site/
```

> If you already cloned without `--recurse-submodules`, run:
>
> ```bash
> git submodule update --init --recursive
> ```

---

## ⚙️ Configuration

The main configuration is in [`config.toml`](./config.toml):

- **`baseURL`** – Set to the GitHub Pages URL
- **`theme`** – `hugo-theme-learn` / FCJ Workshop template
- **`themeVariant`** – Custom AWS-styled workshop theme
- **`defaultContentLanguage`** – `en` as the default language
- **Multilingual** – Configured for English and Vietnamese
- **Menu shortcuts** – Links to GitHub repository and AWS FCJ Study Group

---

## 🔄 CI/CD Deployment

Deployments are automated via **GitHub Actions** (`.github/workflows/deploy-pages.yml`):

1. **Trigger:** Push to the `main` branch or manual `workflow_dispatch`
2. **Build job:**
   - Checks out source code with submodules
   - Installs Hugo Extended
   - Builds the site with Hugo
   - Uploads the build artifact
3. **Deploy job:**
   - Deploys the built artifact to GitHub Pages

---

## 🌏 Multilingual Support

All main content pages are available in both **English** and **Vietnamese**:

- English pages: `_index.md`
- Vietnamese pages: `_index.vi.md`

Language switching is available in the site navigation.

---

## 🔗 Links

- 📁 [GitHub Repository](https://github.com/Phuc540/aws-internship-report-site)
- 👥 [AWS FCJ Study Group (Facebook)](https://www.facebook.com/groups/awsstudygroupfcj/)
- 🎨 [Hugo Theme Learn](https://github.com/matcornic/hugo-theme-learn)
- Linkedin: https://www.linkedin.com/in/minh-ph%C3%BAc-9155a8403/