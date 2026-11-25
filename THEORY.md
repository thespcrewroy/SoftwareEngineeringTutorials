## Backend
- **API (Application Programming Interface)**: a defined contract that lets software components request data and services
    - **API Gateway**: a managed entry point that routes, secures, and throttles requests to backend APIs
    - **API Key**: a unique code that identifies and authorizes an API caller, often with usage limits
    - **Client Library**: a package an API provider offers in a given language to make calling its API easier
    - **GraphQL**: a query language and API runtime that lets clients request exactly the data they need from a server
    - **gRPC API**: a high-performance RPC framework for communication between distributed systems using Protocol Buffers
    - **OData (Open Data Protocol)**: lets you build and consume queryable interoperable RESTful APIs using standard HTTP methods
    - **RESTful API**: a web service architecture that uses standard HTTP methods to exchange data between systems
    - **SOAP API**: a strictly standardized messaging protocol that relies on XML
    - **WebSocket API**: a persistent two-way connection that lets web apps exchange data live, as in chat and online games
- **API Testing**: sending requests to an API to verify its responses, performance, and error handling
- **Authentication**: verifying the identity of a user or service before granting access
    - **Access Token**: a secret string that proves your identity to a service, like a Hugging Face hf_ token
    - **IdP (Identity Provider)**: a service that stores user identities and authenticates them for other applications
- **Backend Framework**: a library that provides routing, request handling, and data access for building server-side apps
- **Browser Automation**: programmatically controlling a web browser to test, scrape, or interact with web pages
- **HTTP (Hypertext Transfer Protocol)**: the request-response protocol web clients and servers use to exchange data
    - **HTTP Header**: metadata sent with a request or response, such as content type and encoding
    - **HTTP Method**: the action a request asks for on a resource, such as GET, POST, PUT, or DELETE
    - **HTTP Request**: a message a client sends to a server asking for data or an action
    - **HTTP Response**: the message a server sends back with a status code, headers, and a body
        - **Status Code**: a three-digit number saying whether a request succeeded or failed, like 200 or 404
- **JavaScript Runtime**: an environment that executes JavaScript outside the browser, such as on a server
    - **JavaScript Engine**: the component that parses, compiles, and executes JavaScript code
- **Web Scraping**: automatically extracting data from websites

## Build Tools
- **Build Automation**: compiling source code, resolving dependencies, running tests, and packaging software automatically
- **Module Bundler**: combines JavaScript modules and assets into optimized files for the browser

## Cloud Computing & Infrastructure
- **CDE (Cloud Development Environment)**: a preconfigured development workspace that runs in the cloud
- **Cloud Service Model**: how responsibility is divided between a cloud provider and its customer
    - **BaaS (Backend as a Service)**: provides ready-made backend features such as databases, authentication, and APIs
    - **CaaS (Containers as a Service)**: deployment, management, and orchestration of containerized apps using Docker or Kubernetes
    - **FaaS (Function as a Service)**: run event-driven functions without managing servers or infrastructure
    - **IaaS (Infrastructure as a Service)**: provides virtualized computing resources such as servers, storage, and networking
    - **NaaS (Network as a Service)**: customers rent networking services from cloud providers instead of owning physicals
    - **PaaS (Platform as a Service)**: offers a managed platform for developing, running, and deploying applications
    - **SaaS (Software as a Service)**: applications are accessed through the internet on a subscription basis
- **Containerization**: creates isolated computing environments to eliminate dependency issues across different infrastructures
    - **Container Orchestration**: automates the deployment, scaling, networking, and management of containers
- **CSP (Cloud Service Provider)**: a company that rents computing, storage, and networking resources over the internet
- **IaC (Infrastructure as Code)**: provisioning and managing infrastructure through version-controlled configuration files
- **Virtualization**: creates entire virtual operating systems to eliminate dependency issues across infrastructure
- **VPC (Virtual Private Cloud)**: a logically isolated private network hosted within a public cloud provider's infrastructure

