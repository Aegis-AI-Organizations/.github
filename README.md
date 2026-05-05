# ⚙️ Aegis AI - Organization Health & Templates

This repository centralizes the global configuration, contribution standards, and security policies for all microservices across the **Aegis AI** organization.

## 🏗️ How It Works
Leveraging GitHub's `.github` repository feature, all files contained here act as global **fallbacks**. 

If a specific repository (e.g., `aegis-agent` or `aegis-api`) does not contain its own Issue or Pull Request templates, GitHub will automatically inherit and display the ones defined in this centralized repository.

## 🗂️ Contents
* `profile/README.md`: The public-facing profile displayed on our organization page `https://github.com/Aegis-Ai`.
* `SECURITY.md`: Our official vulnerability disclosure policy (SecOps).
* `.github/ISSUE_TEMPLATE/`: Our standardized YAML forms to enforce issue tracking consistency.
* `.github/PULL_REQUEST_TEMPLATE.md`: Our mandatory DevSecOps checklist required before any code merge.

## ✍️ Making Changes
Any modifications made to the templates in this repository will instantly propagate to all other repositories within the organization. Please ensure all Pull Requests here are reviewed and approved by a Tech Lead or the CTO.