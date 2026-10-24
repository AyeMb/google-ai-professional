# Project 04: AI Phishing Analyzer — Risk Assessment

**Course:** Google AI Professional Certificate  
**Course 2:** AI for Brainstorming and Planning  
**Lab:** Build with AI — Risk Assessment  
**Tool:** Google Gemini  
**Project Status:** Completed — Planning and Risk Assessment

## Project Overview

This project builds on Project 03, where I identified an
AI-Assisted Phishing Analyzer as a potential IT support solution
for small businesses.

For this lab, I used Google Gemini to evaluate a proposed
four-week development plan for a Python-based phishing analyzer.

The objective was to identify missing project dependencies,
assess their risks, and develop a more secure implementation
timeline.

## Proposed Application

The AI-Assisted Phishing Analyzer would use:

- Python for application development
- Streamlit for the web interface
- Google Gemini API for AI-assisted email analysis
- GitHub for version control and documentation

The application would analyze simulated email content,
identify potential phishing indicators, and recommend
verification steps.

This is a proposed application, not a completed prototype.

## Project Objectives

1. Identify missing dependencies in the original project plan.
2. Evaluate potential security and development risks.
3. Prioritize risks according to their potential impact.
4. Develop an updated four-week implementation timeline.
5. Identify security requirements that must be completed
   before API integration.

## Project Workflow

### Step 1: Identify Missing Dependencies

I provided Gemini with two original planning documents:

- AI Phishing Analyzer Launch Memo
- AI Phishing Analyzer Workback Schedule

Gemini identified four missing dependencies:

| Dependency | Risk Level |
|---|---|
| Secure API key management | High |
| API cost and rate-limit controls | High |
| Early test dataset preparation | Medium |
| Continuous version control | Low |

### Step 2: Assess Project Risks

I selected secure API key management for further analysis.

Gemini identified potential consequences of exposed
API credentials, including:

- Unauthorized API usage
- Unexpected financial costs
- Development delays
- Accidental credential exposure through GitHub
- Security vulnerabilities during API integration

Recommended controls included:

- Environment variables
- Git ignore rules
- Streamlit secrets management
- Credential revocation procedures
- API usage monitoring

### Step 3: Update the Project Timeline

Gemini generated a revised four-week development schedule.

The updated plan introduced security tasks during Week 1,
including Git initialization, credential storage,
and compromised-key response planning.

Secure credential management became a prerequisite
for Gemini API integration during Week 2.

## Critical Evaluation of AI Results

Although Gemini improved the original project plan,
I identified three areas requiring further attention.

### 1. API Spending Controls

Gemini recommended hard spending caps without verifying
whether the selected API service supports them.

Billing alerts should not be assumed to prevent charges.

### 2. Test Dataset Preparation

Gemini initially recommended preparing test data during
Week 1 but retained this task in Week 3 of the revised plan.

This dependency should be moved earlier to support
prompt development and testing.

### 3. Version Control

The revised plan initialized Git during Week 1 but
did not explicitly schedule regular commits throughout
development.

Continuous version control and security checks should
be incorporated into the development workflow.

## Skills Demonstrated

- AI-assisted risk assessment
- Project dependency analysis
- Cybersecurity risk identification
- Secure API integration planning
- Risk mitigation
- Project scheduling
- Critical evaluation of AI-generated recommendations
- Technical documentation

## Key Takeaway

AI can help identify overlooked project dependencies
and improve development plans.

However, AI-generated recommendations must be reviewed
for technical accuracy, consistency, and feasibility.

This project demonstrated the importance of identifying
security requirements before beginning application development.

## Project Status

Completed — Risk Assessment Lab.

The proposed phishing analyzer remains in the planning stage.
