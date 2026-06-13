<div align="center">
  <a href="https://www.linkedin.com/in/juan-musau">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://medium.com/@musaujoseph8">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/>
  </a>
  <a href="https://makau5.gumroad.com">
    <img src="https://img.shields.io/badge/Gumroad-36a9ae?style=for-the-badge&logo=gumroad&logoColor=white" alt="Gumroad"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=musaumakau&style=for-the-badge&color=0077B5" alt="Profile views"/>
</div>

---

# Juan Makau -- Senior DevOps Engineer

I build infrastructure that doesn't surprise you. That means cost gates before `apply`, policy enforcement as part of the pipeline, and drift detection that fires before oncall does.

Based in Nairobi. 5+ years working across AWS, Kubernetes, and Terraform at scale.

---

## What I've shipped

**50% reduction in deployment cycle time** by replacing a monolithic GitHub Actions pipeline with composite actions, reusable workflows, and parallel security scanning (tfsec, checkov, trivy). Wrote about it on Medium -- hit 1,000+ impressions on day one.

**40% reduction in infrastructure costs** through automated Infracost + OPA gates: PRs with cost increases above threshold are blocked before they reach AWS.

**87% reduction in surprise infrastructure costs** across the `infrastructure-modules` project using real-time cost analysis, blast radius scoring, and semantic drift detection with per-environment risk thresholds.

**Production-grade GitOps** with ArgoCD on EKS, HashiCorp Vault for secrets, Terragrunt for environment promotion, and environment protection gates for Staging and Prod.

---

## Featured projects

### [infrastructure-modules](https://github.com/musaumakau/infrastructure-modules)
Enterprise Terraform modules with a full governance layer built in:
- Blast radius scoring on every PR
- OPA cost gates blocking spend above threshold
- Semantic drift detection with risk-aware fingerprinting for high-risk resource types
- Parallel security scanning: tfsec, checkov, trivy
- `terraform test` + Terratest Go tests for VPC and EKS modules

> [Case study on Medium](https://medium.com/@musaujoseph8/building-enterprise-infrastructure-governance-how-we-eliminated-cost-overruns-and-compliance-gaps-0d8dd6772110)

### [infrastructure-live](https://github.com/musaumakau/infrastructure-live)
Terragrunt-based multi-environment deployment repo:
- Composite actions for AWS OIDC auth, Terragrunt setup, EKS kubeconfig
- Destroy workflow with confirmation guards
- Environment protection gates enforced via GitHub environments (Staging, Prod)
- Manifest-as-contract pattern for verified deployments

---

## Currently building

- **IDP lab** -- local-first Internal Developer Platform (Docker Compose, FastAPI, Backstage-compatible service catalog) exploring self-service infrastructure patterns
- **Gumroad store** -- DevOps tools and templates for engineers: [makau5.gumroad.com](https://makau5.gumroad.com)

---

## Stack

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" title="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/terraform/terraform-original.svg" title="Terraform" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/kubernetes/kubernetes-plain.svg" title="Kubernetes" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" title="Docker" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/prometheus/prometheus-original.svg" title="Prometheus" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/grafana/grafana-original.svg" title="Grafana" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/ansible/ansible-original.svg" title="Ansible" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/bash/bash-original.svg" title="Bash" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" title="Git" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" title="Linux" width="40" height="40"/>
</div>

**Also:** GitHub Actions, ArgoCD, HashiCorp Vault, Terragrunt, OPA/Gatekeeper, Infracost, tfsec, checkov, trivy, Karpenter, Gitleaks

---

## Latest writing

- [Your CI Pipeline Has the Same Problems as Badly Written Software](https://medium.com/@musaujoseph8/how-i-built-a-production-grade-terraform-ci-cd-pipeline-that-actually-catches-problems-before-they-f6b6cc85ee5d) -- how I refactored a 300-line GitHub Actions monolith into reusable workflows and a thin orchestrator
- [The Plan You Reviewed Is the Plan That Gets Applied](https://medium.com/@musaujoseph8/the-plan-you-reviewed-is-the-plan-that-gets-applied-41440cf6285f) -- manifest-as-contract pattern for verified Terraform deployments
- [How We Eliminated Cloud Cost Overruns Using Terraform + Policy-as-Code](https://medium.com/@musaujoseph8/building-enterprise-infrastructure-governance-how-we-eliminated-cost-overruns-and-compliance-gaps-0d8dd6772110) -- OPA gates, Infracost, and automated governance in CI/CD

---

## GitHub activity

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=musaumakau&theme=default&hide_border=true" alt="GitHub streak"/>
</div>

---

*Open to DevOps roles and infrastructure consulting. Reach me on [LinkedIn](https://www.linkedin.com/in/juan-musau).*
