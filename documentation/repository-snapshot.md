# Repository Snapshot Generator

**Use this when:** You want a comprehensive overview of your repository structure, key components, and documentation gaps.

**Skill Level:** Beginner to Advanced

---

## Copy This Prompt:

```
Please analyze this repository and create a comprehensive high-level snapshot that documents the project structure, key components, and provides suggestions for improvements.

## Repository Analysis Request:

Please examine the codebase and provide a detailed analysis covering:

### 1. Project Overview
- **Project Name and Purpose**: What does this project do?
- **Technology Stack**: Main languages, frameworks, and tools used
- **Project Type**: Web app, API, library, CLI tool, etc.
- **Target Audience**: Who is this built for?
- **Current Status**: Development stage, maturity level

### 2. Architecture Summary
- **Overall Architecture**: High-level system design
- **Key Components**: Main modules, services, or features
- **Data Flow**: How data moves through the system
- **External Dependencies**: Third-party services, APIs, databases
- **Design Patterns**: Architectural patterns used

### 3. Repository Structure Analysis
- **Directory Organization**: How the code is organized
- **Key Files and Directories**: Most important files to understand
- **Configuration Files**: Environment, build, deployment configs
- **Entry Points**: Main application entry points
- **Build and Deploy**: Build process and deployment setup

### 4. Feature Analysis
- **Core Features**: Main functionality provided
- **User Workflows**: Primary user journeys supported
- **API Endpoints**: Available APIs and their purposes (if applicable)
- **Database Schema**: Data models and relationships (if applicable)
- **Authentication**: Security and user management approach

### 5. Development Setup
- **Prerequisites**: Required tools, versions, dependencies
- **Installation Process**: How to get the project running locally
- **Development Workflow**: How developers work with this codebase
- **Testing Strategy**: Current testing approach and coverage
- **Code Quality**: Linting, formatting, quality gates

### 6. Documentation Assessment
Current documentation status and gaps:
- **README Quality**: Is the README comprehensive?
- **Code Documentation**: Inline comments and docstrings
- **API Documentation**: Endpoint documentation (if applicable)
- **Architecture Documentation**: System design documentation
- **User Documentation**: End-user guides and tutorials

### 7. Missing Documentation Suggestions
Identify and suggest locations for:
- **Product Requirements Document (PRD)**: Suggest adding link to `/docs/requirements/PRD.md`
- **Architecture Decision Records (ADRs)**: Suggest `/docs/decisions/` directory
- **API Documentation**: Link to `/docs/api/` or external docs
- **Deployment Guide**: Link to `/docs/deployment/` or deployment section
- **Contributing Guidelines**: Link to `CONTRIBUTING.md`
- **Changelog**: Link to `CHANGELOG.md`
- **Security Policy**: Link to `SECURITY.md`

### 8. Technical Debt and Improvements
- **Code Quality Issues**: Areas needing refactoring
- **Performance Concerns**: Potential bottlenecks or optimizations
- **Security Considerations**: Security gaps or recommendations
- **Scalability Issues**: Areas that might not scale well
- **Dependency Management**: Outdated or problematic dependencies

### 9. Project Health Metrics
- **Code Complexity**: Overall complexity assessment
- **Test Coverage**: Testing completeness
- **Documentation Coverage**: How well documented the project is
- **Maintainability Score**: How easy it is to maintain
- **Technical Debt Level**: Amount of technical debt present

### 10. Recommendations and Next Steps
Prioritized suggestions for:
- **Critical Issues**: Must-fix problems
- **Documentation Improvements**: High-impact documentation needs
- **Code Quality**: Important refactoring opportunities  
- **Feature Gaps**: Missing functionality that should be added
- **Infrastructure**: Deployment, monitoring, CI/CD improvements

## Specific Analysis Requests:

Please also provide:
- **Quick Start Guide**: 3-step process to get the project running
- **Key Contact Points**: Where to find help, contribute, or report issues
- **Related Resources**: Links to relevant external documentation
- **Project Roadmap**: If evident from the code, what's planned next

## Documentation Template Suggestions:

For missing documentation, suggest specific templates:
- README structure improvements
- PRD template and location (`/docs/requirements/PRD.md`)
- Architecture documentation template (`/docs/architecture/`)
- API documentation structure (`/docs/api/`)
- Contributing guidelines template (`CONTRIBUTING.md`)

## Repository Snapshot Format:

Present the analysis as a structured document that could serve as:
- **Project onboarding guide** for new team members
- **Technical overview** for stakeholders
- **Improvement roadmap** for the development team
- **Documentation audit** highlighting gaps

Focus on being comprehensive but concise - provide enough detail to understand the project quickly while highlighting the most important aspects and improvement opportunities.
```

---

## Tips for Better Results:

- **Run this on your entire repository** - make sure Cursor has access to all files
- **Use regularly** - run this periodically as your project evolves
- **Share the output** - great for onboarding new team members
- **Act on suggestions** - use the recommendations to improve your project
- **Combine with other prompts** - use suggestions to guide other documentation prompts 