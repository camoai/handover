# Centre for Antimicrobial Optimization Artificial Intelligence Repository and Group

Welcome to the official GitHub organization for the **Centre for Antimicrobial Optimization Artificial Intelligence (CAO-AI)**.

This space serves as a **central hub** for storing, sharing, and handing over research code, models, reports, and related AI work produced by group members.

---

## 🔍 Purpose

- Ensure smooth **handover** of project code and documentation.
- Provide a **shared platform** for collaboration and archiving.
- Offer a structured, consistent **repository format** for AI research outputs.
- Serve as a **directory to personal and project repositories**.

---

## 📂 Contribution Guidelines

You can contribute your work to this organization in two ways:

---

### 🛠 Option 1: Full Project Repository

If you have been developing your project in a **personal GitHub repository**, you can transfer or clone it into this organization.

#### Steps:

1. Ask the admin for access to the organization.
2. Clone your personal repo into the org:

   ```bash
   git clone --mirror https://github.com/your-username/your-project.git
   cd your-project.git
   git push --mirror https://github.com/cao-ai/your-project.git
   ```

3. Alternatively, you can fork or recreate the repository under the organization and push your local files.

4. Ensure your new repository includes:
   - A `README.md` with a **brief description of the project**, your **name**, and **contact information**.
   - Any usage instructions, dependencies, and citations.

---

### 📄 Option 2: Structured Handover Repository

If you only want to submit specific artifacts (e.g., final models, code, thesis), use the following structure:

```
/your-project-name/
│
├── /code/        # Main scripts or notebooks
├── /models/      # Trained models, weights, architecture
├── /docs/        # Thesis, reports, supplementary material
├── /handover/    # Instructions, configuration, setup notes
└── README.md     # Project summary + contributor info
```

#### Instructions:

1. Create a new repository under the organization.
2. Populate the directory with your materials.
3. Include a top-level `README.md` like the example below:

````markdown
# [Project Title]

## Description

Brief overview of the project, goals, and results.

## Contributor

- **Name**: Your Full Name  
- **Email**: your.email@example.com  
- **Affiliation**: Centre for Antimicrobial Optimization AI Group

## Contents

- `/code/`: Scripts, pipelines, or notebooks.
- `/models/`: Trained models or training logs.
- `/docs/`: Project report, thesis, or publications.
- `/handover/`: Any configuration or setup information needed to reproduce results.

## Notes

Add anything needed to replicate the results or continue the work.
