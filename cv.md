![Nadzeya Kaluzayeva](./1.jpg)

# Nadzeya Kaluzayeva

## Software Developer

- 📧 nadiakoluzaeva@gmail.com
- 📞 215 268 8878
- 💬 [Мой Discord аккаунт](https://discord.com/users/nadia9022)
- 🔗 [LinkedIn](https://www.linkedin.com/in/nadzeya-kaluzayeva/)
- 📍 Philadelphia, 19116

### Summary

Accomplished QA Automation Engineer with over 5 years of experience specializing in the development and implementation of automated testing solutions. Expertise in Cypress, Selenium, Django frameworks, complemented by a strong background in both UI and API testing across various software development methodologies. Proven track record in creating effective test strategies, automating complex test cases, and enhancing overall software quality through meticulous manual testing, particularly for mobile applications. Skilled in integrating testing into CI/CD workflows and contributing to the entire software development lifecycle.

### Technical Skills

- **Automation Tools/Frameworks/Libraries:** Cypress, Mocha, Chai, Axios, Selenium WebDriver, Django, Playwright, Puppeteer
- **Programming Languages:** JavaScript, Python, SQL, HTML, CSS, TypeScript
- **API Tools:** Postman, Swagger
- **Reporting Tools:** Cypress Cloud, Cypress-Mochawesome-Reporter, Allure-Report
- **Databases:** MySQL, PostgreSQL
- **Containerization Tools:** Docker
- **Development Tools:** Visual Studio Code, PyCharm, DBeaver
- **Version Control:** Git, GitHub
- **Software Development Project Management Tools:** Jira, Confluence, TestRail
- **CI/CD:** GitHub Actions
- **Methodologies:** Agile Scrum, Kanban

### Professional Experience

**QA Automation Engineer | Tembook | April 2023 - Present**

- Project: "Peshkariki" Courier Service:

  - Spearheading automated testing for a courier service platform, facilitating small and medium-sized businesses in managing cargo transportation efficiently.
  - Leading the design and development of Cypress and Postman-based automated scripts for UI/API validation, achieving 98% test coverage.
  - Streamlining test processes, achieving a 20% reduction in testing time and a 15% decrease in post-release defects.
  - Integrating automated tests into the CI/CD pipeline, enhancing software stability and product quality.
  - Orchestrating cross-functional collaboration, contributing significantly to quality assurance and documentation.

- Project: "Team-tracker" tool for tracking team tasks and projects:
  - Central to the development of a Django-based backend project mirroring JIRA's functionality for task and project tracking.
  - Focusing on Python and Django backend testing with PostgreSQL, ensuring high system reliability.
  - Utilized Docker to create containerized test environments, significantly improving the efficiency and consistency of testing processes.
  - Participating actively in Agile Scrum processes, aligning testing strategies with development cycles.

**QA Automation Engineer | Clarip INC | February 2022 - March 2023**

- Project: Privacy Governance Platform:
  - Contributed to the development of a privacy governance platform aligning with GDPR and CCPA regulations.
  - Developed Cypress-based automated testing solutions, reducing critical defects by 30% and enhancing customer satisfaction.
  - Managed over 500 test cases, significantly speeding up feature releases while maintaining high software quality.
  - Conducted API testing and SQL database checks, leading to a substantial decrease in integration issues and data-related incidents.

**AQA Engineer | TestArmy Group S.A. | November 2020 - November 2021**

- Project: Payment Platform Application:
  - Undertook manual and automated testing for a web-based payment platform, focusing on functional, integration, and mobile application testing.
  - Maintained a comprehensive understanding of application features, contributing to a well-rounded testing approach.

**QA Analyst | Emmandarindotcom LLC | July 2018 - September 2020**

- Project: Online Marketplace:
  - Engaged in manual and automated testing for a diverse online marketplace, collaborating closely with developers and QA teams.
  - Executed extensive test cases for web and mobile applications, ensuring thorough defect identification and resolution.

### Code Sample: Codewars Kata Solution
**Problem**: Find the length of the longest contiguous subarray in a binary array that consists of an equal number of 0s and 1s.

```javascript
function binarray(a) {
  let count = 0;
  let countMap = new Map();
  countMap.set(0, -1);
  let maxLength = 0;
  
  for (let i = 0; i < a.length; i++) {
    if (a[i] === 1) {
      count++;
    } else {
      count--;
    }
    if (countMap.has(count)) {
      maxLength = Math.max(maxLength, i - countMap.get(count));
    } else {
      countMap.set(count, i);
    }
  }
  
  return maxLength;
} 
```

### Education

- Bachelor’s Degree in Law and Social-Information Technologies


### Languages
- **English:** Upper-Intermediate
- **Russian:** Native
- **Polish:** Advanced
