project_name: Playwright API Automation Framework
repository: https://github.com/Sureshprashanth/playwrightAPIAutomation

overview:
  description: >
    A scalable API automation framework built using Playwright Test,
    designed to validate REST APIs with high reliability, clean structure,
    and CI/CD readiness. The framework focuses on maintainability,
    reusability, and fast execution for enterprise-grade systems.

tech_stack:
  language: JavaScript
  test_framework: Playwright Test
  api_testing: Playwright APIRequestContext
  package_manager: npm
  version_control: Git
  ci_cd_ready: true

architecture:
  design_pattern:
    - Modular test structure
    - Separation of test logic and utilities
    - Reusable API request handlers
  layers:
    - config: Environment and base configuration
    - utils: Common utilities and helpers
    - services: API request builders and handlers
    - tests: API test cases and validations

features:
  - REST API automation using Playwright
  - Environment-based execution support
  - Reusable API request contexts
  - Status code and response body validation
  - JSON schema and payload assertions
  - Fast execution compared to traditional API frameworks
  - Easy CI/CD pipeline integration

execution:
  prerequisites:
    - Node.js (v16+)
    - npm
  steps:
    - git clone https://github.com/Sureshprashanth/playwrightAPIAutomation.git
    - cd playwrightAPIAutomation
    - npm install
    - npx playwright test

use_cases:
  - API regression testing
  - Smoke and sanity API validation
  - Backend contract validation
  - CI/CD pipeline quality gates
  - Modern alternative to RestAssured-based API frameworks

highlights:
  - Demonstrates modern API testing using Playwright
  - Clean and extensible framework design
  - Suitable for enterprise-scale API automation
  - Designed for reliability and low maintenance
  - Complements UI + API testing strategy

maintainer:
  name: Suresh Prashanth
  role: SDET Lead | Automation Architect
  github: https://github.com/Sureshprashanth
  linkedin: https://www.linkedin.com/in/suresh-prashanth-11a617168
  email: sureshraviprashanth@gmail.com

relevance_for_global_talent_visa:
  criteria_alignment:
    mandatory_criteria:
      - Demonstrates technical leadership through framework design
      - Shows impact via modern testing practices
    optional_criteria_oc1:
      - Adoption of modern automation tools (Playwright API testing)
      - Framework architecture and innovation
  evidence_type:
    - Open-source technical contribution
    - Demonstrable engineering capability
    - Reusable automation solution
