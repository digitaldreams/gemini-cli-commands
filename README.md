## Software Engineering Lifecycle (Simple Definition)

The Software Engineering Lifecycle (SELC) is the structured process of creating software applications. Think of it like building a house: you start with planning and design, then construction, testing, and finally maintenance. In software terms, this means understanding what needs to be built, designing the solution, writing the code, testing it thoroughly, and then maintaining and improving it over time.

## Available Commands

This project includes a collection of automated commands that support the full software development lifecycle. Each command is designed for specific tasks in the development process:

### Requirements Analysis Commands
- **`/requirements`**: Analyzes user requirements with brutal honesty, suggests improvements, discovers components, and adds competitor analysis
-
### System Modeling Commands
- **`/system_design`**: Generates a concise system_design.md based on requirements
- **`/architecture`**: Creates practical architectural design for web development based on requirements
- **`/system_modeling`**: Creates comprehensive UML and system models
- **`/system_model_class_er`**: Generates detailed Class and ER diagrams based on system design
- **`/system_model_behaviour`**: Generates behavioral diagrams (Sequence, State) based on system design and requirements
- **`/model_use_cases`**: Generates detailed textual Use Cases based on requirements

### Task Management Commands
- **`/tasks`**: Breaks down requirements into Epics and actionable tasks

### Design Commands
- **`/design:user_journey_map`**: Generates focused, actionable user journey insights from requirements and architecture
- **`/design:information_architecture`**: Generates comprehensive information architecture from user journeys, requirements, and system model
- **`/design:wireframe`**: Generates clean, focused wireframes showing layout and content structure
- **`/design:design_system`**: Analyzes your project and generates a custom design system with Tailwind CSS v4.1+, making opinionated decisions based on your specific needs
- **`/design:component_inventory`**: Generates a prioritized inventory of all UI components needed based on wireframes and design system

### Frontend-Related Commands
- **`/next/gen-ui-component`**: Generates minimal, production-ready Next.js 15 UI components with Tailwind CSS v4.1+
- **`/next/page`**: Generates a complete Next.js 15 page using existing UI components, based on wireframes and information architecture
- **`/next/vsa-plan`**: Generates a complete Vertical Slice Architecture (VSA) folder structure for Next.js 15 based on information architecture
- **`/next/component_inventory`**: Analyzes wireframes to generate Next.js 16 component inventory with Vertical Slice Architecture, shadcn/ui, React Hook Form + Yup
- **`/next/design_system`**: Generates a complete design system using Tailwind CSS v4.1+ with CSS-first configuration
- **`/design/component`**: Generates production-ready Next.js 15 UI components with Tailwind (JavaScript)

### Laravel-Specific Commands
- **`/laravel/database`**: Generates Laravel database schema with migrations and models
- **`/laravel/code_review`**: Reviews implementation against task requirements and Laravel best practices
- **`/laravel/security_audit`**: Scans Laravel app for security vulnerabilities and provides fixes
- **`/laravel/task_plan`**: Generates implementation plan for a task based on project architecture




## Key Components

This project uses a Laravel backend with a focus on:
- Tour planning and collaboration
- Real-time tracking and check-ins
- Story creation and sharing
- User management and subscriptions

## Getting Started

Follow the setup instructions in the documentation to get your development environment running.

## Usage

Each command in the .qwen/commands or .gemini/commands directory is designed to automate common development tasks. To use a command, simply reference it by name in your development environment. The commands will generate appropriate files and code based on your project requirements and design documents.

These automated commands help maintain consistency, speed up development, and ensure best practices are followed throughout the software engineering lifecycle.
