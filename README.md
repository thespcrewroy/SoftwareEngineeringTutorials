# Software Engineering Tutorials

<details>
<summary>📖 Table of Contents</summary>
<br />

- [Backend](#backend)
- [Build Tools](#build-tools)
- [Cloud Computing & Infrastructure](#cloud-computing--infrastructure)
- [Computer Graphics](#computer-graphics)
- [Configuration](#configuration)
- [Database](#database)
- [Deployment & Hosting](#deployment--hosting)
- [Desktop App Development](#desktop-app-development)
- [Developer Tools](#developer-tools)
- [DevOps](#devops)
- [Documentation](#documentation)
- [Frontend](#frontend)
- [Full Stack](#full-stack)
- [Game Development](#game-development)
- [Geographic Information Systems (GIS)](#geographic-information-systems-gis)
- [Mobile App Development](#mobile-app-development)
- [Package Managers](#package-managers)
- [Project Management and Collaboration](#project-management-and-collaboration)
- [Software Development](#software-development)
- [System Design](#system-design)
- [Systems Programming](#systems-programming)
- [Text Editors, Code Editors, & Integrated Development Environments (IDEs)](#text-editors-code-editors--integrated-development-environments-ides)
- [UI/UX Design, Copywriting, and Typography](#uiux-design-copywriting-and-typography)
- [Version Control](#version-control)
- [Web Builders](#web-builders)
- [Web3](#web3)

</details>

## Backend
- **API (Application Programming Interface)**
    - **API Gateway**
        - **[AWS API Gateway](https://docs.aws.amazon.com/apigateway/)**: managed service for creating, securing, monitoring, and scaling APIs
- **API Testing**
    - **[Postman](https://learning.postman.com/docs/)**: an API platform used to design, test, document, and monitor APIs
- **Authentication**
    - **IdP (Identity Provider)**
        - **[Authentik](https://docs.goauthentik.io/)**: a self-hosted, open-source identity provider
- **Backend Framework**
    - **[ASP.NET](https://learn.microsoft.com/en-us/aspnet/core/)**: a Microsoft framework for building web apps and APIs with C# and F#
        - **[Razor](https://learn.microsoft.com/en-us/aspnet/core/mvc/views/razor)**: ASP.NET's markup syntax for building dynamic web pages with embedded C# code
    - **[Django](https://docs.djangoproject.com/)**: a high-level Python web framework for rapid development of secure, database-driven web apps
    - **[ExpressJS](https://expressjs.com/)**: a lightweight backend web framework for Node.js used to build APIs and microservices
    - **[FastAPI](https://fastapi.tiangolo.com/)**: a modern Python framework for high-performance APIs with automatic validation and async support
    - **[Flask](https://flask.palletsprojects.com/)**: a lightweight Python web framework used to build web apps, APIs, and backend services
    - **[Laravel](https://laravel.com/docs)**: a PHP web framework used to build modern web apps and APIs with MVC architecture
    - **[NestJS](https://docs.nestjs.com/)**: a TypeScript backend framework for Node.js used to build modular, scalable server-side apps
    - **[Ruby on Rails](https://guides.rubyonrails.org/)**: a Ruby web framework for server-side apps, APIs, database logic, and routing
    - **[Spring Boot](https://spring.io/projects/spring-boot)**: a Java framework that simplifies building production-ready web apps, APIs, and microservices
- **Browser Automation**
    - **[Playwright](https://playwright.dev/docs/intro)**: automates multiple browsers for web testing, scraping, and automated workflows
    - **[Puppeteer](https://pptr.dev/)**: a Node.js library that automates and controls Chrome and Firefox
    - **[Selenium](https://www.selenium.dev/documentation/)**: a browser automation framework for testing and interacting with web pages
- **[Golang](https://go.dev/doc/)**: Google's statically typed language for scalable backend systems, cloud services, and concurrent apps
- **[Google Apps Script](https://developers.google.com/apps-script)**: cloud-based JavaScript platform for integrating Google Workspace workflows
- **[Java](https://dev.java/learn/)**: a platform-independent object-oriented programming language widely used for enterprise applications
- **JavaScript Runtime**
    - **[Bun](https://bun.sh/docs)**: a fast all-in-one JavaScript runtime with a built-in package manager, bundler, and test runner
    - **JavaScript Engine**
        - **[V8](https://v8.dev/docs)**: Google's open-source JavaScript and WebAssembly engine used by Chrome and Node.js
    - **[NodeJS](https://nodejs.org/en/docs)**: a JavaScript runtime built on Chrome’s V8 engine for running JavaScript on the server
- **[PHP](https://www.php.net/manual/en/)**: server-side scripting language primarily used to build dynamic websites
- **[Python](https://docs.python.org/3/)**: a versatile high-level programming language known for its readability
- **[Ruby](https://www.ruby-lang.org/en/documentation/)**: a dynamic object-oriented language designed for simplicity and developer productivity
- **[Scala](https://docs.scala-lang.org/)**: a statically typed language that combines object-oriented and functional programming
- **[VBA (Visual Basic for Applications)](https://learn.microsoft.com/en-us/office/vba/api/overview/)**: Microsoft's language for automating Office apps with macros
- **Web Scraping**
    - **[Apify](https://docs.apify.com/)**: cloud platform for web scraping, browser automation, and data extraction using reusable actors
    - **[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)**: a Python library for parsing and extracting data from HTML and XML
    - **[Scrapy](https://docs.scrapy.org/)**: a Python framework for building scalable web scrapers and crawlers

## Build Tools
- **Build Automation**
    - **[Apache Maven](https://maven.apache.org/guides/getting-started/)**: a build automation and project management tool primarily used for Java projects
    - **[CMake](https://cmake.org/cmake/help/latest/)**: tools to build, test (CTest), and package (CPack) C and C++ software
    - **[Gradle](https://docs.gradle.org/)**: an open-source build automation tool used for dependency management, testing, and automation
- **Module Bundler**
    - **[Vite](https://vite.dev/guide/)**: a fast frontend build tool and development server

## Cloud Computing & Infrastructure
- **CDE (Cloud Development Environment)**
    - **[GitHub Codespaces](https://docs.github.com/en/codespaces)**: cloud-based, fully configured coding workspaces in GitHub
    - **[Ona (formerly Gitpod)](https://ona.com/)**: cloud development environments that launch ready-to-code workspaces from Git repos
- **Cloud Service Model**
    - **BaaS (Backend as a Service)**
        - **[Firebase](https://firebase.google.com/docs)**: Google’s BaaS with authentication, databases, hosting, analytics, and cloud functions
        - **[Supabase](https://supabase.com/docs)**: an open-source BaaS on PostgreSQL that provides authentication, databases, storage, and APIs
    - **FaaS (Function as a Service)**
        - **[AWS Lambda](https://docs.aws.amazon.com/lambda/)**: Amazon's serverless service that runs code automatically in response to events
            - **[AWS Chalice](https://aws.github.io/chalice/)**: a Python serverless framework for deploying apps to AWS Lambda
        - **[Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/)**: Microsoft’s serverless service that runs event-driven code on demand
        - **[Serverless Framework](https://www.serverless.com/framework/docs)**: a CLI for building and deploying serverless apps across cloud providers
    - **PaaS (Platform as a Service)**
        - **[AWS Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/)**: deploys web apps on AWS and automatically manages their infrastructure and scaling
        - **[DokPloy](https://docs.dokploy.com/)**: open-source, self-hostable PaaS for deploying and managing applications and databases
        - **[Heroku](https://devcenter.heroku.com/)**: cloud platform that simplifies application deployment, hosting, and scaling
        - **[PythonAnywhere](https://help.pythonanywhere.com/)**: cloud platform for developing, hosting, and running Python apps from a browser
- **Containerization**
    - **Container Orchestration**
        - **[Kubernetes (K8s)](https://kubernetes.io/docs/concepts/overview/)**: automates the deployment, scaling, networking, and management of containerized apps
            - **[K8Studio](https://k8studio.io/)**: a desktop IDE for managing Kubernetes clusters
            - **[K9s](https://k9scli.io/)**: a terminal UI for navigating and managing Kubernetes clusters
            - **[Lens](https://lenshq.io/)**: a desktop Kubernetes IDE for viewing and managing clusters
        - **[Red Hat OpenShift](https://docs.redhat.com/en/documentation/openshift_container_platform/)**: Kubernetes-based platform for building, deploying, and scaling cloud-native apps
    - **[Docker](https://docs.docker.com/get-started/)**: packages applications and their dependencies into portable, isolated containers
        - **[Dive](https://github.com/wagoodman/dive)**: inspects Docker image layers to find wasted space
    - **[Podman](https://docs.podman.io/)**: a daemonless platform for building, running, and managing containers
- **CSP (Cloud Service Provider)**
    - **[Amazon Web Services (AWS)](https://docs.aws.amazon.com/)**: Amazon's comprehensive cloud computing platform
    - **[DigitalOcean](https://docs.digitalocean.com/)**: cloud platform providing virtual servers, databases, storage, networking, and deployment
    - **[Google Cloud Platform (GCP)](https://cloud.google.com/docs)**: Google's cloud services platform
    - **[Microsoft Azure](https://learn.microsoft.com/en-us/azure/)**: Microsoft’s cloud computing platform
- **IaC (Infrastructure as Code)**
    - **[AWS CDK (Cloud Development Kit)](https://docs.aws.amazon.com/cdk/)**: defines AWS infrastructure in programming languages instead of config files
    - **[Terraform](https://developer.hashicorp.com/terraform/docs)**: automates creating and managing cloud and on-premises infrastructure as code
        - **[Atlantis](https://www.runatlantis.io/docs/)**: runs Terraform plan and apply through pull requests
- **[LocalStack](https://docs.localstack.cloud/)**: emulates AWS services locally for development and testing
- **Virtualization**
    - **[AWS EC2 (Elastic Compute Cloud)](https://docs.aws.amazon.com/ec2/)**: scalable virtual servers in the cloud for hosting applications
    - **[Proxmox VE](https://pve.proxmox.com/pve-docs/)**: open-source virtualization platform for managing virtual machines and Linux containers
- **VPC (Virtual Private Cloud)**
    - **[AWS VPC](https://docs.aws.amazon.com/vpc/)**: isolated virtual networks in AWS for securely hosting and managing cloud resources

## Computer Graphics
- **Creative Coding**
    - **[Manim](https://github.com/3b1b/manim)**: 3Blue1Brown's Python animation engine for math explainer videos
    - **[Processing](https://processing.org/)**: an open-source programming language and visual arts framework for interactive graphics
        - **[p5.js](https://p5js.org/)**: a JavaScript take on Processing for creating interactive graphics in the browser
- **Data Visualization**
    - **[Bokeh](https://docs.bokeh.org/)**: a Python library for interactive, web-based data visualizations and dashboards
- **Graphics API**
    - **[DirectX](https://learn.microsoft.com/en-us/windows/win32/directx)**: Microsoft APIs for 3D graphics, texture rendering, and audio in Windows games
    - **[NVIDIA NVRHI](https://github.com/NVIDIA-RTX/NVRHI)**: a common interface that maps onto graphics APIs including Direct3D and Vulkan
    - **[OpenGL](https://www.opengl.org/)**: a cross-platform graphics API for rendering 2D and 3D vector graphics on the GPU
- **Shading Language**
    - **[HLSL (High-Level Shader Language)](https://learn.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl)**: C-like language for writing custom GPU shaders in DirectX
    - **[Slang](https://shader-slang.org/)**: modular shading language and compiler for real-time graphics, ray tracing, and neural graphics
- **[Three.js](https://threejs.org/docs/)**: a JavaScript library for rendering 3D graphics and animations in the browser using WebGL

## Configuration
- **JSON (JavaScript Object Notation)**
    - **[JSON Crack](https://jsoncrack.com/)**: visualizes JSON, YAML, XML, and CSV as interactive graphs
    - **[Quicktype](https://quicktype.io/)**: generates typed models and serializers from JSON data

## Database
- **In-Memory Database**
    - **[Redis](https://redis.io/docs/)**: commonly used as a cache, database, and message broker for ultra-fast data access
- **[JDBC (Java Database Connectivity)](https://docs.oracle.com/javase/tutorial/jdbc/)**: a Java API for connecting to and querying relational databases
- **Non-Relational Database (NoSQL)**
    - **[AWS DynamoDB](https://docs.aws.amazon.com/dynamodb/)**: Amazon's fully managed NoSQL database for low-latency applications
    - **[MongoDB](https://www.mongodb.com/docs/)**: a document-oriented database that stores data in flexible JSON-like documents
- **Object Storage**
    - **[AWS S3 (Simple Storage Service)](https://docs.aws.amazon.com/s3/)**: scalable cloud object storage service for unstructured data
- **ORM (Object-Relational Mapping)**
    - **[Drizzle](https://orm.drizzle.team/docs/overview)**: a lightweight JavaScript and TypeScript ORM with type-safe SQL queries
    - **[Entity Framework](https://learn.microsoft.com/en-us/ef/)**: Microsoft's ORM for .NET and C# that simplifies database access
    - **[Prisma](https://www.prisma.io/docs)**: an ORM for Node.js and TypeScript that simplifies database access
- **Relational Database**
    - **[IBM Db2](https://www.ibm.com/docs/en/db2)**: a family of enterprise-grade relational database management systems
    - **[Microsoft SQL Server](https://learn.microsoft.com/en-us/sql/sql-server/)**: Microsoft's enterprise relational database management system
        - **[.NET Aspire SQL Server Integration](https://learn.microsoft.com/en-us/dotnet/aspire/database/sql-server-integration)**: configures and connects SQL Server in .NET Aspire apps
    - **[MySQL](https://dev.mysql.com/doc/)**: an open-source relational DBMS for storing and managing structured data with SQL
    - **[Oracle Database](https://docs.oracle.com/en/database/)**: an enterprise-grade relational database management system by Oracle
    - **[PostgreSQL](https://www.postgresql.org/docs/)**: an open-source relational database known for reliability, advanced SQL features, and extensibility
    - **[SQLite](https://www.sqlite.org/docs.html)**: a serverless relational database engine that stores data locally in a single file
- **Time-Series Database**
    - **[Prometheus](https://prometheus.io/docs/introduction/overview/)**: monitoring and alerting toolkit built around a time-series database
- **Vector Database**
    - **[Chroma](https://docs.trychroma.com/)**: an open-source vector database designed for building LLM applications
    - **[Milvus](https://milvus.io/docs)**: an open-source vector database built for scalable similarity search
    - **[pgvector](https://github.com/pgvector/pgvector)**: an open-source vector similarity search extension for PostgreSQL
    - **[Pinecone](https://docs.pinecone.io/)**: a fully managed, cloud-native vector database for high-performance vector search
    - **[Qdrant](https://qdrant.tech/documentation/)**: a vector database and search engine written in Rust with extended filtering
    - **[Weaviate](https://docs.weaviate.io/)**: an open-source vector database that stores both objects and vectors

## Deployment & Hosting
- **CDN (Content Delivery Network)**
    - **[Cloudflare](https://developers.cloudflare.com/)**: CDN, domain registrar, and security provider for web infrastructure
    - **[Cloudinary](https://cloudinary.com/documentation)**: cloud platform for storing, optimizing, transforming, and delivering images and videos
- **Domain Registrar**
    - **[GoDaddy](https://www.godaddy.com/)**: a domain registrar and web host providing website, email, and online business services
    - **[Porkbun](https://porkbun.com/)**: a domain registrar known for affordable domains, hosting, and DNS management
- **Static Site Hosting**
    - **[GitHub Pages](https://docs.github.com/en/pages)**: hosts static websites directly from GitHub repositories
    - **[Netlify](https://docs.netlify.com/)**: platform for building, deploying, and hosting web apps with CI/CD and serverless features
    - **[Vercel](https://vercel.com/docs)**: platform for deploying, hosting, and scaling frontend apps and serverless functions
- **[Void](https://void.cloud/)**: open-source full-stack SDK, CLI, and platform for building Vite apps and deploying them to Cloudflare
- **VPS (Virtual Private Server)**
    - **[Hetzner](https://docs.hetzner.com/)**: cloud and dedicated hosting provider offering scalable servers, storage, and infrastructure
- **Web Hosting**
    - **[Bluehost](https://www.bluehost.com/)**: a web host offering domains, business email, website hosting, and WordPress integration
    - **[iFastNet](https://ifastnet.com/)**: a hosting provider offering shared, VPS, and dedicated servers for web applications

## Desktop App Development
- **Cross-Platform Desktop Framework**
    - **[ElectronJS](https://www.electronjs.org/docs/latest/)**: a framework for building cross-platform desktop apps using JavaScript, HTML, and CSS
    - **[JavaFX](https://openjfx.io/)**: a Java framework for building desktop apps with graphical user interfaces and multimedia
- **[.NET](https://learn.microsoft.com/en-us/dotnet/)**: Microsoft's development platform and runtime for building applications in C# and F#

## Developer Tools
- **[Chrome DevTools](https://developer.chrome.com/docs/devtools)**: inspect, test, profile, and debug websites and web applications
- **Code Formatter**
    - **[Code Beautify Python Formatter](https://codebeautify.org/python-formatter-beautifier)**: an online Python code formatter and beautifier
- **[GitHub Apps](https://docs.github.com/en/apps)**: integrations that act on GitHub independently through webhooks and APIs
- **[LaTeX](https://www.latex-project.org/)**: a document preparation system for professionally formatted technical, scientific, and academic documents
    - **[Overleaf](https://www.overleaf.com/learn)**: a cloud-based collaborative LaTeX editor
- **[Linktree](https://linktr.ee/)**: a link-in-bio platform for sharing multiple links through a single landing page
- **[ntfy](https://docs.ntfy.sh/)**: sends push notifications to your phone or desktop through simple HTTP requests
- **URL Shortener**
    - **[Bitly](https://bitly.com/)**: a URL shortening and link management platform for creating and tracking short links
- **Workflow Automation**
    - **[Power Automate](https://learn.microsoft.com/en-us/power-automate/)**: Microsoft's platform for automating repetitive tasks and triggering actions across apps
    - **[Zapier](https://zapier.com/)**: connects apps and automates tasks between services without code
- **[XQuartz](https://www.xquartz.org/)**: an open-source X Window System server that runs Linux and Unix GUI apps on macOS

## DevOps
- **CI/CD (Continuous Integration and Continuous Deployment)**
    - **[Azure Pipelines](https://learn.microsoft.com/en-us/azure/devops/pipelines/)**: Azure DevOps service for CI/CD pipelines and testing
    - **[Bitbucket Pipelines](https://support.atlassian.com/bitbucket-cloud/docs/get-started-with-bitbucket-pipelines/)**: CI/CD built into Bitbucket repositories
    - **[CircleCI](https://circleci.com/docs/)**: automates code building, testing, and deployment pipelines
    - **[Codemagic](https://docs.codemagic.io/)**: automates building, testing, and deploying mobile apps, especially Flutter projects
    - **[Concourse](https://concourse-ci.org/docs.html)**: an open-source, container-based CI/CD system built around pipelines
    - **[GitHub Actions](https://docs.github.com/en/actions)**: GitHub's CI/CD platform for building, testing, and deploying code through workflows
        - **[act](https://github.com/nektos/act)**: runs GitHub Actions workflows locally
    - **[GitLab CI/CD](https://docs.gitlab.com/ci/)**: CI/CD pipelines built into GitLab
    - **GitOps**
        - **[Argo CD](https://argo-cd.readthedocs.io/)**: a declarative GitOps continuous delivery tool for Kubernetes
    - **[Jenkins](https://www.jenkins.io/doc/)**: automates software building, testing, and deployment through customizable pipelines
    - **[TeamCity](https://www.jetbrains.com/help/teamcity/)**: JetBrains' CI/CD server for building, testing, and deploying code
    - **[Travis CI](https://docs.travis-ci.com/)**: automates software testing and deployment directly from source code repositories
- **Configuration Management**
    - **[Ansible](https://docs.ansible.com/)**: open-source IT automation for configuring systems, deploying apps, and orchestrating infrastructure
        - **[Ansible AWX](https://github.com/ansible/awx)**: a web UI and REST API for running Ansible at scale
    - **[Chef](https://docs.chef.io/)**: tests, versions, and deploys infrastructure code (cookbooks and recipes) to live servers
    - **[Puppet](https://www.puppet.com/docs)**: automates infrastructure provisioning and system configuration across servers
    - **[Salt (SaltStack)](https://docs.saltproject.io/)**: automates infrastructure management, remote execution, and configuration at scale using Python
- **[.NET Aspire](https://learn.microsoft.com/en-us/dotnet/aspire/)**: cloud-native framework for building, orchestrating, and managing distributed .NET apps
- **Software Testing**
    - **Beta Testing**
        - **[TestFlight](https://developer.apple.com/testflight/)**: Apple's platform for distributing and beta testing iOS, iPadOS, watchOS, and tvOS apps
    - **E2E Testing (End-to-End Testing)**
        - **[Cypress](https://docs.cypress.io/)**: an end-to-end testing framework for web applications with real-time debugging
    - **Static Code Analysis**
        - **[SonarQube](https://docs.sonarsource.com/sonarqube-server/)**: code quality and security platform that detects bugs, vulnerabilities, and maintainability issues
    - **Unit Testing**
        - **[Jest](https://jestjs.io/docs/getting-started)**: a JavaScript testing framework commonly used for React and other frontend or backend code
        - **[JUnit](https://junit.org/)**: a test automation framework for Java
        - **[MSTest](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-mstest)**: Microsoft’s unit testing framework for .NET applications
        - **[Pytest](https://docs.pytest.org/)**: a Python framework for writing and running simple to complex automated tests
- **Web Server**
    - **[Apache HTTP Server (httpd)](https://httpd.apache.org/docs/)**: a daemon that serves web pages over HTTP or HTTPS
    - **[Caddy](https://caddyserver.com/docs/)**: an open-source web server and reverse proxy in Go that automates HTTPS and load balancing
    - **[NGINX](https://nginx.org/en/docs/)**: a web server used for routing, reverse proxying, and load balancing
- **Workflow Orchestration**
    - **[Apache Airflow](https://airflow.apache.org/docs/)**: a platform for authoring, scheduling, and monitoring workflows as code

## Documentation
- **Documentation Site Generator**
    - **[Docusaurus](https://docusaurus.io/docs)**: Meta's open-source static site generator for documentation websites
    - **[MkDocs](https://www.mkdocs.org/)**: a static site generator for project documentation written in Markdown
    - **[VitePress](https://vitepress.dev/guide/what-is-vitepress)**: a static site generator built on Vite and Vue for documentation websites
- **Markdown (MD)**
    - **README.md**
        - **[GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)**: generates a polished GitHub profile README
        - **[GitHub Stats Extended](https://github.com/stats-organization/github-stats-extended)**: generates stats cards about your GitHub contributions, languages, and more
        - **[Skill Icons](https://github.com/tandpfun/skill-icons)**: icons for showcasing your skills on GitHub READMEs and résumés
- **[Scribe](https://scribehow.com/)**: AI-powered generator for step-by-step documentation and guides
- **Snippet Sharing**
    - **[GitHub Gist](https://docs.github.com/en/get-started/writing-on-github/editing-and-sharing-content-with-gists)**: GitHub's feature for sharing and versioning code snippets and text files
    - **[Pastebin](https://pastebin.com/)**: online service for storing and sharing plain text, code snippets, and logs

## Frontend
- **[Codepen](https://codepen.io/)**: a social platform for building, testing, and sharing frontend web projects
- **Component Library**
    - **[MagicUI](https://magicui.design/docs)**: prebuilt animated UI components and design elements for React and Tailwind CSS
    - **[RadixUI](https://www.radix-ui.com/primitives/docs)**: low-level React library of accessible, unstyled UI primitives
    - **[ShadCN](https://ui.shadcn.com/docs)**: copy-in components built with Tailwind CSS and Radix UI for modern web interfaces
- **[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)**: stylesheet language used to control the layout, design, and visual appearance of web pages
- **CSS Framework**
    - **[Bootstrap](https://getbootstrap.com/docs/)**: a popular CSS framework of prebuilt UI components and layout utilities
    - **[TailwindCSS](https://tailwindcss.com/docs)**: a utility-first CSS framework that composes small reusable classes directly in HTML or JSX
- **Frontend Framework**
    - **[Angular](https://angular.dev/)**: Google's TypeScript-based framework for building dynamic, scalable websites
    - **[ReactJS](https://react.dev/)**: Meta's JavaScript library for building fast, component-based user interfaces
        - **[JSX (JavaScript XML)](https://react.dev/learn/writing-markup-with-jsx)**: a JavaScript syntax extension for writing HTML-like markup in React components
        - **[NextJS](https://nextjs.org/docs)**: a React framework for fast web apps with server-side rendering and static site generation
        - **[TSX (TypeScript XML)](https://react.dev/learn/typescript)**: combines TypeScript with JSX to build typed React components
    - **[Svelte](https://svelte.dev/docs)**: a JavaScript framework by Rich Harris that compiles components instead of shipping a heavy runtime
    - **[VueJS](https://vuejs.org/guide/introduction.html)**: a progressive JavaScript framework for interactive UIs and single-page applications
        - **[NuxtJS](https://nuxt.com/docs)**: a Vue-based full-stack framework for server-rendered and statically generated web apps
- **[Google Lighthouse](https://developer.chrome.com/docs/lighthouse/)**: an open-source auditing tool that analyzes web pages for performance, accessibility, and SEO
- **[HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)**: standard markup language used to structure and display content on web pages
- **[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)**: a versatile programming language used to create interactive websites
    - **[TypeScript](https://www.typescriptlang.org/docs/)**: a statically typed superset of JavaScript that adds type safety and tooling
- **JavaScript Library**
    - **[Framer Motion](https://motion.dev/)**: creates smooth interactive animations and transitions for web applications
    - **[HTMX](https://htmx.org/docs/)**: adds dynamic, server-driven interactions to HTML without heavy JS frameworks
    - **[jQuery](https://api.jquery.com/)**: simplifies DOM manipulation, event handling, animations, and AJAX interactions
- **Rendering Strategy**
    - **SSG (Static Site Generation)**
        - **[Gatsby](https://www.gatsbyjs.com/docs/)**: a React-based static site generation framework for fast, optimized websites
        - **[Jekyll](https://jekyllrb.com/docs/)**: a Ruby-based static site generator that converts Markdown and templates into websites
- **State Management**
    - **[Redux](https://redux.js.org/)**: a library for managing and centralizing application state predictably
- **[W3C Markup Validation Service](https://validator.w3.org/)**: validates HTML markup

## Full Stack
- **AI Coding Agent**
    - **[ChatGPT Codex](https://openai.com/codex/)**: OpenAI's coding agent for performing development tasks
    - **[Claude Code](https://www.claude.com/product/claude-code)**: Anthropic's coding agent for performing development tasks
        - **[Matt Pocock Skills](https://github.com/mattpocock/skills)**: agent skills for software engineers
    - **[Devin](https://devin.ai/)**: Cognition's cloud-based AI software engineer that plans, writes, tests, and submits code
    - **[Google Gemini Jules](https://jules.google.com/session)**: Google's coding agent for performing app development tasks
- **No-Code App Builder**
    - **[Google Gemini Opal](https://opal.google/landing/)**: builds and deploys AI mini apps without coding

## Game Development
- **[C#](https://learn.microsoft.com/en-us/dotnet/csharp/)**: Microsoft's object-oriented programming language for building applications on .NET
- **Game Engine**
    - **[Cocos2d-x](https://www.cocos.com/en/cocos2d-x)**: open-source cross-platform framework for building 2D games
    - **[Godot](https://docs.godotengine.org/)**: open-source engine for developing 2D and 3D games
    - **[Roblox Studio](https://create.roblox.com/docs)**: Roblox's official environment for creating, testing, and publishing experiences
        - **[Luau](https://luau.org/)**: Roblox's scripting language, based on Lua, built for game development and performance
    - **[Unity](https://docs.unity.com/)**: a real-time 2D and 3D engine for games, simulations, and interactive experiences
    - **[Unreal Engine](https://dev.epicgames.com/documentation/en-us/unreal-engine)**: a real-time 3D engine for high-fidelity games, simulations, and films
- **[Google Gemini Genie](https://labs.google/fx/projectgenie)**: generates playable video game worlds with AI

## Geographic Information Systems (GIS)
- **[ArcGIS](https://usg.maps.arcgis.com/home/webscene/viewer.html)**: GIS for mapping, spatial analysis, geospatial data management, and visualization
- **Desktop GIS**
    - **[QGIS](https://docs.qgis.org/)**: open-source GIS application for creating, analyzing, and visualizing geospatial data and maps
- **Mapping API**
    - **[Google Maps Platform](https://developers.google.com/maps)**: embeds maps, geolocation, routing, and geospatial features into apps and websites
    - **[Mapbox](https://docs.mapbox.com/)**: customizable maps, navigation, location services, and spatial data tools
- **Virtual Globe**
    - **[Google Earth](https://earth.google.com/)**: explore satellite imagery, terrain, and maps in 3D

## Mobile App Development
- **Cross-Platform Development**
    - **[Flutter](https://docs.flutter.dev/)**: Google’s UI toolkit for cross-platform mobile, web, and desktop apps from one Dart codebase
        - **[Dart](https://dart.dev/guides)**: Google's programming language for building cross-platform apps with Flutter
    - **[Ionic](https://ionicframework.com/docs)**: builds mobile and desktop apps with HTML, CSS, and JavaScript
    - **[React Native](https://reactnative.dev/docs/getting-started)**: Meta's JavaScript framework for building cross-platform mobile apps
    - **[Xamarin](https://dotnet.microsoft.com/en-us/apps/xamarin)**: Microsoft's C# and .NET framework for Android and iOS apps (retired, succeeded by .NET MAUI)
- **Native Development**
    - **[Kotlin](https://kotlinlang.org/docs/home.html)**: a modern statically typed language for concise, safe Android development
        - **[Jetpack Compose](https://developer.android.com/compose)**: Android’s modern declarative UI toolkit
    - **[Swift](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/)**: Apple's language for building fast, safe, and efficient apps across Apple platforms
        - **[SwiftUI](https://developer.apple.com/documentation)**: Apple’s declarative UI framework for iOS, macOS, watchOS, and tvOS apps
- **[SF Symbols](https://developer.apple.com/sf-symbols/)**: Apple’s library of scalable vector symbols for iOS, macOS, watchOS, and tvOS

## Package Managers
- **Language Package Manager**
    - **[npm](https://docs.npmjs.com/)**: the default package manager for Node.js used to install and share JavaScript libraries
    - **[vcpkg](https://learn.microsoft.com/en-us/vcpkg/)**: C and C++ package manager maintained by Microsoft and the C++ community
    - **[Yarn](https://yarnpkg.com/)**: a fast, reliable JavaScript package manager focused on consistent dependency management
- **System Package Manager**
    - **[Homebrew](https://docs.brew.sh/)**: package manager for macOS and Linux for installing and updating software from the command line
    - **[MacPorts](https://guide.macports.org/)**: an open-source package manager for macOS that installs Unix-based software
- **Virtual Environment**
    - **[Conda](https://docs.conda.io/)**: package and environment manager for installing dependencies in isolated environments

## Project Management and Collaboration
- **Agile Methodology**
    - **Kanban**
        - **[GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects)**: GitHub boards and tables for organizing tasks and tracking progress
        - **[Trello](https://trello.com/)**: visual project management with boards, lists, and cards
- **[Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/)**: Microsoft's suite for version control, project tracking, and collaboration
- **Issue Tracking**
    - **[GitHub Issues](https://docs.github.com/en/issues)**: GitHub's built-in tracker for bugs, tasks, feature discussions, and project coordination
    - **[JIRA](https://www.atlassian.com/software/jira)**: Atlassian's project management and issue tracker widely used for agile development
    - **[Linear](https://linear.app/docs)**: a fast project management and issue-tracking tool for software teams
- **ITSM (IT Service Management)**
    - **[ServiceNow](https://www.servicenow.com/docs/)**: an enterprise cloud ticketing platform for IT service management and workflow automation
- **[Notion](https://www.notion.com/help)**: all-in-one workspace for notes, project management, documentation, and collaboration
- **Office Suite**
    - **[Google Workspace](https://workspace.google.com/)**: Google's cloud productivity suite with Gmail, Docs, Drive, Meet, and Calendar
    - **[Microsoft Office Suite](https://www.microsoft.com/en-us/microsoft-365)**: productivity apps such as Word, Excel, PowerPoint, and Outlook
- **Team Communication**
    - **[Slack](https://slack.com/help)**: workplace platform for messaging, file sharing, integrations, and team coordination

## Software Development
- **[Fortran](https://fortran-lang.org/learn/)**: an early programming language designed for high-speed mathematical and scientific computing
- **Functional Programming**
    - **[Haskell](https://www.haskell.org/documentation/)**: a purely functional language known for its mathematical purity, laziness, and strong typing
    - **[Lisp](https://lisp-lang.org/)**: a multi-paradigm language that was the first functional language and second high-level language
    - **[OCaml](https://ocaml.org/docs)**: a functional language that emphasizes type safety and raw performance
- **Mainframe Computing**
    - **[COBOL](https://www.ibm.com/docs/en/cobol-zos)**: a programming language for business, finance, and administrative mainframe systems
    - **[JCL (Job Control Language)](https://www.ibm.com/docs/en/zos-basic-skills)**: scripting language used to instruct IBM mainframe operating systems

## System Design
- **UML (Unified Modeling Language)**
    - **[Astah UML](https://astah.net/)**: a software modeling tool used to create UML diagrams
    - **[StarUML](https://staruml.io/)**: a modeling tool for creating UML diagrams and software architectures
    - **[Umbrello](https://apps.kde.org/umbrello/)**: an open-source UML modeling tool
    - **[UML Designer](https://www.umldesigner.org/)**: an Eclipse-based tool for creating and visualizing UML diagrams

## Systems Programming
- **[C](https://en.cppreference.com/w/c)**: a procedural language widely used for operating systems, embedded systems, and low-level software
    - **[glibc](https://sourceware.org/glibc/)**: the GNU C Library, the standard C library on most Linux systems
- **[C++](https://en.cppreference.com/w/cpp)**: a high-performance programming language used mainly for performance-critical applications
- **Debugger**
    - **[GNU Debugger (GDB)](https://sourceware.org/gdb/documentation/)**: CLI debugger for analyzing and controlling programs written in systems languages
- **Flight Software**
    - **[F´ (F Prime)](https://nasa.github.io/fprime/)**: NASA JPL's open-source, component-driven flight software framework
- **[Lua](https://www.lua.org/docs.html)**: lightweight embeddable scripting language for games, embedded systems, and app scripting
- **[Rust](https://doc.rust-lang.org/book/)**: systems programming language focused on performance, memory safety, and concurrency
- **SDR (Software-Defined Radio)**
    - **[GNU Radio](https://wiki.gnuradio.org/)**: free software development framework that provides signal processing functions for SDR
- **[WebAssembly (Wasm)](https://webassembly.org/)**: a low-level binary instruction format that runs near-native-speed code alongside JavaScript

## Text Editors, Code Editors, & Integrated Development Environments (IDEs)
- **AI Coding Assistant**
    - **[GitHub Copilot](https://docs.github.com/en/copilot)**: AI code completion and chat for code editors and IDEs
- **AI-Native Editor**
    - **[Cursor](https://cursor.com/docs)**: AI-powered code editor
    - **[Devin Desktop (formerly Windsurf)](https://windsurf.com/)**: AI-powered VS Code-based IDE with integrated coding agents for local development
    - **[Google Antigravity](https://antigravity.google/)**: AI-powered IDE developed by Google
- **Code Editor**
    - **[Notepad++](https://notepad-plus-plus.org/)**: a lightweight Windows text and source code editor that supports many languages and plugins
    - **[Sublime Text](https://www.sublimetext.com/docs/)**: a fast, lightweight text editor known for speed, simplicity, and multi-cursor editing
    - **[VSCode](https://code.visualstudio.com/docs)**: lightweight, extensible code editor by Microsoft with debugging and extensions
    - **[Zed](https://zed.dev/docs)**: a high-performance, multiplayer code editor designed for fast collaboration
- **IDE (Integrated Development Environment)**
    - **[Android Studio](https://developer.android.com/studio)**: Google’s official IDE for coding, testing, debugging, and designing Android apps
    - **[BlueJ](https://www.bluej.org/)**: an educational Java IDE that helps beginners learn object-oriented programming
    - **[Eclipse](https://www.eclipse.org/ide/)**: an IDE for developing, debugging, and managing projects in multiple languages
    - **[IntelliJ IDEA](https://www.jetbrains.com/help/idea/)**: JetBrains' IDE designed primarily for Java and JVM-based development
    - **[NetBeans](https://netbeans.apache.org/)**: an IDE for developing, testing, and debugging applications in Java and other languages
    - **[PyCharm](https://www.jetbrains.com/help/pycharm/)**: JetBrains' Python IDE with intelligent code assistance, debugging, and testing
    - **[Theia IDE](https://theia-ide.org/)**: an open-source IDE framework for building cloud and desktop IDEs
    - **[Visual Studio](https://learn.microsoft.com/en-us/visualstudio/)**: Microsoft's IDE for building desktop, web, cloud, and mobile apps in many languages
    - **[WebStorm](https://www.jetbrains.com/help/webstorm/)**: JetBrains' IDE for JavaScript and web development
    - **[Xcode](https://developer.apple.com/xcode/)**: Apple’s IDE for building, testing, and deploying apps for iOS, macOS, watchOS, and tvOS
- **Text Editor**
    - **[Emacs](https://www.gnu.org/software/emacs/)**: a highly customizable text editor and environment for programming, editing, and automation
        - **[Doom Emacs](https://github.com/doomemacs/doomemacs)**: a fast, modular Emacs configuration framework focused on ergonomics
        - **[Evil](https://github.com/emacs-evil/evil)**: an Emacs extension that brings Vim-style modal editing and keybindings
    - **[Nano](https://www.nano-editor.org/)**: a simple command-line text editor for Unix and Linux
    - **[Vi](https://pubs.opengroup.org/onlinepubs/9799919799/utilities/vi.html)**: lightweight command-line text editor standard on Unix and Linux systems
        - **[Vim](https://www.vim.org/docs.php)**: a highly configurable Vi-based editor designed for efficient keyboard-driven editing
            - **[NeoVim](https://neovim.io/doc/)**: a highly extensible Vim-based editor with modern plugins and customization

## UI/UX Design, Copywriting, and Typography
- **Iconography**
    - **[Font Awesome](https://docs.fontawesome.com/)**: an icon toolkit that provides scalable vector icons and social logos
- **Logo Design**
    - **[Brandmark.io](https://brandmark.io/)**: creates AI-powered logo designs
- **Mockup**
    - **[Claude Design](https://claude.ai/design)**: Anthropic's AI tool for generating Figma-compatible UI/UX mockups and prototypes
    - **[Figma](https://github.com/thespcrewroy/SoftwareEngineeringTutorials/blob/main/UIUXDesign/Figma.md)**: a collaborative cloud-based design platform for UI/UX design
    - **[Google Gemini Stitch](https://stitch.withgoogle.com/)**: Google's AI tool for generating Figma-compatible UI/UX mockups
- **Typography**
    - **[Google Fonts](https://fonts.google.com/)**: free web font library for integrating customizable fonts into websites
- **Whiteboarding**
    - **[Miro](https://miro.com/)**: an AI-powered visual workspace where teams brainstorm, design, and plan together
- **Wireframe**
    - **[Concepts](https://github.com/thespcrewroy/SoftwareEngineeringTutorials/blob/main/UIUXDesign/Concepts.md)**: drawing app used for lo-fidelity wireframes
    - **[Diagrams.net](https://www.drawio.com/)**: creates wireframes for websites, apps, and software interfaces using built-in UI components
    - **[Wireframe.cc](https://github.com/thespcrewroy/SoftwareEngineeringTutorials/blob/main/UIUXDesign/WireframeCC.md)**: cloud-based tool for creating wireframes

## Version Control
- **Git GUI Client**
    - **[GitHub Desktop](https://docs.github.com/en/desktop)**: free, open-source app for working with Git repositories through a GUI
    - **[GitKraken](https://help.gitkraken.com/)**: a graphical Git client with visualizations for branches, commits, and pull requests
- **Source Code Hosting**
    - **[BitBucket](https://support.atlassian.com/bitbucket-cloud/)**: Atlassian's Git platform for code collaboration, version control, and CI/CD
    - **[Gitblit](https://gitblit.com/)**: a pure-Java server for hosting and viewing Git repositories
    - **[Gitea](https://docs.gitea.com/)**: a lightweight, self-hosted Git service with code review and CI/CD
    - **[GitHub](https://docs.github.com/)**: cloud-based platform for hosting, managing, and collaborating on Git repositories
    - **[GitLab](https://docs.gitlab.com/)**: Git repository hosting with CI/CD pipelines and collaboration tools
    - **[Gogs](https://gogs.io/docs)**: a painless, self-hosted Git service written in Go
- **VCS (Version Control System)**
    - **[Git](https://git-scm.com/doc)**: distributed version control system for tracking code changes and collaborating on project history

## Web Builders
- **AI Website Builder**
    - **[Codefoli](https://codefoli.com/)**: AI-powered portfolio website builder
    - **[Figma Make](https://www.figma.com/make/)**: generates websites and apps from UIs, mockups, and user flows using AI
    - **[Figma Sites](https://www.figma.com/sites/)**: AI-driven website and web app builder
    - **[GoDaddy Airo](https://www.godaddy.com/airo)**: creates websites, generates logos, and manages marketing tasks with AI
- **CMS (Content Management System)**
    - **[WordPress](https://wordpress.org/documentation/)**: web builder offering the most customization for software engineers
- **E-Commerce Platform**
    - **[Shopify](https://help.shopify.com/)**: web builder for e-commerce stores
        - **[Aftersell](https://www.aftersell.com/)**: offers post-purchase upsells without needing coding experience
        - **[Upcart](https://apps.shopify.com/upcart-cart-builder)**: customizable cart drawers with in-cart upsells, cross-sells, and rewards
- **No-Code Website Builder**
    - **[SquareSpace](https://support.squarespace.com/)**: web builder for beautiful design portfolios and websites
    - **[Webflow](https://university.webflow.com/)**: web builder for custom professional sites
    - **[Wix](https://www.wix.com/)**: web builder for beginners
        - **[Wix Harmony](https://www.wix.com/harmony)**: AI-powered hybrid website builder that generates a complete website layout
- **[Rosslite](https://rossilite.com/)**: builds platforms, websites, and systems for businesses to operate

## Web3
- **Blockchain**
    - **[Stellar](https://developers.stellar.org/docs)**: an open-source blockchain network for low-cost cross-border payments and digital asset transfers
        - **[Soroban](https://developers.stellar.org/docs/build/smart-contracts/overview)**: Stellar's smart contract platform for scalable, developer-friendly apps

<p align="right"><a href="#top">🔼 Back to top</a></p>
</small>
