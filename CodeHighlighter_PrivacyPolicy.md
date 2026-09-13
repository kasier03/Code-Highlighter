# Privacy Policy for Code Highlighter
Effective Date: September 13, 2026

Developer Contact: kartik.cse.edu@gmail.com

## 1. Introduction
Welcome to Code Highlighter ("we," "our," or "us"). We respect your privacy and are committed to protecting your data. This Privacy Policy explains how our Google Docs Add-on handles your information when you use our service.

By installing and using Code Highlighter, you agree to the terms outlined in this Privacy Policy.

## 2. Information We Process
Code Highlighter is designed with privacy-first principles. We do not collect, harvest, store, or share your personal data or source code.

* **Document Text & Code Snippets:** When you activate the add-on to highlight code, the application reads the specific text selection within your active Google Document strictly to process syntax tokens.
* **Processing Execution:** All syntax highlighting and tokenization occur dynamically within the app's execution cycle (leveraging the client-side sidebar and Google Apps Script runtime). Your code snippets and document contents are never saved to any external databases, logs, or third-party servers.
* **User Preferences:** Temporary UI configurations (such as your chosen theme, font family, and font size) are maintained locally within your active session and are not tracked or profiled.

## 3. How We Use Information
The minimal data processed (selected text strings) is used for a single, specific purpose:

* To parse programming language structures (via client-side syntax parsers like Prism.js) and format them back into your Google Document with appropriate color-coding, fonts, and styles.

## 4. Third-Party Services
* **CDNs for Syntax Highlighting:** The add-on's sidebar loads standard, open-source script libraries (such as Prism.js via public content delivery networks like cdnjs.cloudflare.com) to render code themes locally in your browser. These CDNs may log standard technical metadata (such as IP addresses) pursuant to their respective privacy policies.
* **Google Workspace APIs:** The add-on interacts exclusively with Google Docs via official Google APIs (DocumentApp), adhering strictly to Google's API Services User Data Policy.

## 5. Data Sharing and Disclosure
We do not sell, trade, rent, or transfer your data or document contents to any external third parties. We will only disclose information if required by law, court order, or governmental regulation.

## 6. Compliance with International Privacy Laws
We design our software to comply with major global data protection frameworks:

* **European Union (GDPR):** If you are located in the European Economic Area (EEA), you retain rights regarding data access, rectification, and erasure. Because we do not store any personal data or code text on our servers, there is no stored user data to access or delete. Processing is conducted based on user instruction and consent when executing the tool.
* **United States (CCPA/CPRA & State Regulations):** We do not "sell" or "share" personal information (as defined under the California Consumer Privacy Act). No personal profiles are built or monetized.
* **India (Digital Personal Data Protection Act - DPDP):** We process data with explicit notice and consent, adhering to the principle of data minimization. Since no personal data is collected or archived, user privacy risks are mitigated entirely at the infrastructure level.

## 7. Data Security
Because your source code remains within your Google Document environment and is processed purely in-memory during execution, it benefits from Google Cloud's robust, enterprise-grade security infrastructure.

## 8. Changes to This Privacy Policy
We may update this Privacy Policy from time to time. Any changes will be posted directly within our GitHub repository with an updated effective date. Continued use of the add-on after any modifications constitutes acceptance of the updated policy.

## 9. Contact Us
If you have any questions, concerns, or requests regarding this Privacy Policy, please contact the developer at:

* **Email:** kartik.cse.edu@gmail.com