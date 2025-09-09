## Phase 1 — Prerequisites

This project deploys a **self-hosted team password manager (Passbolt CE)** on **AWS**. Before deployment, I prepared the cloud account, a local Linux VM,

### 1) AWS account secured
- Enabled **MFA** on the root account
- Created an **IAM admin user** for daily work
- Set a **budget alert** to avoid surprise costs

**Evidence**
- ![Root MFA enabled](evidence/lesson-01/aws-root-mfa.png)
- ![IAM admin user](evidence/lesson-01/iam-admin.png)
- ![Billing budget](evidence/lesson-01/budget.png)

---

### 2) Local Linux VM (Ubuntu)
I use a local Ubuntu VM for notes, keys, and quick CLI checks.

- VM: 2 vCPU, 2–4 GB RAM, 25+ GB disk
- Updated after install:
  ```bash
  sudo apt update && sudo apt -y full-upgrade
