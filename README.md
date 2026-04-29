# Hi, I’m Sujith 👋

I’m an Android engineer based in Bengaluru, India. Most of my work has been around building mobile applications that are reliable in the real world — low bandwidth, background sync, large codebases, production crashes, slow builds, release pressure, and teams trying to move faster without breaking things.

I have spent the last 9+ years working across Android, mobile architecture, offline-first systems, CI/CD, app reliability, computer vision, and more recently AI-assisted developer workflows.

This GitHub profile is a mix of things I have worked on, things I have experimented with, and areas I’m actively learning in public.

---

## What I usually work on

- Android application architecture
- Kotlin and Java-based Android development
- Clean Architecture, MVVM, Repository pattern, modularisation
- Jetpack Compose and traditional Android View system
- Coroutines, Flow, WorkManager, Room, DataStore, Retrofit, OkHttp
- Offline-first mobile experiences and background sync
- App performance, crash reduction, observability, and release stability
- CI/CD improvements using Jenkins, Gradle, caching, and release automation
- Secure mobile patterns such as SSL pinning, obfuscation, secure storage, and API key handling
- Computer vision and on-device ML experiments using TFLite, OpenCV, JavaCV, MobileNet/YOLO/SSD-style workflows
- AI/LLM-assisted tooling for documentation, resume tailoring, structured reasoning, and developer productivity

---

## A bit about my engineering journey

I started my career building Android applications around image processing and computer vision. At Intello Labs, I worked on mobile applications used for produce quality grading, where Android apps interacted with image-processing and ML workflows to help evaluate produce quality.

Later, I worked on product and commerce platforms, including SaaS-style Android applications where user flows like catalogue creation, search, cart, checkout, onboarding, and performance mattered heavily.

At Indihood, I worked across Android and Flutter-based mobile experiences, including secure authentication, privacy-focused flows, native integrations, and observability. Some of this work involved fintech and banking-oriented use cases where handling user data carefully was important.

At LEAD Group, my work moved deeper into Android architecture, scale, reliability, and delivery systems. I worked on the Teacher App, focusing on offline-first behaviour, background sync, WorkManager-based orchestration, modularisation, release optimisation, and app reliability.

Over time, I have become increasingly interested in the systems around Android development — not just writing features, but improving how mobile teams build, test, release, debug, and maintain applications.

---

## Work I’m proud of

### App reliability and crash reduction

One of the most meaningful parts of my recent work has been improving production reliability. I have worked on identifying crash patterns, debugging critical flows, improving observability, and reducing instability in large Android applications.

A major reliability improvement I contributed to was moving crash-free sessions from roughly 70% to the 96–98% range through focused RCA, fixes, monitoring, and production hardening.

### Android build and CI/CD optimisation

I enjoy improving developer experience. Slow builds and slow PR feedback loops create hidden friction for teams.

I worked on Gradle and Jenkins-based optimisation efforts that reduced Android build time from around 20 minutes to around 8 minutes. This involved looking at build caching, pipeline structure, Gradle behaviour, and release feedback loops.

### Modularisation and Clean Architecture

I have worked on refactoring legacy Android codebases into more modular, maintainable systems. My focus is usually not “modularise everything”, but to find boundaries that reduce coupling, improve testability, and make future feature work safer.

I care about practical architecture — architecture that helps teams ship with more confidence, not architecture that only looks good in diagrams.

### Offline-first sync and background work

A lot of Android apps are used in imperfect network conditions. I have worked on offline-first data models, local persistence, sync orchestration, resumable background work, and conflict-aware flows.

I am especially interested in how WorkManager, local databases, sync state, retries, and idempotent backend APIs come together to create reliable mobile behaviour.

### AI-assisted developer workflows

Recently, I have been experimenting with AI-assisted engineering workflows. This includes document generation, resume tailoring, structured reasoning, local/cloud LLM workflows, JSON-based response parsing, and ways to use LLMs for developer productivity.

I’m interested in AI as a practical engineering amplifier — especially for documentation, code understanding, review assistance, interview preparation, and internal tooling.

---

## Some repositories on this profile

### [ResumeForge](https://github.com/sujithTSR/ResumeForge)

An experiment around AI-assisted resume and cover letter tailoring.

This project came from a real problem: job applications often need better context matching than simply sending the same resume everywhere. ResumeForge explores how AI can help tailor career documents based on role descriptions, candidate experience, and structured inputs.

Areas explored:

- AI-assisted resume tailoring
- Cover letter generation
- Job application workflows
- Structured content generation
- Career-productivity tooling

---

### [android-knowledge-mesh](https://github.com/sujithTSR/android-knowledge-mesh)

A personal Android knowledge base and learning repository.

This is where I organise Android concepts, interview preparation notes, architecture topics, and deeper learning material. I use it as a way to convert scattered learning into structured explanations.

Areas explored:

- Android interview preparation
- Kotlin and Android fundamentals
- Architecture notes
- Senior/Lead Android preparation
- Long-form learning material

---

### [DaggerHiltSample](https://github.com/sujithTSR/DaggerHiltSample)

