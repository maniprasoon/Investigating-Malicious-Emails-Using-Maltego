# 🕵️‍♂️ Investigating a Malicious Email Using Maltego

This project demonstrates the use of **Maltego**, a powerful OSINT and forensics tool, to investigate a malicious email and uncover its associated entities. The investigation follows a structured process to trace digital footprints, analyze entity relationships, and conclude with a threat profile.

## 📌 Project Objective

To trace the origins and digital footprint of a suspicious email address using Maltego transforms and visualize the relationships between associated domains, data breaches, aliases, documents, and other metadata.

## 🔍 Investigation Workflow

1. **Entity Initialization**  
   Began with the suspicious email: `louiseennis@optusnet.com.au`.

2. **Initiate PoI Investigation**  
   Loaded the email address entity into Maltego to initiate the process.

3. **Run All Transforms**  
   Applied a comprehensive set of transforms to fetch related domains, breaches, social profiles, and document links.

4. **Footprinting and Investigation**  
   Examined connections such as:
   - Data breach via *OnlinerSpambot*
   - Associated domains: `myspace.com`, `oxfam.org.au`, `optusnet.com.au`
   - Leaked credentials and low deliverability scores (via IPQS)
   - Public documents indexed in DocumentCloud

5. **Information Analysis**  
   Assessed the legitimacy, exposure, and historical digital trail of the entity using sources like:
   - [HaveIBeenPwned](https://haveibeenpwned.com/account/louiseennis@optusnet.com.au)
   - [DocumentCloud](https://www.documentcloud.org)

6. **Conclude and Summarize**  
   Identified the email as compromised, widely circulated in spam/breach datasets, and likely used in malicious campaigns.

## 🧠 Key Findings

- Email is **leaked**, **low deliverability**, and tied to **multiple document leaks**.
- Connected to over 20 external entities including URLs and aliases.
- Domain and metadata enrichment provided rich intelligence for reporting.

## 🛠️ Tools Used

- **Maltego CE** – Entity-based visualization and transformation
- **HaveIBeenPwned** – Breach exposure data
- **DocumentCloud** – Public intelligence resources
- **IPQualityScore (IPQS)** – Email validation and risk tagging

## 📄 License

This investigation uses public intelligence sources under CC-BY 4.0 and is intended strictly for educational and ethical cybersecurity analysis.

---

> 🚨 *Disclaimer: This project is for educational and research purposes only. Do not use these techniques on real systems without proper authorization.*

