# Security Policy

## MagicUser Theme Security

This security policy outlines the security measures implemented in the MagicUser theme for Obsidian, which adheres to Obsidian Developer Policies (https://docs.obsidian.md/Developer+policies).

**Theme Composition:**

* This free and open-source theme is built entirely with CSS and does not include JavaScript code (**theme.css** file).
* The other file is a **manifest.json** file with general theme information.

**Security Benefits:**

* **No Data Access:** The theme does not access or store any user data.
* **No Code Execution:** The theme is purely CSS and does not execute any code, eliminating the risk of malicious script injection.
* **No Network Requests:** The theme adheres to Obsidian Developer Policies by not making any network requests. It relies solely on its embedded assets (secure SVG icons).
* **Embedded Assets:** All theme assets are included within the theme itself, with no external connections.

**Security Recommendations:**

* **Trusted Sources:** Always install this theme from trusted sources, such as the Obsidian application or the theme's official GitHub repository.
* **Theme Updates:** While the risk of vulnerabilities in pure CSS is lower, keeping your theme updated ensures you benefit from any improvements or bug fixes that might enhance security.

**Reporting Vulnerabilities:**

If you suspect a vulnerability in this theme, please follow these responsible disclosure practices:

* **Do not publicly disclose the vulnerability.** Public disclosure can leave users vulnerable before a fix is implemented. Contact the developer/repository owner (@drbap).
* **Provide a clear description of the vulnerability and the steps to reproduce it.**

By following these guidelines, you can ensure a secure and reliable experience when using the MagicUser theme.