A sample project for exploring dependency injection in Android using Dagger/Hilt.

Dependency injection is one of those topics that becomes more important as projects grow. This repository is part of my effort to practise and explain Android DI in a simple, inspectable way.

Areas explored:

- Hilt setup
- Dependency injection basics
- Android architecture wiring
- Testability and separation of concerns

---

### [AndroidJobServices](https://github.com/sujithTSR/AndroidJobServices)

A repository for testing Android Job Services and compatibility behaviour.

Background execution on Android has changed a lot over the years. This repo reflects my interest in understanding how background work behaves across Android versions and system constraints.

Areas explored:

- JobService
- Background execution
- Android version compatibility
- Scheduling experiments

---

### [WikiMobile](https://github.com/sujithTSR/WikiMobile)

A Wikipedia search Android app with suggestions.

This is one of my older Android projects, focused on search, suggestions, API integration, and building a simple mobile information-discovery experience.

Areas explored:

- Android UI
- Search experience
- API integration
- Suggestions and result rendering

---

### [NestedRecyclerView](https://github.com/sujithTSR/NestedRecyclerView)

A simple Android example demonstrating nested RecyclerView usage.

This was built as a practical UI experiment around nested lists and RecyclerView behaviour.

Areas explored:

- RecyclerView
- Nested UI rendering
- Android list performance basics
- UI composition patterns

---

### [EasyProfileAccess](https://github.com/sujithTSR/EasyProfileAccess)

A Chrome extension for quickly accessing public profiles.

This is a small utility-style project. I like building small tools when I see repeatable friction in everyday workflows.

Areas explored:

- Browser extension basics
- Profile access shortcuts
- Small productivity utilities

---

### [surface-curvature](https://github.com/sujithTSR/surface-curvature)

A Python-based project around surface curvature analysis.

This repository is different from my Android work, but I like that it reflects curiosity outside mobile development. I have always enjoyed technical areas where programming meets maths, image analysis, geometry, or computation.

Areas explored:

- Python
- NumPy / SciPy-style computation
- Surface curvature
- Mathematical experimentation

---

## Technologies I have worked with

### Android and mobile

Kotlin, Java, Android SDK, Jetpack Compose, XML layouts, Material Design, View system, Navigation, WorkManager, Room, DataStore, LiveData, Coroutines, Flow, Retrofit, OkHttp, Realm, SQLite, Firebase, Flutter, basic iOS exposure

### Architecture and engineering practices

Clean Architecture, MVVM, Repository pattern, modularisation, dependency injection, Hilt, Dagger, Koin, offline-first design, background sync, caching, release management, CI/CD, TDD, app observability

### Testing and quality

JUnit, Mockito, MockK, Espresso, unit testing, integration testing, automated test pipelines, crash analysis, performance profiling, release monitoring

### Build, release, and tooling

Gradle, Jenkins, Firebase App Distribution, Play Store releases, ProGuard/R8, build caching, pipeline optimisation, version catalogues, CI/CD hygiene

### Security and privacy

SSL pinning, API key protection, secure storage, code obfuscation, PII masking, authentication flows, mobile security best practices

### AI, ML, and experimentation

OpenAI APIs, Gemini APIs, Claude API, local/cloud LLM workflows, MCP experiments, TFLite, OpenCV, JavaCV, MobileNet, YOLO/SSD-style mobile ML workflows

---

## Topics I’m currently learning and writing about

- Jetpack Compose architecture and performance
- Android system design for senior and lead interviews
- Offline-first sync and conflict resolution
- WorkManager and reliable background execution
- Kotlin Coroutines and Flow internals
- Mobile security for fintech and banking apps
- Android CI/CD and build optimisation
- Modularisation strategies for large Android codebases
- AI agents and LLM-assisted developer workflows
- Moving from feature ownership to platform and systems-level ownership

---

## My engineering philosophy

I think good Android engineering is not only about building screens.

It is about building systems that continue to work under pressure:

- when the network is poor,
- when the app runs in the background,
- when releases need to be shipped quickly,
- when old code needs to evolve,
- when multiple teams touch the same codebase,
- and when users depend on the app every day.

I care about writing code, but I care just as much about the surrounding engineering system: architecture, build speed, release quality, observability, communication, and team clarity.

The Android work I enjoy most sits at the intersection of product, platform, reliability, and developer experience.

---

## GitHub activity

![Sujith's GitHub stats](https://github-readme-stats.vercel.app/api?username=sujithTSR&show_icons=true&hide_title=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sujithTSR&layout=compact)

---

## Connect

- GitHub: [github](https://github.com/sujithTSR)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/sujith-thotlapalepu-a5284a93/)
- Stack Overflow: [Stack Overflow](https://stackoverflow.com/users/5222029/sujith-royal)
- Email: [sujith.royal.216@gmail.com](sujith.royal.216@gmail.com)

---

## Currently open to conversations around

- Android architecture
- Senior / Lead Android engineering
- Mobile platform engineering
- Offline-first app design
- App reliability and performance
- CI/CD for Android teams
- AI-assisted developer productivity
- Practical system design for mobile apps
