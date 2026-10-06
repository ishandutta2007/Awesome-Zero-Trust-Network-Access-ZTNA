# Awesome-Zero-Trust-Network-Access-ZTNA

# Top Zero Trust Network Access (ZTNA) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Identity-Aware Access, Microsegmentation & Self-Hosted Zero Trust*  
**Last updated: October 2026**

This repository tracks notable **commercial ZTNA platforms** and **open-source projects** that replace traditional VPNs with identity-aware, least-privilege access to applications and services. These tools enforce "never trust, always verify" by authenticating users and devices before granting access to specific resources — not the entire network.

**Examples** include AWS Verified Access, Zscaler Private Access, Cloudflare Access, Palo Alto Prisma Access, Cisco Secure Access, Tailscale, Perimeter 81, Twingate, Appgate SDP, and Netskope Private Access (the category leaders).

**Open-source emphasis**: ZTNA is a strong open-source domain. **OpenZiti** leads as the most comprehensive open-source zero trust networking platform with 2,900+ GitHub stars. **Pomerium** brings identity-aware access proxy capabilities, **Teleport** secures infrastructure access, and **BunkerWeb** provides a full-featured web application firewall with ZTNA principles. **Pritunl Zero** delivers BeyondCorp-style access, while **wg-access-server** provides a simple WireGuard-based solution. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS Verified Access](https://aws.amazon.com/verified-access/)**  
  AWS's ZTNA service — identity-aware access to applications without VPN. **Native integration with AWS IAM, SSO, and device trust**. **Best for AWS-centric organizations**.

- **[Zscaler Private Access](https://www.zscaler.com/products/zscaler-private-access)**  
  **The market-leading ZTNA platform** — zero trust access to private apps with cloud-native architecture. **The reference for enterprise ZTNA** .

- **[Cloudflare Access](https://www.cloudflare.com/zero-trust/products/access/)**  
  **Cloudflare's ZTNA solution** — identity-aware access to self-hosted and SaaS applications. **Free tier for up to 50 users** . **The most accessible enterprise ZTNA** .

- **[Palo Alto Prisma Access](https://www.paloaltonetworks.com/prisma/access)**  
  Comprehensive SASE platform with ZTNA, SWG, and firewall capabilities. **Best for Palo Alto ecosystem users** .

- **[Cisco Secure Access](https://www.cisco.com/)**  
  Cisco's SSE platform with ZTNA, secure web gateway, and cloud access security broker.

- **[Tailscale](https://tailscale.com/)**  
  **The easiest WireGuard-based mesh VPN** — identity-aware networking with ACLs, MagicDNS, and SSO. **Free tier for personal use** . **The most developer-friendly ZTNA** .

- **[Perimeter 81](https://www.perimeter81.com/)**  
  ZTNA platform (now Check Point) with cloud-based private networking and secure remote access.

- **[Twingate](https://www.twingate.com/)**  
  **Modern ZTNA for developers** — simple setup, identity-based access, and no network changes. **The easiest enterprise ZTNA to deploy** .

- **[Appgate SDP](https://www.appgate.com/)**  
  Software-defined perimeter with dynamic, identity-centric access controls.

- **[Netskope Private Access](https://www.netskope.com/)**  
  ZTNA within Netskope's SSE platform — private app access with data protection.

## Open-Source GitHub Projects

- **[OpenZiti](https://github.com/openziti/ziti)**  
  **The leading open-source zero trust networking platform**, Apache-2.0 licensed with **2,900+ GitHub stars** . **Comprehensive ZTNA with zero trust principles** — identity-aware, least-privilege access to services . Features **SDKs for Go, Java, Python, Node.js, C, and Swift** . **Embeddable zero trust** — integrate into existing applications . **The most complete open-source ZTNA platform** . **Best for organizations wanting full control over zero trust infrastructure** .

- **[Pomerium](https://github.com/pomerium/pomerium)**  
  **Identity-aware access proxy (IAP) for zero trust**, Apache-2.0 licensed with **4,000+ GitHub stars** . **BeyondCorp-style access** — authenticate and authorize every request . **Integrates with SSO providers (Okta, Azure AD, Google)** . **No VPN required** — access internal apps via identity . **The best open-source identity-aware proxy** . **Best for securing internal web applications** .

- **[Teleport](https://github.com/gravitational/teleport)**  
  **Identity-based access for infrastructure**, Apache-2.0 licensed with **16,000+ GitHub stars** . **Access SSH, Kubernetes, databases, and web apps** with identity-based controls . **Certificate-based access** — no static credentials . **The most comprehensive open-source infrastructure access platform** . **Best for securing infrastructure access** .

- **[BunkerWeb](https://github.com/bunkerity/bunkerweb)**  
  **Open-source next-generation web application firewall (WAF) with ZTNA capabilities**, AGPL-3.0 licensed with **8,000+ GitHub stars** . **Full-featured security** — WAF, ModSecurity, CrowdSec, rate limiting, and **identity-aware access** . **The most complete open-source web security platform with ZTNA** . **Best for protecting web applications with zero trust** .

- **[Pritunl Zero](https://github.com/pritunl/pritunl-zero)**  
  **Open-source BeyondCorp server**, Apache-2.0 licensed . **Zero trust access for privileged SSH and web applications** . **Compatible with OneLogin, Okta, Google, Azure, and Auth0** . **Role-based access policies** . **The best open-source alternative to Teleport and Cloudflare Access** . **Best for SSH and web app zero trust access** .

- **[wg-access-server](https://github.com/Place1/wg-access-server)**  
  **All-in-one WireGuard VPN with web UI**, MIT licensed . **Self-hosted VPN with device management and access controls** . **The simplest open-source ZTNA-like solution** . **Best for small teams wanting simple secure access** .

- **[Gluetun](https://github.com/qdm12/gluetun)**  
  **VPN client with WireGuard and OpenVPN support** — not ZTNA per se, but provides secure network access . **Best for VPN connectivity** .

- **[Headscale](https://github.com/juanfont/headscale)**  
  **Self-hosted Tailscale control server**, BSD-3-Clause licensed . **Open-source alternative to Tailscale's coordination server** . **Use Tailscale clients with your own control plane** . **Best for users wanting Tailscale without vendor dependency** .

- **[Netmaker](https://github.com/gravitl/netmaker)**  
  **WireGuard-based zero trust networking platform**, Apache-2.0 licensed . **Create flat, encrypted overlay networks** — every node is "next door" . **Kernel WireGuard for performance** . **Access policies with IDP integration** . **Best for connecting devices across environments** .

- **[NetBird](https://github.com/netbirdio/netbird)**  
  **Open-source zero trust networking platform**, Apache-2.0 licensed . **WireGuard-based peer-to-peer overlay networks** . **Identity provider integration** for granular access control . **Self-hosted with admin dashboard** . **Best for teams wanting managed-like experience with full data ownership** .

- **[OpenVPN](https://github.com/OpenVPN/openvpn)**  
  **The veteran open-source VPN**, GPL-2.0 licensed . **Not ZTNA** but provides secure remote access . **Best for traditional VPN needs** .

- **[WireGuard](https://github.com/WireGuard/wireguard-linux)**  
  **The modern VPN protocol underlying most ZTNA solutions**, GPL-2.0 licensed . **Kernel-level performance with modern cryptography** . **The building block for Netmaker, NetBird, Tailscale, and Headscale** .

### Additional Strong Open-Source Options

- **Ockam** — Open-source tools for end-to-end encrypted, mutually authenticated communication .
- **BeyondCorp (Google)** — Google's zero trust model (not open-source but foundational research) .
- **Envoy** — Open-source edge and service proxy with RBAC and JWT authentication .
- **Traefik** — Cloud-native application proxy with forward auth middleware .
- **Authelia** — Open-source authentication and authorization server with 2FA and SSO .
- **Authentik** — Open-source identity provider with proxy and forward auth .
- **Keycloak** — Open-source identity and access management with SSO .
- **OAuth2 Proxy** — Reverse proxy providing OAuth2 authentication .
- **Casbin** — Open-source authorization library with ACL, RBAC, and ABAC .

**Frameworks for building custom ZTNA solutions**: Combine **OpenZiti** for comprehensive zero trust networking with embeddable SDKs . Use **Pomerium** for identity-aware access proxy with SSO integration . Deploy **Teleport** for infrastructure access (SSH, Kubernetes, databases) . Choose **BunkerWeb** for WAF + ZTNA protection of web applications . Use **Pritunl Zero** for BeyondCorp-style SSH and web app access . For WireGuard-based overlay networks, **Netmaker** or **NetBird** provide strong foundations . Integrate **Authelia** or **Authentik** for authentication . Note that true enterprise ZTNA with global points of presence, managed SLAs, and advanced threat protection (Zscaler, Cloudflare Access, Palo Alto Prisma) remains primarily commercial territory; open-source stacks provide strong identity-aware access, microsegmentation, and self-hosted zero trust foundations that require integration for complete enterprise deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ZTNA platforms control access to sensitive applications and infrastructure. Self-hosted solutions require proper security hardening, identity provider integration, and access policy management.
- **ZTNA is not a silver bullet** — it must be combined with endpoint security, data protection, and monitoring for complete zero trust architecture .
- **Identity provider integration is critical** — ZTNA is only as strong as your identity verification. Use MFA and device trust for sensitive resources .
- **Open-source ZTNA requires operational expertise** — certificate management, key rotation, and policy tuning are ongoing responsibilities. Commercial platforms provide managed infrastructure and support .
- The open-source ecosystem provides strong identity-aware access, microsegmentation, and self-hosted zero trust foundations, but **global points of presence, managed SLAs, and advanced threat protection** remain primarily commercial offerings.

---

**Made for security engineers, network architects, and organizations seeking zero trust sovereignty.**  
Let's make zero trust network access more open, transparent, and accessible.
