# Chainguard (chainguard)

Chainguard builds, secures, and maintains a catalog of hardened, minimal container images and software supply chain security tools. Its flagship Chainguard Images rebuild open source software from source daily on a zero-known-CVE promise, signed with Sigstore, and distributed through the cgr.dev registry. The Chainguard platform exposes REST APIs, a command-line tool (chainctl), a Terraform provider, and an SDK for managing organizations, IAM, image repositories, registries, vulnerabilities, and event subscriptions. Chainguard Libraries extends the model to language ecosystems (Java, Python, Go, Node.js).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/chainguard/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Cloud Native, Container Images, Containers, DevSecOps, Kubernetes, Registry, Security, Software Supply Chain, Vulnerability Management

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-23

## APIs

### Chainguard API v2

Chainguard API v2 is the current REST API for the Chainguard platform. Endpoints cover Identity and Access Management (IAM), image registry operations, and vulnerability data under `/iam/v2beta1/`, `/registry/v2beta1/`, and `/vulnerabilities/v2beta1/`. v2 introduces cursor-based pagination, server-side ordering, consistent resource patterns, and structured error responses.

**Human URL:** [https://edu.chainguard.dev/chainguard/api/spec-api-v2/](https://edu.chainguard.dev/chainguard/api/spec-api-v2/)
**Base URL:** `https://console-api.enforce.dev`

#### Tags

- IAM, REST, Registry, Vulnerabilities

#### Properties

- [Documentation](https://edu.chainguard.dev/chainguard/api/spec-api-v2/)
- [Tutorial](https://edu.chainguard.dev/chainguard/api/api-v2-tutorial/)
- [Authentication](https://edu.chainguard.dev/chainguard/api/authentication/)

### Chainguard API v1

Chainguard API v1 is the legacy REST API for the Chainguard platform, covering the same broad surface as v2 (IAM, registry, vulnerabilities) and remaining available for existing integrations while customers migrate to v2.

**Human URL:** [https://edu.chainguard.dev/chainguard/api/spec-api-v1/](https://edu.chainguard.dev/chainguard/api/spec-api-v1/)
**Base URL:** `https://console-api.enforce.dev`

#### Tags

- IAM, Legacy, REST, Registry, Vulnerabilities

#### Properties

- [Documentation](https://edu.chainguard.dev/chainguard/api/spec-api-v1/)
- [Authentication](https://edu.chainguard.dev/chainguard/api/authentication/)

### Chainguard Unified API Spec

The unified Chainguard API specification combines API v1 and v2 definitions in a single reference, useful for tool builders and readers who need a consolidated view of the platform surface.

**Human URL:** [https://edu.chainguard.dev/chainguard/api/spec/](https://edu.chainguard.dev/chainguard/api/spec/)

#### Tags

- OpenAPI, Reference

#### Properties

- [Documentation](https://edu.chainguard.dev/chainguard/api/spec/)

### Chainguard chainctl CLI

chainctl is the official command-line interface for the Chainguard platform. It provides commands for authentication, IAM, image management, registry operations, event subscriptions, packages, libraries, and configuration. chainctl uses the same underlying APIs (v1 and v2) and is often the fastest path to automating Chainguard workflows.

**Human URL:** [https://edu.chainguard.dev/chainguard/chainctl/chainctl-docs/chainctl/](https://edu.chainguard.dev/chainguard/chainctl/chainctl-docs/chainctl/)

#### Tags

- Automation, CLI, Tooling

#### Properties

- [Documentation](https://edu.chainguard.dev/chainguard/chainctl/chainctl-docs/chainctl/)
- [Authentication](https://edu.chainguard.dev/chainguard/chainctl/chainctl-docs/chainctl_auth/)
- [GitHub Repository](https://github.com/chainguard-dev/chainctl-releases)

### Chainguard Terraform Provider

The chainguard-dev/chainguard Terraform provider lets platform engineers provision and manage Chainguard resources (organizations, groups, identities, roles, subscriptions, and more) as infrastructure-as-code through the Chainguard API.

**Human URL:** [https://registry.terraform.io/providers/chainguard-dev/chainguard/latest/docs](https://registry.terraform.io/providers/chainguard-dev/chainguard/latest/docs)

#### Tags

- IaC, Provisioning, Terraform

#### Properties

- [Documentation](https://registry.terraform.io/providers/chainguard-dev/chainguard/latest/docs)
- [GitHub Repository](https://github.com/chainguard-dev/terraform-provider-chainguard)

### Chainguard Images Registry (cgr.dev)

cgr.dev is the OCI-compliant distribution endpoint for Chainguard Images. Standard OCI and Docker tooling (`docker pull`, `cosign verify`, `oras`, `crane`, etc.) can authenticate with a pull token or IAM credentials to list tags, fetch images, and verify signatures and attestations.

**Human URL:** [https://edu.chainguard.dev/chainguard/chainguard-images/](https://edu.chainguard.dev/chainguard/chainguard-images/)
**Base URL:** `https://cgr.dev`

#### Tags

- Cosign, Distribution, OCI, Registry, Sigstore

#### Properties

- [Documentation](https://edu.chainguard.dev/chainguard/chainguard-images/)
- [Overview](https://edu.chainguard.dev/chainguard/chainguard-images/overview/)

## Common Properties

- [Website](https://www.chainguard.dev/)
- [Documentation](https://edu.chainguard.dev/)
- [Developer Portal](https://edu.chainguard.dev/chainguard/api/)
- [Academy](https://edu.chainguard.dev/)
- [Blog](https://www.chainguard.dev/unchained)
- [GitHub](https://github.com/chainguard-dev)
- [Pricing](https://www.chainguard.dev/pricing)
- [Sign Up / Console](https://console.chainguard.dev/)
- [Contact](https://www.chainguard.dev/contact)
- [Careers](https://www.chainguard.dev/careers)
- [Security](https://www.chainguard.dev/trust)
- [Status Page](https://status.chainguard.dev/)
- [Terms of Service](https://www.chainguard.dev/legal/terms)
- [Privacy Policy](https://www.chainguard.dev/legal/privacy)
- [X](https://x.com/chainguard_dev)
- [LinkedIn](https://www.linkedin.com/company/chainguard/)
- [YouTube](https://www.youtube.com/@chainguard_dev)

## Features

Hardened Images, Minimal Images, Distroless, Zero-Known-CVE, SBOMs, SLSA Attestations, Sigstore Signatures, Cosign Verification, Daily Rebuilds, Wolfi OS Base, OCI Registry, IAM, RBAC, Audit Logs, Event Subscriptions, Vulnerability Feed, Custom Assembly, FIPS Images, STIG Hardening, Libraries for Java/Python/Go/Node.js, Terraform Provider, CLI (chainctl), REST API

## Use Cases

Software Supply Chain Security, Container Hardening, CVE Remediation, Compliance (FedRAMP, FIPS, PCI, HIPAA), Open Source Dependency Security, Secure Base Images, Air-Gapped Distribution, Kubernetes Workload Security, CI/CD Integration, Image Signing and Verification, Vulnerability Scanning Reduction

## Integrations

Kubernetes, Docker, OCI, Sigstore, Cosign, SLSA, Terraform, GitHub Actions, GitLab CI, Jenkins, Argo CD, Tekton, Harbor, Quay, Amazon ECR, Google Artifact Registry, Azure Container Registry, Snyk, Prisma Cloud, Wiz, Trivy, Grype, Syft, AWS, Google Cloud, Azure

## Products

Chainguard Images, Chainguard Libraries, Chainguard Enforce, Chainguard VMs, Chainguard Containers, Wolfi OS, Custom Assembly

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
