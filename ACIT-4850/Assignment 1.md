## 1. Requirements Elicitation

### Functional Requirements
1. Integrate with **GitLab.com** private repositories for source code triggering
2. Support Automated UI testing for **React** application
3. Provide security scanning for **Python**
4. Provide native static code analysis for **Go** without extra installs
5. Support **automated deployment** of application into a test environment
6. Integrate with a **Docker** Container Registry
7. Support deployment to **Kubernetes**
8. Support integration to **Jira**
### Non-functional Requirements
1. **SaaS**: The tool is a **hosted service**, no local hardware/software managements
2. **Authentication**: The tool integrates with internal **LDAP** for **SSO**
3. **Security**: The tool supports **MFA** for admin access
4. **Auditability**: The tool provides audit logging to **usage tracking** and **user tracking**
5. **Cost**: The total going cost of the tool must not exceed **$300 USD** per developer per year
6. **Support**: The tool offers **technical support** with quick turnaround for critical issues
7. **Scalability**: The tool supports at least **two** separate Scrum teams with distinct pipelines
8. **Transparency**: One-time, training and annual cost must be **clearly defined** for the CFO