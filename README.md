# Hello, I'm Tyler Schaefer

### Software Engineering Student | Backend Development | Software Architecture | Full-Stack Applications

I'm a Software Engineering student maintaining a **4.0 major GPA**, with a strong interest in backend development, software architecture, and building reliable, maintainable applications.

Before transitioning into software engineering, I worked in emergency medicine and fire rescue. That experience shaped my approach to problem-solving, teamwork, leadership, and making informed decisions under pressure.

Today, I apply those skills to software development, with experience ranging from Java desktop applications to full-stack engineering systems developed for real-world clients.

I particularly enjoy designing backend systems, working through complex technical challenges, developing mathematical and analytical applications, and understanding how different components come together to create a complete system.

---

## Featured Projects

### Concrete Batch Analysis & Strength Prediction System (CBAS)

**Client:** Vulcan Materials Company  
**Role:** Backend Lead / CTO — Software Engineering Capstone Project  
**Release:** v1.0.0 — November 2026  
**Status:** Completed — Final Release

**[View GitHub Repository](https://github.com/emmyatri/concrete-analysis-system)**

CBAS is a Windows desktop application developed in collaboration with Vulcan Materials Company to streamline concrete batch management, analyze curing conditions, and predict compressive strength.

The system combines engineering-based mathematical models, historical cylinder break results, and recorded curing conditions to estimate concrete strength development and help engineers identify potentially underperforming batches before traditional 28-day testing is complete.

Developed as a semester-long software engineering capstone, CBAS progressed through three development milestones and culminated in the **v1.0.0 release**, delivering a fully integrated desktop application with automated testing, engineering reports, predictive analysis, and data export capabilities.

**Key Features — v1.0.0**

- **Strength Prediction Engine:** Estimates concrete compressive strength at 3, 7, and 28 days using deterministic engineering models.
- **Prediction Calibration:** Incorporates measured cylinder break results to refine strength estimates and evaluate predictive accuracy.
- **Early-Warning System:** Identifies potentially underperforming batches and provides actionable recommendations based on early break results.
- **Batch Management:** Records concrete mix composition, cement chemistry, specimen information, curing measurements, and compressive strength results.
- **Strength Visualization:** Displays predicted strength development alongside recorded measurements.
- **Engineering Reports:** Generates comprehensive batch reports containing composition, curing conditions, predictions, warnings, and supporting engineering data.
- **Data Export:** Exports structured batch information, curing readings, break results, and predictions in Excel-compatible formats.
- **Cloud Integration:** Supports user-initiated saving of reports and exports to configured cloud-synchronized folders.
- **Offline-First Architecture:** Uses local SQLite persistence without requiring continuous network connectivity.

**My Engineering Contributions**

*Backend Architecture & Technical Leadership*
- Led backend development and contributed to system-wide architectural decisions.
- Designed and implemented RESTful API endpoints using ASP.NET Core.
- Integrated Entity Framework Core and SQLite for local data persistence.
- Contributed to architectural decision records, engineering requirements, and system documentation.

*Strength Prediction & Mathematical Modeling*
- Developed and integrated the deterministic concrete strength prediction engine.
- Implemented engineering calculations supporting strength estimation at multiple curing ages.
- Developed prediction recalibration using measured compressive strength results.
- Implemented prediction recalculation when batch data is modified.
- Contributed to predictive accuracy evaluation and engineering validation.

*Quality Analysis & Reporting*
- Developed early-warning functionality and actionable recommendations for low-strength results.
- Implemented backend functionality supporting batch reporting and structured data exports.
- Developed validation logic and safeguards for engineering data.
- Contributed to the integration of prediction results, calibration information, and quality warnings into the application.

*Testing, Integration & Release*
- Developed automated unit and integration tests using xUnit.
- Supported frontend/backend integration and CI workflows using GitHub Actions.
- Participated in regression testing, debugging, release validation, and the final v1.0.0 delivery.

**Technology Stack**

`C#` `ASP.NET Core` `.NET` `Angular` `TypeScript` `SQLite` `Entity Framework Core` `WPF` `WebView2` `xUnit` `GitHub Actions`

**Key Engineering Concepts**

RESTful API Design • Software Architecture • Mathematical Modeling • Predictive Algorithms • Data Persistence • Automated Testing • Numerical Validation • Technical Leadership

---

### ThermaCrete — Concrete Thermal Analysis & Simulation

**Role:** Project Creator / Lead Developer  
**Status:** In Development  
**Type:** Independent Software Engineering Project

ThermaCrete is an engineering software project focused on modeling and analyzing thermal behavior in concrete through numerical simulation and computational methods.

Building on my experience developing the strength prediction engine for Vulcan CBAS, ThermaCrete explores a different aspect of concrete engineering: how temperature evolves within concrete over time and how mathematical models can be translated into reliable, testable software.

The project emphasizes numerical accuracy, modular software architecture, engineering validation, and the development of a maintainable computational foundation.

**Current Development Focus**
- Establishing a modular .NET solution architecture with clearly separated responsibilities.
- Designing the foundation for concrete thermal analysis and simulation.
- Defining engineering assumptions, governing equations, and numerical methods.
- Developing automated tests for mathematical correctness and edge cases.
- Establishing numerical verification practices, including analytical comparisons, convergence testing, and stability analysis.
- Implementing GitHub-based development workflows, pull request reviews, and continuous integration.

**Engineering Objectives**
- Model temperature development and heat transfer within concrete.
- Implement reliable numerical methods for thermal simulation.
- Validate computational results against analytical or established reference solutions.
- Evaluate numerical stability, convergence, and applicable conservation properties.
- Build an extensible foundation for future engineering analysis capabilities.

**Technology Stack**

`C#` `.NET` `xUnit` `Git` `GitHub Actions`

**Key Engineering Concepts**

Numerical Methods • Heat Transfer • Computational Modeling • Software Architecture • Numerical Verification • Automated Testing • Engineering Simulation

*ThermaCrete is an ongoing project. Simulation capabilities and numerical models are being developed and validated.*

---

## Technical Skills

### Programming Languages

- **Primary:** Java, C#
- **Additional Experience:** Python, C, C++, JavaScript, TypeScript, SQL, Dart
- **Web Technologies:** HTML, CSS

### Frameworks & Technologies

- **Backend:** ASP.NET Core, Spring Framework, Spring Boot, Flask, REST APIs, Entity Framework Core
- **Frontend:** Angular, React, JavaFX, Swing, WPF, Flutter
- **Web Development:** HTML5, CSS3, Tailwind CSS, Vite
- **Databases:** SQLite, Relational Database Design, SQL
- **Testing:** JUnit 5, xUnit, Unit Testing, Integration Testing
- **Build & Deployment:** Maven, Gradle, GitHub Actions, Docker, PyInstaller, jpackage
- **Desktop Integration:** WebView2, Windows Application Packaging

### Development Tools & Environments

- **IDEs & Editors:** IntelliJ IDEA, JetBrains Rider, PyCharm, Visual Studio, Visual Studio Code, Android Studio
- **Version Control:** Git, GitHub, Branching Strategies, Pull Requests, Code Reviews
- **Operating Systems:** Windows, Linux (Ubuntu)
- **Virtualization & Containers:** VirtualBox, Docker
- **Design & Prototyping:** Figma, UI/UX Wireframing and Prototyping

### Engineering & Development Skills

- Object-Oriented Programming and Design
- Data Structures and Algorithms
- Backend Engineering and RESTful API Development
- Software Architecture and System Design
- Full-Stack Application Development
- Desktop and Mobile Application Development
- Relational Database Design and Data Persistence
- Mathematical Modeling and Numerical Computing
- Automated Testing and Continuous Integration
- Requirements Analysis and Technical Documentation
- Debugging, Performance Analysis, and Troubleshooting
- Technical Leadership and Collaborative Development

---

## Additional Projects

### The Fit — Personal Wardrobe & Outfit Organizer

**Status:** In Development  
**Technologies:** Flutter | Dart | Mobile Application Development

The Fit is an independently developed mobile application designed to simplify personal wardrobe management and outfit planning. The project focuses on creating an intuitive, offline-first experience that allows users to organize their clothing collections and build outfits.

**Development Focus**
- Designing responsive, user-friendly mobile interfaces using Flutter.
- Developing clothing categorization and wardrobe organization functionality.
- Implementing outfit creation and management features.
- Exploring local data persistence for offline accessibility.
- Applying modular architecture and maintainable coding practices.
- Prioritizing usability and a streamlined user experience.

**Planned Features**
- Visual wardrobe browsing and clothing organization.
- Custom outfit creation and saved outfit collections.
- Clothing usage tracking.
- Potential future integration of image recognition and outfit recommendations.

**Project Goal:** Develop a complete mobile application independently while expanding my experience in Flutter, Dart, application architecture, and mobile development.

### Dressmaker Commission Randomizer

**Java | Swing | Maven | JUnit 5**

A standalone desktop companion application that generates randomized client commissions for the game *Dressmaker*.

- Developed a character-driven commission system with progression and persistent save data.
- Implemented configurable requirement generation and persistent save data.
- Designed a custom Swing interface with animated character portraits and interactive journal screens.
- Created automated unit tests to validate generation rules and progression.
- Packaged the application into a Windows installer.

### Maze Generator & Solver

**Java | JavaFX | Algorithms | JUnit 5**

An interactive maze-generation and pathfinding application.

- Implemented recursive backtracking for maze generation.
- Developed DFS, BFS, A*, and Right-Hand solving algorithms.
- Built a JavaFX interface for visualizing maze generation and solution paths.
- Added JUnit 5 tests to verify algorithm behavior.

### JavaFX Pizza Shop Ordering System

**Java | JavaFX | JSON**

A desktop ordering application with customizable menu items, dynamic pricing, and persistent order data.

- Developed interactive ordering and shopping cart functionality.
- Implemented real-time price calculations.
- Used JSON for data persistence.

---

## Currently Exploring

- Advanced backend architecture and design patterns
- API development and service integration
- Cloud infrastructure and application deployment
- Software testing and continuous integration
- Numerical methods and computational simulation
- Heat transfer modeling and engineering software development
- Full-stack application architecture

---

## Connect With Me

[LinkedIn](https://www.linkedin.com/in/tyler-schaefer-1502a7275/)

I'm always interested in opportunities to collaborate, solve challenging engineering problems, and continue growing as a software developer.
