# Project 04: Risk Assessment Results

**AI Tool:** Google Gemini
**Status:** Planning and risk assessment completed

## 1. Missing Dependencies

Gemini reviewed the proposed launch memo and workback
schedule and identified four missing dependencies.

| Dependency | Risk | Recommended Action |
|---|---|---|
| Secure API key management | High | Configure secure credential storage before API integration |
| API costs and rate limits | High | Establish usage monitoring and verify available spending controls |
| Test dataset preparation | Medium | Prepare simulated emails earlier |
| Continuous version control | Low | Initialize Git during Week 1 and commit regularly |

## 2. Security Risk Assessment

I selected secure API key management for further analysis.

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| GitHub credential exposure | High | High | Exclude secret files from Git and check repository history |
| Unexpected API costs | Medium | High | Monitor usage and configure available billing controls |
| Development delays | Medium | Medium | Complete secure credential storage before API integration |

### Preventive Controls

- Store API credentials outside application source code.
- Configure `.gitignore` to exclude local secret files.
- Use environment variables or Streamlit secrets management.
- Verify credential storage before API integration.
- Monitor API usage.

### Incident Response

If a credential is exposed:

1. Revoke the compromised key.
2. Generate a replacement credential.
3. Investigate unauthorized usage.
4. Remove exposed credentials from repository history.
5. Verify the replacement credential is securely stored.

## 3. Revised Four-Week Timeline

The following schedule summarizes Gemini's updated plan.

| Week | Days | Planned Activities |
|---|---|---|
| Week 1 | 1–5 | Define requirements, install Python, initialize Git, configure credential storage, and document incident response |
| Week 2 | 6–10 | Build Streamlit interface, integrate Gemini API securely, test authentication, and display analysis results |
| Week 3 | 11–15 | Prepare simulated emails, test assessments, identify inaccuracies, debug errors, and refine prompts |
| Week 4 | 16–20 | Review functionality, document requirements, prepare installation instructions, publish to GitHub, and conduct final review |

### Security Milestones

**Day 3:** Configure Git and `.gitignore`.

**Day 4:** Obtain Gemini API access and configure available
billing and usage controls.

**Day 5:** Configure secure credential storage and document
the credential-compromise response procedure.

**Day 8:** Integrate the Gemini API only after verifying
secure credential storage.

**Day 19:** Check for exposed credentials before publishing
the application to GitHub.

## 4. Critical Evaluation

Gemini improved the original schedule by identifying
security dependencies that were previously overlooked.

However, three recommendations required further review.

### API Spending Controls

Gemini assumed hard spending caps could be configured.

The availability and effectiveness of spending controls
must be verified before relying on them.

### Test Dataset Preparation

Gemini recommended preparing test data earlier but
retained dataset preparation on Day 11.

I would move this task into Week 1 to support prompt
development and early testing.

### Continuous Version Control

Gemini moved Git initialization to Day 3 but did not
explicitly schedule regular commits.

I would incorporate commits and credential checks
throughout the development process.

## 5. Key Learning Outcomes

This lab demonstrated how AI can assist with:

- Identifying project dependencies
- Assessing cybersecurity risks
- Developing mitigation strategies
- Revising project schedules
- Identifying implementation prerequisites

It also reinforced the importance of reviewing
AI-generated recommendations rather than accepting
them without verification.

## 6. Project Status

**Completed:** AI-assisted project risk assessment.

**Not completed:** Application development, API integration,
security implementation, and software testing.

The AI-Assisted Phishing Analyzer remains a proposed
application for future development.
