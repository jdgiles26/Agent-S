# Agent-S: Autonomous AI for Accessibility Compliance

Agent-S is a production-ready autonomous AI agent designed to streamline and automate WCAG and 508 compliance testing. The agent navigates web applications, identifies accessibility issues, generates comprehensive reports, and integrates with development workflows to ensure continuous compliance.

## Core Features

- **Autonomous Keyboard-Based Testing**: Simulates a keyboard-only user to navigate and test every page of a web application, providing live visual feedback with colored overlays.
- **Comprehensive Documentation Generation**: Automatically produces all required accessibility and 508 compliance documentation, including:
  - Up-to-date 508 compliance checklists with pass/fail status.
  - Complete summary reports and development team action plans.
  - Automated VPAT 2.5, SRT/ART, and Trusted Tester documents.
- **Seamless Workflow Integration**:
  - Automated Jira ticket creation for identified violations.
  - Custom-generated CI/CD GitHub workflow for integrated accessibility testing.
- **Intelligent Remediation**: Provides actionable code suggestions, examples, and source links for each violation.
- **Continuous Learning and Monitoring**: Learns from each testing cycle to improve and enables continuous monitoring through scheduled autonomous tests and CI/CD pipeline integration.

## Getting Started

To initiate a test, use the following command:

`test {url}`

The agent will then begin the automated crawling and testing process for the entire site. All generated reports and documents will be available for download upon completion.