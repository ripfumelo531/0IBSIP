# Patch Management

## Introduction
Patch management is the process of identifying, assessing, testing, deploying, and verifying updates to software, operating systems, and devices. Patches fix defects and may address security vulnerabilities.

## CVEs
A Common Vulnerabilities and Exposures (CVE) identifier is a standardized reference for a publicly known cybersecurity vulnerability. CVE identifiers help organizations communicate consistently about specific vulnerabilities. A CVE record does not by itself describe an organization's exposure or guarantee that a patch is available.

## Examples and consequences
- **WannaCry (2017):** exploited a Windows vulnerability for which a security update had been released before the outbreak. Organizations that had not applied the update were among those affected. Consequences included disruption to services and operational costs.
- **Equifax (2017):** attackers exploited a known Apache Struts vulnerability in an internet-facing application. The breach exposed sensitive personal information. The incident highlighted the importance of asset visibility, timely patching, and verification.

## Patch-management lifecycle
1. **Discovery:** identify devices, applications, versions, and missing updates.
2. **Assessment:** evaluate severity, exploitability, and business impact.
3. **Testing:** test updates in a controlled environment for compatibility.
4. **Deployment:** roll out approved patches using a managed process.
5. **Verification:** confirm installation and check that the vulnerability is addressed.

## Seven-step checklist
1. Maintain an accurate asset inventory.
2. Subscribe to trusted vendor security advisories.
3. Prioritize actively exploited and critical vulnerabilities.
4. Back up important data and prepare rollback plans.
5. Test patches before broad deployment when practical.
6. Deploy updates within defined time targets.
7. Verify installation and document exceptions.

## Common challenges
Organizations may face legacy systems, limited budgets, downtime concerns, compatibility problems, and incomplete asset inventories. Risk-based prioritization, automation, maintenance windows, and clear ownership can help address these challenges.

## Conclusion
Effective patch management reduces exposure to known vulnerabilities. It requires continuous asset discovery, risk-based decisions, careful deployment, and verification rather than simply installing updates occasionally.

## References
- CISA, Known Exploited Vulnerabilities Catalog: https://www.cisa.gov/known-exploited-vulnerabilities-catalog
- NIST, Guide to Enterprise Patch Management Planning: https://csrc.nist.gov/pubs/sp/800/40/r4/final
- Microsoft Security Update Guide: https://msrc.microsoft.com/update-guide
- Apache Struts security bulletins: https://struts.apache.org/
- US-CERT / CISA WannaCry resources: https://www.cisa.gov/
