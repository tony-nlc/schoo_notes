## 1. Requirements Elicitation

### Functional Requirements
1. Must Integrate with **GitLab.com** private repositories for source code triggering
2. Must support Automated UI testing for **React** application
3. Must provide security scanning for **Python**
4. Must provide native static code analysis for **Go** without extra installs
5. Must support **automated deployment** of application into a test environment
6. Must integrate with a **Docker** Container Registry
7. Must support deployment to **Kubernetes**
8. Must support integration to **Jira**
### Non-functional Requirements
1. **SaaS**: The tool must be a **hosted service**, no local hardware/software managements
2. **Authentication**: The tool must integrate with internal **LDAP** for **SSO**
3. **Security**: The tool must support **MFA** for admin access
4. **Auditability**: The tool must provide audit logging to **usage tracking** and **user tracking**
5. **Cost**: The total going cost must not exceed **$300 USD**