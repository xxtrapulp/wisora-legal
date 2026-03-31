# Wisora Privacy Policy

**Effective Date:** March 31, 2026

**Plain English Summary:** Wisora is designed to protect you from bad car deals. To do this, when you activate the extension on a supported automotive listing (like AutoTrader or CarGurus), we read the vehicle's public data (Make, Model, Year, Price, VIN, and CarFax history) from the page. We send this publicly available vehicle information to our secure AI servers (and third-party AI providers like Google Gemini) to generate your Wisdom Score and Verdict. **We do not track you across the web. We do not sell your personal data. We do not inject ads.** The extension only wakes up and reads data on the specific car sites it is built to analyze.

---

## 1. Introduction
Welcome to Wisora ("we," "our," or "us"). This Privacy Policy explains how our Chrome Extension, Wisora — Smart Car Deal Checker ("the Extension"), collects, uses, processes, and protects your information. By installing and using the Extension, you agree to the data practices described in this policy. 

This policy is designed to comply with the Google Chrome Web Store Developer Program Policies, the General Data Protection Regulation (GDPR), and general consumer privacy standards.

## 2. Information Collected
Wisora minimizes data collection to only what is strictly necessary to provide its core functionality.

*   **Webpage Content (Restricted):** The Extension requests `host_permissions` strictly for specific, supported automotive marketplaces (e.g., AutoTrader, CarGurus, Cars.com, Kijiji, Craigslist, Carvana) and vehicle history providers (CarFax). When you view a listing on these sites, the Extension reads public listing data (Make, Model, Year, Trim, Mileage, Price, VIN, and raw text history reports) from the webpage’s HTML framework.
*   **User Input:** If you manually enter a VIN into the Extension, we collect that input to process the analysis.
*   **Technical Data:** We automatically collect non-identifiable technical data to facilitate the API request, such as browser type, extension version, and generic error logs, purely for maintaining stability.
*   **Local Storage:** The Extension uses your browser's local storage API (`chrome.storage.local`) to save your analysis history locally on your machine, allowing you to re-open closed analyses rapidly without re-processing.

## 3. How Information Is Used
We process your data exclusively to provide and improve the Extension’s core functionality:
*   Extracting vehicle data to cross-reference fair market value algorithms.
*   Sending raw automotive text to third-party AI models to generate English-language risk summaries ("The Verdict").
*   Caching results in our remote database to rapidly serve identical vehicle analyses to other users looking at the exact same public car listing.

**We do not use your data for advertising, profiling, or cross-site tracking.**

## 4. Legal Basis for Processing (GDPR)
For users in the European Economic Area (EEA), our legal basis for processing your data is **Legitimate Interest** and **Contractual Necessity**. Because the Extension's primary service requires real-time algorithmic processing of the webpage you are requesting an analysis on, data processing is strictly necessary to fulfill the service you initiate.

## 5. Data Sharing and Third Parties
To function intelligently, Wisora transmits extracted vehicle data (such as VIN, Year, Make, Model, and CarFax text) to our backend API. 
*   **AI Processors:** The backend securely passes this anonymized automotive data to third-party Large Language Model providers (e.g., Google Gemini API) to generate the written Verdict. 
*   **We NEVER sell, rent, or trade your personal data or user-specific metrics to any third parties.**

## 6. Data Retention
*   **Vehicle Data:** Publicly available vehicle data (VINs, listing prices, analysis results) is permanently cached in our secure database to speed up future requests for that exact vehicle. 
*   **Personal Data:** We do not permanently store tying identifiers (like your IP address or browser fingerprint) alongside the cached vehicle analyses. 
*   **Local Data:** You can clear your localized extension history at any time by clearing your Chrome browser data or uninstalling the Extension.

## 7. Data Security Measures
All data transmission between the Extension and our API occurs over secure, encrypted connections (HTTPS/TLS). While we use commercially acceptable methods to protect the data we process, no method of transmission over the internet is completely secure, and we cannot guarantee absolute security.

## 8. User Rights (GDPR)
If you reside in a jurisdiction with comprehensive data privacy laws (like the GDPR), you have the right to request access to, correction of, or deletion of any personal data we hold. Because we do not require account creation, our ability to identify "your" specific data in our systems is deliberately limited by design. If you have concerns, you may contact us using the information below.

## 9. Cookies and Tracking
The Extension **does not** use cookies for tracking, nor does it inject third-party analytical trackers into your browser. 

## 10. Children’s Privacy
Wisora is not directed toward children under the age of 13 (or 16 in the EEA), and we do not knowingly collect personal data from children. If we become aware that we have inadvertently collected such data, we will delete it immediately.

## 11. Changes to This Policy
We may update this Privacy Policy from time to time as we add support for new sites or adjust our APIs. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date."

## 12. Contact Information
If you have any questions or concerns about this Privacy Policy or our data practices, please contact us at:
INSERT_YOUR_EMAIL_HERE
