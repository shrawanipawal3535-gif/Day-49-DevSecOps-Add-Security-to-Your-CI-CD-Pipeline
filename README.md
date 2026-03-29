# Day-49-DevSecOps-Add-Security-to-Your-CI-CD-Pipeline

1️⃣ Implemented **automated Build & Test** for every Pull Request (PR) to catch issues early.
2️⃣ Added **Dependency Vulnerability Checks** using GitHub’s dependency-review-action.
3️⃣ PRs now **fail automatically** if any critical vulnerabilities are detected in dependencies.
4️⃣ Created **reusable workflows** for Docker Build & Push, improving maintainability.
5️⃣ Integrated **Trivy scans** to detect critical/high vulnerabilities in Docker images.
6️⃣ Docker images **cannot be pushed or deployed** if critical vulnerabilities exist.
7️⃣ Enabled **GitHub Secret Scanning** to detect accidental leaks of API keys and tokens.
8️⃣ Enabled **Push Protection** to block commits containing secrets proactively.
9️⃣ Updated workflow permissions to **least privilege** using `permissions: contents: read`.
🔟 Added `pull-requests: write` only where workflows need to comment on PRs.
1️⃣1️⃣ PR Workflow: Build & Test → Dependency Scan → PR status check.
1️⃣2️⃣ Main Branch Workflow: Build & Test → Docker Build → Trivy Scan → Docker Push → Deploy.
1️⃣3️⃣ Ensured that **only secure, tested code** reaches production.
1️⃣4️⃣ Automated pipeline reduces manual effort and improves reliability.
1️⃣5️⃣ Security-first approach minimizes risks from compromised actions or secrets leaks.
1️⃣6️⃣ Learned to integrate **DevSecOps practices** directly into CI/CD pipelines.
1️⃣7️⃣ Gained hands-on experience with **GitHub Actions, Docker, and Trivy**.
1️⃣8️⃣ Strengthened my understanding of **secure automation best practices**.
1️⃣9️⃣ Implemented real-world **checks for code, dependencies, and container images**.
2️⃣0️⃣ Overall, the pipeline ensures **faster, safer, and more reliable deployments**.