## Computer Graphics
- **Boid Flocks**: a simulation algorithm that models the movement of groups such as birds or fish using simple heuristics
- **Creative Coding**: writing code to produce visual art, animation, and interactive experiences
- **Data Visualization**: representing data graphically with charts, plots, and interactive dashboards
- **Graphics API**: a low-level interface programs use to send rendering commands to the GPU
- **Image Format**: a standard for encoding and storing image data in a file
    - **APNG (Animated Portable Network Graphics)**: lossless animated PNG format supporting transparency
    - **AVIF (AV1 Image File Format)**: highly compressed image format supporting transparency and HDR
    - **BMP (Bitmap)**: raster format for storing uncompressed images
    - **GIF (Graphics Interchange Format)**: raster format supporting simple animations and 256 colors
    - **HEIC (High Efficiency Image Container)**: space-efficient photo format commonly used by Apple
    - **ICO (Icon)**: image format for website favicons and Windows icons
    - **JPEG XL (JXL)**: modern image format supporting lossy, lossless, and HDR images
    - **JPEG/JPG (Joint Photographic Experts Group)**: lossy raster format optimized for photographs
    - **PNG (Portable Network Graphics)**: lossless raster format supporting transparency
    - **SVG (Scalable Vector Graphics)**: XML-based vector format for scalable logos, icons, and illustrations
    - **TIFF (Tagged Image File Format)**: high-quality raster format for photography and printing
    - **WebP**: modern image format supporting compression, transparency, and animation
- **Shading Language**: a programming language for writing shaders that run on the GPU

## Configuration
- **.config**: generic files applications and systems use to store user preferences, settings, and runtime configuration
- **.editorconfig**: keeps coding styles and settings consistent across different editors and IDEs for a repository
- **.env**: stores environment variables such as API keys, database credentials, and app settings outside the source code
- **Environment Variable**: a named value stored outside the code that programs read at runtime, like HF_TOKEN
- **.gitignore**: specifies which files and folders Git should exclude from version control tracking
- **JSON (JavaScript Object Notation)**: a lightweight data-interchange format that stores structured data as key-value pairs and arrays
- **Serialization**: converting an object into text or bytes so it can be stored or sent
    - **MessagePack**: a compact binary serialization format like JSON but smaller
    - **Protocol Buffers (Protobuf)**: Google's compact binary serialization format
