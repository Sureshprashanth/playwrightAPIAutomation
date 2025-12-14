# Playwright API Automation Framework

A **Playwright-based API automation framework** built using **JavaScript**, designed for scalable, maintainable, and CI/CD-ready API testing.  
This project leverages Playwright’s API testing capabilities to validate REST APIs efficiently with clean architecture and reporting.

---

## 🚀 Tech Stack

- **Playwright** – API testing using request context  
- **JavaScript** – Core language  
- **Node.js / npm** – Runtime & dependency management  
- **Playwright Test Runner** – Test execution & reporting  

---

## ✨ Features

- API automation using Playwright request context  
- Modular request and response handling  
- Reusable utilities and helper functions  
- Environment-based configuration support  
- CI/CD-friendly execution  
- Built-in Playwright HTML reporting  

---

## 📁 Project Structure

├── api/ # API request handlers & endpoints
├── tests/ # API test cases
├── utils/ # Common utilities & helpers
├── config/ # Environment configurations
├── playwright.config.js # Playwright configuration
├── package.json # Dependencies & scripts
├── playwright-report/ # HTML test reports

yaml
Copy code

---

## 🛠 Installation

### Prerequisites
- Node.js (v16 or above)
- npm

### Steps

1. Clone the repository  
   ```bash
   git clone https://github.com/Sureshprashanth/playwrightAPIAutomation.git
Navigate to the project

bash
Copy code
cd playwrightAPIAutomation
Install dependencies

bash
Copy code
npm install
▶️ Running Tests
Run all API tests

bash
Copy code
npx playwright test
Run tests in headed mode

bash
Copy code
npx playwright test --headed
View test report

bash
Copy code
npx playwright show-report
📊 Reporting
Playwright generates a rich HTML report after execution.
Reports are available under:

Copy code
playwright-report/
✅ Best Practices Followed
Separation of request logic and assertions

Environment-based configuration for flexibility

Validation of status codes, headers, and response payloads

Independent and deterministic test cases

Clean, maintainable test structure

🔄 CI/CD Support
This framework is designed to work seamlessly with:

GitHub Actions

Jenkins

👤 Maintainer
Suresh Prashanth
SDET Lead • Automation Architect
GitHub: https://github.com/Sureshprashanth






