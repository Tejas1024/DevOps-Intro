# What is DevOps?

DevOps is a culture and practice where both development (Dev) and operations (Ops) teams work together.

**Goal:** Deliver applications faster, reliably, automated, and continuously.

Earlier, Dev and Ops worked separately causing delays. DevOps solves that gap.

## Phases in DevOps:
- Development (build software).
- Operations (install, deploy, monitor, maintain).

---

## Overview of DevOps Workflow

Developers (Dev1, Dev2, Dev3) write code and push it to GitHub (Version Control System).  
GitHub acts as a common space for the code.

CI (Continuous Integration) tools like Maven, GitHub Actions, Jenkins check code whenever commits occur.  

- CI: Combine code frequently and test it automatically.  
- CD (Continuous Delivery/Deployment): Automatically deploy code after testing.

Jenkins manages:
- Build process
- Testing on Test Environments (TE1, TE2)
- Release pipelines
- Continuous Deployment

Once tests pass, Jenkins deploys to production, enabling continuous updates to end users without manual work.
