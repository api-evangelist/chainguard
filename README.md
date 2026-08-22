# Chainguard (chainguard)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
