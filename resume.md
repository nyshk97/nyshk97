# Tsubasa Namatame

Yokohama, Japan (JST / UTC+9)

## Summary

Freelance backend engineer with approximately 7 years of experience building and maintaining web services since October 2019. Primarily focused on Ruby on Rails, with additional experience in Python, TypeScript, and PHP.

Core strengths include backend performance optimization (reduced page load times by up to 67% on a 30M MAU service), Ruby version upgrades (led Ruby 2 → 3 migration), and architecture improvements (led modular monolith migration using Packwerk). Primarily focused on backend and infrastructure, with the ability to handle frontend work when needed. Able to ramp up quickly on legacy codebases with minimal documentation — once took over a project after the entire engineering team had left, rebuilt documentation, error monitoring, and development workflows from scratch.

## Skills

| Skill | Years | Details |
|---|---|---|
| Ruby on Rails | 7 | Primary expertise. Version upgrades, performance optimization, architecture improvements |
| TypeScript | 4 | Backend and frontend |
| Python | 1 | AI integration layer using LiteLLM for multi-provider LLM routing |
| PHP | 2 | Laravel-based SaaS development |
| GraphQL | 2 | API design and implementation with Rails |
| AWS / Terraform | 5 | ECS, S3, EventBridge, Lambda, etc. IaC with Terraform/OpenTofu |
| Docker | 5 | Development and production environments |
| React / Next.js | 4 | SPA and SSR |

## Experience

### Freelance Engineer | Oct 2019 – Present

#### Lubis, Inc. — AI-Powered Slide Generation SaaS | Mar 2025 – Present
**Role:** Full-stack Engineer (team: ~20, engineers: 8)

**Stack:** Ruby on Rails, Next.js, TypeScript, Python, LiteLLM, Terraform (OpenTofu), AWS (ECS, EventBridge, ECR, S3), Docker, MySQL, Redis, Stripe

- Built CMS admin panel with Active Admin and designed v2 APIs for B2B features including folder/document CRUD, member management, and Stripe-based subscription billing
- Developed AI integration layer in Python using LiteLLM, implementing multi-provider routing (Gemini, Claude, GPT) for slide outline generation, content generation, cover design, and diagram generation
- Implemented Google Search grounding and async parallel processing for AI endpoints
- Managed EventBridge Scheduler with OpenTofu and improved CI/CD pipelines

#### Lincwell, Inc. — Online Medical Clinic Management System | Jun 2024 – Jun 2025
**Role:** Backend / Frontend Engineer (team: ~10, engineers: 4)

**Stack:** Ruby on Rails, GraphQL, React, TypeScript, Packwerk, Docker, AWS

- Developed appointment booking and medical record systems using Rails + GraphQL backend and React frontend in a Scrum team
- Integrated with ORCA (medical billing computer) APIs, navigating domain-specific data structures
- Led modular monolith migration using Packwerk — restructured domain boundaries and visualized dependency graphs across the monolithic Rails application

#### my best, Inc. — Product Comparison Media (30M MAU) | Oct 2023 – May 2024
**Role:** Backend Engineer (company: ~200, team: ~10, engineers: 2–5)

**Stack:** Ruby on Rails, GraphQL, Elasticsearch, Next.js, TypeScript, Docker, MySQL, Redis

- Focused on backend API development using Rails and GraphQL for a product comparison platform with 30M monthly unique users
- Identified and resolved performance bottlenecks through backend query optimization and data retrieval improvements, reducing page load times by up to 67%
- Evaluated infrastructure architecture and cost estimates for video content delivery
- Delivered RSS feeds, batch data processing, and various feature improvements in 2-week Scrum sprints

#### WAmazing, Inc. — Ski Resort Booking Platform for Inbound Tourists | Jun 2022 – Sep 2023
**Role:** Lead Engineer (company: ~160, team: ~20, engineers: 2–5)

**Stack:** Ruby on Rails, React, TypeScript, Docker, PostgreSQL, Redis, Heroku, CircleCI

- Joined as lead engineer after the entire senior engineering team had departed; rebuilt documentation, specs, and error monitoring from scratch
- Redesigned backend data models from the ground up for new product lines, including database schema, CSV ingestion format, and API integration
- Led Ruby 2 → 3 upgrade across the application
- Collaborated with a multicultural team (approximately half non-Japanese members) and coordinated with external partners and cross-functional departments

#### Laibo, Inc. — Company Review Platform (1.5M MAU) | Apr 2021 – May 2022
**Role:** Backend Engineer (company: ~40, engineers: 10)

**Stack:** Ruby on Rails, RSpec, Vue.js, Docker, ECS, MySQL, CircleCI, Terraform

- Conducted daily code reviews and drove feature improvements and test infrastructure enhancements
- Evaluated and introduced Autify for E2E testing, establishing team-wide testing workflows
- Ran data-driven UX improvements using Google Analytics and Redash, iterating through hypothesis → implementation → measurement cycles
- Contributed to engineering hiring: designed code-reading-based technical assessments and conducted interviews

#### Early Freelance Projects | Oct 2019 – Oct 2020
- Built an order management system from scratch as the sole engineer (requirements through deployment) using Ruby on Rails
- Designed and implemented web billing systems for 3 gas utility companies, translating requirements from non-technical stakeholders into multiple solution proposals

### Co-founder & CEO | Danmica, Inc. | Dec 2021 – Present
Operating developer-focused SaaS products ([HyperForm](https://hyperform.jp/), [malcheck](https://malcheck.com/)) with ~140 paying customers. Responsible for overall business operations as product owner.

### ChatPlus, Inc. | Intern → Full-time | Dec 2017 – Sep 2019
Built third-party API integrations for a chat SaaS product (team: ~10) using FuelPHP and AWS (EC2, RDS, S3, Lambda, SQS).

## Education

Sophia University — B.A. (2019)

## Publications

- Book: [個人Webサービスシステム構成事典](https://booth.pm/ja/items/2381283) (System Architecture Guide for Indie Web Services)
