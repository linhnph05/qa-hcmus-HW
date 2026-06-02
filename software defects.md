1. **Spring4Shell, CVE-2022-22965, Spring Framework**

   * source link: [https://spring.io/security/cve-2022-22965](https://spring.io/security/cve-2022-22965) ([Home][1])
   * description: Spring MVC or WebFlux applications on JDK 9+ could be vulnerable to remote code execution through data binding under specific deployment conditions.
   * severity: Critical.
   * consequences: Server takeover, web shell deployment, data theft, and lateral movement.
   * solution: Upgrade Spring Framework to fixed versions and update dependent Spring Boot/Tomcat deployments.

2. **Follina, CVE-2022-30190, Microsoft MSDT**

   * source link: [https://www.microsoft.com/en-us/msrc/blog/2022/05/guidance-for-cve-2022-30190-microsoft-support-diagnostic-tool-vulnerability](https://www.microsoft.com/en-us/msrc/blog/2022/05/guidance-for-cve-2022-30190-microsoft-support-diagnostic-tool-vulnerability) ([Microsoft][2])
   * description: MSDT could be invoked from apps such as Word through a URL protocol, allowing arbitrary code execution.
   * severity: High.
   * consequences: Attackers could run code with the user’s privileges, install programs, alter data, or create accounts.
   * solution: Apply Microsoft security updates and disable the MSDT URL protocol where patching is delayed.

3. **Atlassian Confluence RCE, CVE-2022-26134**

   * source link: [https://confluence.atlassian.com/doc/confluence-security-advisory-2022-06-02-1130377146.html](https://confluence.atlassian.com/doc/confluence-security-advisory-2022-06-02-1130377146.html) ([Atlassian Documentation][3])
   * description: An OGNL injection flaw allowed unauthenticated remote code execution on Confluence Server and Data Center.
   * severity: Critical.
   * consequences: Full Confluence compromise, malware installation, cryptomining, and data exposure.
   * solution: Upgrade to Atlassian’s fixed versions or apply the temporary workaround until upgrade.

4. **OpenSSL X.509 email address buffer overflows, CVE-2022-3602 and CVE-2022-3786**

   * source link: [https://openssl-library.org/post/2022-11-01-email-address-overflows/](https://openssl-library.org/post/2022-11-01-email-address-overflows/) ([OpenSSL Library][4])
   * description: OpenSSL 3.0.0 through 3.0.6 mishandled malicious X.509 email address fields, causing buffer overflow conditions.
   * severity: High.
   * consequences: Denial of service and, for one issue, concern about possible code execution depending on platform conditions.
   * solution: Upgrade OpenSSL to 3.0.7 or later.

5. **MOVEit Transfer SQL injection, CVE-2023-34362**

   * source link: [https://community.progress.com/s/article/MOVEit-Transfer-Critical-Vulnerability-31May2023](https://community.progress.com/s/article/MOVEit-Transfer-Critical-Vulnerability-31May2023) ([Progress Community][5])
   * description: A SQL injection flaw in MOVEit Transfer allowed unauthorized database access.
   * severity: Critical.
   * consequences: Large scale file theft, extortion, regulatory exposure, and supply chain impact.
   * solution: Apply Progress patches, review indicators of compromise, rotate credentials, and investigate possible exfiltration.

6. **Citrix NetScaler ADC and Gateway RCE, CVE-2023-3519**

   * source link: [https://support.citrix.com/external/article/CTX561482/citrix-adc-and-citrix-gateway-security-b.html](https://support.citrix.com/external/article/CTX561482/citrix-adc-and-citrix-gateway-security-b.html) ([Citrix Support][6])
   * description: A vulnerability in NetScaler ADC and Gateway could allow unauthenticated remote code execution in affected configurations.
   * severity: Critical.
   * consequences: Appliance takeover, web shell installation, and internal network compromise.
   * solution: Upgrade to fixed NetScaler versions and inspect exposed appliances for compromise.

7. **libwebp heap buffer overflow, CVE-2023-4863**

   * source link: [https://nvd.nist.gov/vuln/detail/CVE-2023-4863](https://nvd.nist.gov/vuln/detail/CVE-2023-4863) ([NVD][7])
   * description: A heap buffer overflow in libwebp affected Chrome and many other applications that parse WebP images.
   * severity: Critical in Chromium.
   * consequences: Crafted WebP content could cause memory corruption and possible code execution.
   * solution: Update browsers, Electron applications, image tools, and system libwebp packages.

8. **Cisco IOS XE Web UI privilege escalation, CVE-2023-20198**

   * source link: [https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-iosxe-webui-privesc-j22SaA4z](https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-iosxe-webui-privesc-j22SaA4z) ([Cisco][8])
   * description: Attackers exploited the IOS XE web UI to create a high privilege account on affected devices.
   * severity: Critical.
   * consequences: Full device control, unauthorized account creation, implant deployment, and network infrastructure compromise.
   * solution: Upgrade to Cisco fixed releases, disable unnecessary HTTP server exposure, and hunt for unauthorized accounts.

9. **XZ Utils backdoor, CVE-2024-3094**

   * source link: [https://access.redhat.com/security/cve/cve-2024-3094](https://access.redhat.com/security/cve/cve-2024-3094) ([Red Hat Customer Portal][9])
   * description: Malicious code was inserted into upstream XZ Utils 5.6.0 and 5.6.1 release tarballs.
   * severity: Critical.
   * consequences: Potential unauthorized remote access on affected Linux systems.
   * solution: Downgrade or upgrade to safe XZ versions, verify package provenance, and rebuild from trusted sources.

10. **OpenSSH regreSSHion, CVE-2024-6387**

* source link: [https://www.qualys.com/regresshion-cve-2024-6387](https://www.qualys.com/regresshion-cve-2024-6387) ([Qualys][10])
* description: A race condition regression in OpenSSH server on glibc based Linux systems could allow unauthenticated remote code execution.
* severity: Critical.
* consequences: Possible root level compromise of exposed SSH servers.
* solution: Upgrade OpenSSH, restrict SSH exposure, and use rate limiting or login grace time hardening as temporary risk reduction.

11. **CrowdStrike Falcon faulty content update, July 2024**

* source link: [https://www.crowdstrike.com/wp-content/uploads/2024/08/Executive-Summary_Root-Cause-Analysis_Channel-File-291.pdf](https://www.crowdstrike.com/wp-content/uploads/2024/08/Executive-Summary_Root-Cause-Analysis_Channel-File-291.pdf) ([CrowdStrike][11])
* description: A defective Falcon content configuration update caused Windows systems to crash globally.
* severity: Critical operational defect, not a cyberattack.
* consequences: Outages across airlines, healthcare, banking, media, and enterprise IT.
* solution: CrowdStrike deployed fixes and changed testing, validation, and staged rollout processes.

12. **CUPS cups-browsed vulnerability, CVE-2024-47176**

* source link: [https://nvd.nist.gov/vuln/detail/CVE-2024-47176](https://nvd.nist.gov/vuln/detail/CVE-2024-47176) ([NVD][12])
* description: cups-browsed trusted packets from arbitrary sources and could be chained with other CUPS issues.
* severity: High.
* consequences: Remote command execution risk where vulnerable printing services were reachable.
* solution: Patch CUPS packages, disable cups-browsed if unused, and block UDP port 631 from untrusted networks.

13. **Windows CLFS zero day, CVE-2025-29824**

* source link: [https://www.microsoft.com/en-us/security/blog/2025/04/08/exploitation-of-clfs-zero-day-leads-to-ransomware-activity/](https://www.microsoft.com/en-us/security/blog/2025/04/08/exploitation-of-clfs-zero-day-leads-to-ransomware-activity/) ([Microsoft][13])
* description: A use after free flaw in the Windows Common Log File System driver allowed local privilege escalation.
* severity: High.
* consequences: Attackers could elevate privileges after initial access, and Microsoft observed ransomware related exploitation.
* solution: Apply Microsoft’s April 2025 security updates and investigate endpoints for compromise.

14. **Fortinet stack based buffer overflow, CVE-2025-32756**

* source link: [https://fortiguard.fortinet.com/psirt/FG-IR-25-254](https://fortiguard.fortinet.com/psirt/FG-IR-25-254) ([FortiGuard Labs][14])
* description: A stack based overflow in FortiVoice, FortiMail, FortiNDR, FortiRecorder, and FortiCamera allowed remote unauthenticated command execution.
* severity: Critical.
* consequences: Appliance compromise and attacker foothold inside enterprise networks.
* solution: Upgrade affected Fortinet products and review devices for signs of exploitation.

15. **cPanel and WHM authentication bypass, CVE-2026-41940**

* source link: [https://support.cpanel.net/hc/en-us/articles/40073787579671-Security-CVE-2026-41940-cPanel-WHM-WP2-Security-Update-04-28-2026](https://support.cpanel.net/hc/en-us/articles/40073787579671-Security-CVE-2026-41940-cPanel-WHM-WP2-Security-Update-04-28-2026) ([cPanel Support][15])
* description: An authentication bypass issue affected cPanel software versions after 11.40.
* severity: Critical.
* consequences: Unauthorized access to hosting control panels, possible full server and website compromise.
* solution: Apply cPanel’s fixed builds immediately and review logs for suspicious access.

16. **AI/LLM hallucination: ChatGPT fake legal cases in Mata v. Avianca**

* source link: [https://www.reuters.com/legal/new-york-lawyers-sanctioned-using-fake-chatgpt-cases-legal-brief-2023-06-22/](https://www.reuters.com/legal/new-york-lawyers-sanctioned-using-fake-chatgpt-cases-legal-brief-2023-06-22/) ([Reuters][16])
* description: Lawyers submitted legal citations generated by ChatGPT that turned out to be fictitious.
* severity: High for legal reliability.
* consequences: Court sanctions, reputational damage, and legal process disruption.
* solution: Require human verification of AI generated legal work using primary legal databases.

17. **AI/LLM hallucination: Air Canada chatbot misinformation**

* source link: [https://www.americanbar.org/groups/business_law/resources/business-law-today/2024-february/bc-tribunal-confirms-companies-remain-liable-information-provided-ai-chatbot/](https://www.americanbar.org/groups/business_law/resources/business-law-today/2024-february/bc-tribunal-confirms-companies-remain-liable-information-provided-ai-chatbot/) ([American Bar Association][17])
* description: Air Canada’s chatbot gave incorrect information about retroactive bereavement fare refunds.
* severity: Medium to High.
* consequences: Customer harm, compensation order, and confirmation that companies can be liable for chatbot misinformation.
* solution: Ground chatbot answers in approved policy sources, test against current policies, log responses, and provide human escalation.

18. **AI/LLM bias and historical inaccuracy: Google Gemini image generation**

* source link: [https://blog.google/products-and-platforms/products/gemini/gemini-image-generation-issue/](https://blog.google/products-and-platforms/products/gemini/gemini-image-generation-issue/) ([blog.google][18])
* description: Gemini produced historically inaccurate people images because of overcorrection around diversity and representation.
* severity: High reputational and trust impact.
* consequences: Google paused people image generation and faced public criticism.
* solution: Improve prompt interpretation, evaluate historical context handling, test bias scenarios, and relaunch only after stronger validation.

19. **AI/LLM prompt injection or jailbreak: DPD chatbot inappropriate responses**

* source link: [https://www.theguardian.com/technology/2024/jan/20/dpd-ai-chatbot-swears-calls-itself-useless-and-criticises-firm](https://www.theguardian.com/technology/2024/jan/20/dpd-ai-chatbot-swears-calls-itself-useless-and-criticises-firm) ([The Guardian][19])
* description: A customer manipulated DPD’s chatbot into producing inappropriate and brand damaging responses.
* severity: Medium.
* consequences: Viral reputational damage and reduced trust in automated customer support.
* solution: Constrain chatbot behavior, add prompt injection resistance, improve monitoring, and route unresolved issues to human support.

20. **AI/LLM prompt injection: EchoLeak, CVE-2025-32711, Microsoft 365 Copilot**

* source link: [https://nvd.nist.gov/vuln/detail/CVE-2025-32711](https://nvd.nist.gov/vuln/detail/CVE-2025-32711) ([NVD][20])
* description: An AI command injection flaw in Microsoft 365 Copilot could allow unauthorized information disclosure over a network.
* severity: Critical.
* consequences: Potential leakage of sensitive organizational data through AI agent context handling.
* solution: Apply Microsoft’s fix, enforce least privilege for AI agents, separate trusted and untrusted context, and strengthen input and output filtering.