- **~/.ssh**: the user-specific directory that stores SSH keys, configuration files, known hosts, and authorized keys
- **TOML (Tom's Obvious, Minimal Language)**: a simple key-value configuration format used heavily by Python and Rust
    - **pyproject.toml**: the standard Python project file for metadata, dependencies, and build settings (PEP 621)
- **XML (Extensible Markup Language)**: a markup language used to structure, store, and transport data in a readable hierarchy
- **YAML (YAML Ain't Markup Language)**: a human-readable format for settings, workflows, infra definitions, or data serializations

## Database
- **CRUD (Create, Read, Update, Delete)**: the four fundamental operations used to manage data in databases, REST APIs, and backends
- **In-Memory Database**: stores all data directly in RAM instead of traditional disk storage
- **Non-Relational Database (NoSQL)**: flexible non-table models such as key-value pairs, JSON documents, wide columns, or graphs
- **Object Storage**: stores unstructured data as objects in flat buckets accessed over HTTP
- **ORM (Object-Relational Mapping)**: libraries that let you work with databases through a programming language instead of raw SQL
- **Relational Database**: organizes data into tabular rows and columns with fixed schemas
    - **Cardinality**: how many rows in one table can relate to rows in another table
        - **Many-to-Many Relationship (N:M)**: many rows in one table link to many in another, like students and courses
            - **Junction Table (Join Table)**: a table of foreign key pairs that connects two tables in a many-to-many link
        - **One-to-Many Relationship (1:N)**: one row links to many rows in another table, like a customer and orders
        - **One-to-One Relationship (1:1)**: each row links to at most one row in another table, like a user and profile
    - **Foreign Key (FK)**: a column that references another table's primary key to link rows across tables
    - **NULL**: a special value meaning a field is empty or its data is missing
    - **Primary Key (PK)**: a column whose values uniquely identify every row and can never be NULL
    - **RDBMS (Relational Database Management System)**: software that creates, manages, and queries relational databases
    - **Referential Integrity**: the rule that every foreign key must point to an existing primary key
    - **SQL (Structured Query Language)**: the standard language for querying and managing relational databases
    - **Table (Relation)**: holds data about one kind of entity, such as Customers or Orders
        - **Column (Field)**: an attribute with a fixed data type, such as Name or Email
        - **Row (Record)**: one entry in a table, representing a single instance of the entity
- **Time-Series Database**: specialized for sequential data points indexed by timestamp
- **Vector Database**: specialized for nearest-neighbor lookups using mathematical distances for AI and ML pipelines

## Deployment & Hosting
- **CDN (Content Delivery Network)**: a distributed network of servers that caches and delivers content from locations near users
- **Domain Registrar**: a company accredited to sell and manage domain name registrations
- **Static Site Hosting**: serving prebuilt HTML, CSS, and JavaScript files without a dedicated application server
- **VPS (Virtual Private Server)**: a virtual machine rented from a hosting provider with dedicated resources and root access
- **Web Hosting**: renting server space and services to make a website reachable on the internet

## Desktop App Development
- **Cross-Platform Desktop Framework**: builds desktop apps for Windows, macOS, and Linux from a single codebase

## Developer Tools
- **Code Formatter**: automatically rewrites source code to follow consistent style rules
- **URL Shortener**: a service that maps long web addresses to short redirect links
- **Workflow Automation**: connecting apps so actions in one automatically trigger tasks in another

## DevOps
- **Artifact Repository**: centralized storage for managing, versioning, and distributing software packages, binaries, and build artifacts
- **CI/CD (Continuous Integration and Continuous Deployment)**: automates code integration, testing, and deployment
    - **GitOps**: managing deployments by treating a Git repository as the source of truth for the desired state
- **Configuration Management**: keeping servers and systems in a consistent, defined state through automation
- **Container Orchestration**: automating the deployment, scaling, networking, and management of containerized applications
- **Internal Developer Portal (IDP)**: centralized platform for discovering software services, managing development resources, and enabling developer self-service
- **Service Mesh**: an infrastructure layer that manages service-to-service traffic, security, and observability
- **Software Testing**: evaluating software to find defects and confirm it meets requirements
    - **Beta Testing**: releasing a pre-release build to real users to collect feedback before launch
    - **E2E Testing (End-to-End Testing)**: testing complete user flows through the whole application as a real user would
    - **Static Code Analysis**: examining source code without running it to find bugs, vulnerabilities, and code smells
    - **TDD (Test-Driven Development)**: tests are written before code to guide implementation and ensure functionality
    - **Unit Testing**: verifies that individual components or functions of an application work correctly in isolation
        - **AAA (Arrange, Act, Assert)**: unit testing pattern that structures tests into setup, execution, and verification
            - **Arrange:** set up all preconditions, inputs, mock objects, and environment configurations before running the test
            - **Act:** execute the target method, function, or API behavior under test (ideally focused on a single action)
            - **Assert:** verify that the actual output or side effect matches the expected result using framework assertion methods 
- **Web Server**: software that accepts HTTP requests and serves web content or proxies requests to applications
- **Workflow Orchestration**: scheduling and coordinating multi-step jobs and data pipelines across the SDLC


## Documentation
- **API Specification**: a machine-readable description of an API's endpoints, messages, and data models
    - **AsyncAPI**: a specification for documenting and designing event-driven APIs for messaging and streaming systems
    - **OpenAPI**: a specification standard for describing and documenting RESTful APIs in a machine-readable format
- **Documentation Site Generator**: a static site generator specialized for project and API documentation
- **LICENSE**: specifies the legal terms, permissions, and restrictions for using, modifying, and distributing a project
- **Markdown (MD)**: a lightweight markup language used to format plain text into structured documents with simple syntax
    - **CODE_OF_CONDUCT.md**: defines community behavior standards, participation guidelines, and enforcement policies
    - **CONTRIBUTING.md**: details the coding standards, workflows, and submission guidelines contributors must follow
    - **MDX (Markdown XML)**: combines Markdown with JSX so React components can be embedded directly inside Markdown
    - **README.md**: provides an overview, setup instructions, and usage details for a software project
    - **SECURITY.md**: outlines security policies, vulnerability reporting procedures, and supported software versions
- **Snippet Sharing**: storing and sharing small pieces of code or text through a link

## Frontend
- **AJAX (Asynchronous JavaScript and XML)**: a web dev technique that lets web pages load data from servers asynchronously
- **Component Library**: a collection of prebuilt, reusable UI components for building interfaces
- **CSS Framework**: a prewritten stylesheet library of layout utilities and UI components
- **Frontend Framework**: a library that structures how a web app's user interface is built, rendered, and updated
- **JavaScript Library**: reusable JavaScript code for common tasks such as DOM manipulation or animation
- **PRPL Pattern (Preload, Render, Precache, Lazy Load)**: a web performance strategy that improves app loading speed
- **Rendering Strategy**: how and when a web page's HTML is generated
    - **CSR (Client-Side Rendering)**: the server sends a blank HTML shell and JS files for the browser to build the page
    - **ISR (Incremental Static Regeneration)**: serves static pages and regenerates them on the server on demand or at a set interval
    - **SSG (Static Site Generation)**: prebuilds every page into static HTML files at build time
    - **SSR (Server-Side Rendering)**: the server generates the HTML page first, which is great for SEO search bots
- **State Management**: tracking, storing, and updating data and UI state over time so an app stays consistent and responsive
- **Static Site Generator**: a tool that builds a website ahead of time into static HTML, CSS, and JavaScript files
- **Widget**: an interactive UI element, such as a slider, text input, or checkbox

## Full Stack
- **AI Coding Agent**: an AI agent that plans, writes, tests, and submits code changes with limited supervision
- **No-Code App Builder**: a platform for building and deploying apps through prompts or visual editors without writing code
- **Tech Stack**: the combination of languages, frameworks, and services used to build an application
    - **MERN Stack**: a full-stack JavaScript stack consisting of MongoDB, Express.js, React, and Node.js

## Game Development
- **Game Engine**: a software framework that provides rendering, physics, audio, and scripting for building games
    - **Physics Engine**: code that simulates how physical objects move and collide over time

## Geographic Information Systems (GIS)
- **Desktop GIS**: GIS software installed locally for creating, editing, and analyzing spatial data
- **Mapping API**: a service that lets developers embed maps, geocoding, and routing in apps and websites
- **Virtual Globe**: a 3D model of the Earth for exploring satellite imagery and terrain

## Mobile App Development
- **Cross-Platform Development**: building one codebase that runs on multiple mobile operating systems
- **Native Development**: building apps with a platform's own languages and SDKs for the best performance and OS integration

## Package Managers
- **Content Addressable Cache**: a global package store that saves each file once, keyed by a hash of its contents
- **Dependency Resolution**: working out which package versions a project needs so they all work together
- **Dev Dependency**: a package needed only for development or testing, not by the finished app
- **Language Package Manager**: installs and manages the libraries a programming language's projects depend on
- **Lockfile**: records the exact version of every package so an environment resolves identically anywhere
- **Reproducibility**: the ability to recreate the exact same environment or result on any machine
    - **Cross Platform Drift**: differences that appear when one environment is built on Windows, macOS, and Linux
- **System Package Manager**: installs and updates software across an operating system from the command line
- **Virtual Environment**: an isolated set of installed packages for a single project

## Project Management and Collaboration
- **Agile Methodology**: emphasizes iterative progress, collaboration, adaptability, and continuous delivery of value
    - **Kanban**: a visual workflow method that tracks tasks as cards moving across board columns
    - **Scrum**: agile framework that organizes work into iterative sprints for collaboration efficiency
- **Issue Tracking**: recording, assigning, and following bugs and tasks through to completion
- **ITSM (IT Service Management)**: managing how IT services and support requests are delivered to users
- **Office Suite**: a bundle of productivity apps for documents, spreadsheets, presentations, and email
- **Team Communication**: chat and calling platforms that keep distributed teams in contact
- **Waterfall Methodology**: each project phase is completed sequentially before moving to the next stage

## Software Development
- **Asynchronous Programming**: running work independently of the main flow so the program doesn't wait for it
    - **Blocking**: code that stops the program from moving on until it finishes
    - **Callback Function**: a function passed to another so it runs automatically when an event happens
    - **Coroutine**: a function defined with async def that can pause, running only when awaited
    - **Event Loop**: the scheduler that runs coroutines and callbacks as they become ready
    - **Non-Blocking**: code that returns right away so the program can keep working
- **Declarative Programming**: a paradigm where you describe the result you want and the framework handles how
- **Decorator**: a function that wraps another function or class to add behavior, written with @ above it
- **Functional Programming**: a paradigm that builds programs from pure functions and immutable data
- **Mainframe Computing**: large centralized systems used for high-volume business and financial transaction processing
- **OOP (Object-Oriented Programming)**: a paradigm that organizes code into objects that bundle data with behavior
    - **Encapsulation**: bundling data and the methods that act on it into one unit, such as a class
    - **Inheritance**: a class taking on the attributes and methods of an existing parent class
- **SDLC (Software Development Life Cycle)**: structured process for developing software and software systems
    - **Plan**: goals, requirements, feasibility, timelines, and resources are identified and organized
    - **Analyze**: business and technical requirements are gathered, evaluated, and documented
    - **Design**: creating the software architecture, user interfaces, databases, and system specifications
    - **Develop**: phase where developers write and build the application’s code and core functionality
    - **Test**: stage where the software is evaluated for bugs, security issues, performance, and functionality
    - **Deploy**: release and distribute the software to users or production environments
    - **Maintain**: ongoing phase of updating, monitoring, fixing, and improving the software after release
- **SOLID Principles**: object-oriented design principles that improve maintainability, scalability, and flexibility
    - **Single Responsibility Principle**: a class should have only one responsibility or reason to change
    - **Open/Closed Principle**: software entities should be open for extension but closed for modification
    - **Liskov Substitution Principle**: subtypes should be replaceable for their base types without altering program correctness
    - **Interface Segregation Principle**: clients should not be forced to depend on interfaces they do not use
    - **Dependency Inversion Principle**: high-level modules should depend on abstractions rather than concrete implementations

## System Design
- **12-Factor App**: best practices for building modern, scalable, and portable SaaS apps that run in the cloud
- **Latency**: the delay between an event and the system's response
- **Scheduled Polling**: applications periodically check for new data at fixed time intervals
- **Software Architecture**: the high-level structure of a system and how its components interact
    - **Clean Architecture**: organizes applications into layered, independent components
    - **Client-Server Architecture**: clients send requests to a server that processes them and returns responses
    - **Event-Driven Architecture**: system components communicate and react to events asynchronously as they occur
        - **Publish-Subscribe Pattern (Pub/Sub)**: publishers send messages to topics and a broker delivers them to subscribers
            - **Fan-Out**: one published message reaching many subscribers at once
    - **Microservices Architecture**: structures applications as independently deployable services that communicate over networks
    - **Monolithic Architecture**: all application components are built and deployed as a single unified system
        - **Modular Monolith Architecture**: a single deployable monolith organized into well-separated internal modules
    - **Serverless Architecture**: apps run on third-party infrastructure and auto-scale without managing a server
    - **SOA (Service-Oriented Architecture)**: reusable services communicate over a network to support business processes
- **UI Architectural Pattern**: a pattern that separates an app's data, presentation, and input handling
    - **Flux**: Facebook's architecture for building unidirectional data flows in React frontends
    - **MVC (Model-View-Controller)**: separates an app into three interconnected components
        - **Model**: manages data and business logic
        - **View**: handles layout and display
        - **Controller**: routes commands and user input
    - **MVP (Model-View-Presenter)**: the presenter handles user interaction logic between the model and the view
    - **MVVM (Model-View-ViewModel)**: separates app logic, UI, and data binding through a view model
- **UML (Unified Modeling Language)**: a standardized visual modeling language used to design software systems

## Systems Programming
- **Debugger**: a tool for pausing, inspecting, and stepping through a running program
- **Flight Software**: software that controls spacecraft and other embedded systems in real time
- **Hard Link**: a file system entry that points to the same stored data as another file without copying it
- **SDR (Software-Defined Radio)**: radio communication where signal processing is done in software instead of hardware
- **Standard Streams**: a program's stdin, stdout, and stderr channels for input, output, and errors
- **Thread**: a separate path of execution in a program that can run at the same time as other code

## Text Editors, Code Editors, & Integrated Development Environments (IDEs)
- **AI Coding Assistant**: an editor plugin that suggests and completes code using AI
- **AI-Native Editor**: a code editor built around an integrated AI agent that can edit across a whole project
- **Code Editor**: a lightweight editor with syntax highlighting, extensions, and language tooling for source code
- **IDE (Integrated Development Environment)**: an application combining an editor, build tools, and a debugger in one place
- **Text Editor**: a program for creating and editing plain text files

## UI/UX Design, Copywriting, and Typography
- **Design Trend**: a popular visual style shaping current interface design
    - **Bento UI**: organizes content into grid-based cards of varying sizes, inspired by Japanese bento boxes
    - **Claymorphism**: soft, inflated 3D shapes with rounded corners and inner shadows that look like clay
    - **Flat Design**: simple 2D shapes, solid colors, and no gradients or shadows that imitate depth
    - **Glassmorphism**: frosted-glass panels with background blur, transparency, and thin light borders
        - **Liquid Glass**: Apple's 2025 design language of translucent, light-refracting glass across its platforms
    - **Hand-Drawn Design**: sketchy doodles, scribbled lines, and handwritten type that make an interface feel human and playful
    - **Minimalism**: stripping an interface to essential content with generous whitespace and limited color
    - **Neo-Brutalism**: thick black borders, hard shadows, bright flat colors, and intentionally raw layouts
    - **Neumorphism**: soft extruded elements that blend into the background using paired light and dark shadows
    - **Rubber Hose Style**: 1920s–30s black-and-white cartoon look with bendy limbs, pie-cut eyes, and white gloves (ex. Cuphead)
    - **Skeuomorphism**: interface elements that mimic the look and texture of real-world objects
    - **Spatial Design**: floating, layered windows with depth and lighting for AR and VR interfaces like visionOS
- **Iconography**: the design and use of icons to communicate actions and concepts visually
- **Logo Design**: creating the mark that identifies a brand
- **Mockup**: a static, high-fidelity visual of how an interface will look
- **Typography**: the arrangement and styling of type to make text readable and appealing
- **Whiteboarding**: collaborating visually on an infinite canvas with sticky notes, diagrams, and sketches
- **Wireframe**: a low-fidelity layout sketch showing structure and content placement

## Version Control
- **Git GUI Client**: a graphical app for running Git operations without the command line
- **Source Code Hosting**: a service that stores Git repositories online and adds collaboration features like pull requests
- **VCS (Version Control System)**: software that tracks file changes over time so versions can be compared and restored

## Web Builders
- **AI Website Builder**: generates a website's layout, content, and code from prompts
- **CMS (Content Management System)**: software for creating and managing website content without coding each page
- **E-Commerce Platform**: a hosted service for building and running an online store
- **No-Code Website Builder**: a drag-and-drop tool for building websites without writing code

## Web3
- **Blockchain**: a distributed ledger that records transactions in linked, tamper-resistant blocks
- **Smart Contract**: a self-executing program stored on a blockchain that acts when predetermined conditions are met
