# Licensing for Citation Enforcement and Non-Commercial Use on GitHub

## Overview

Licenses that **enforce citation (attribution)** and **restrict commercial use** are less common in traditional open source software licensing but are widely used in academic and creative contexts. This document summarizes their features, GitHub availability, and best practices for academic software projects.

---

## License Types and Characteristics

| License Type                     | Enforces Citation (Attribution) | Restricts Commercial Use | Suitable for Software Code? | OSI Approved? | Typical Use Case                          |
|---------------------------------|---------------------------------|-------------------------|-----------------------------|---------------|-------------------------------------------|
| **Creative Commons Attribution-NonCommercial (CC BY-NC)** | Yes                             | Yes                     | No (not recommended)         | No            | Documentation, datasets, academic works   |
| **Custom Non-Commercial Licenses**                       | Often                          | Yes                     | Depends                     | No            | Research software with special restrictions|
| **Permissive Licenses (MIT, BSD, Apache 2.0, ISC)**      | Attribution via license text    | No                      | Yes                         | Yes           | Broad software use with commercial rights |
| **Copyleft Licenses (GPL v3)**                           | Attribution                    | No                      | Yes                         | Yes           | Ensuring software freedom and source openness|

---

## GitHub License Picker Availability

| License Type                     | Available in GitHub License Picker? | Notes                                                        |
|---------------------------------|------------------------------------|--------------------------------------------------------------|
| MIT, Apache 2.0, BSD, GPL       | Yes                                | Standard open source licenses                                 |
| Creative Commons BY-NC           | No (must add manually)              | Not recommended for software code; mainly for non-code assets|
| Custom Non-Commercial Licenses  | No                                 | Must be manually added with LICENSE file                      |
| Citation Request via `CITATION.cff` | No (manual addition of file)      | Encourages citation without legal enforcement                 |

---

## Practical Considerations

- **Open Source Definition and Commercial Use**:  
  OSI-approved licenses **must allow commercial use**. Therefore, licenses restricting commercial use **are not classified as open source**.

- **Citation Enforcement**:  
  Traditional open source licenses require **attribution in license text** but **do not legally enforce scholarly citation**.  
  To promote academic citation without legal restrictions, use the [`CITATION.cff`](https://citation-file-format.github.io/) file in your GitHub repository.

- **Creative Commons Licenses for Non-Commercial Use**:  
  The **CC BY-NC** license enforces attribution and prohibits commercial use but is intended for non-software content (documentation, datasets). It is not suitable for software code licensing.

---

## Recommendations for Academic Software Projects on GitHub

| Goal                               | Recommended Approach                                    |
|-----------------------------------|--------------------------------------------------------|
| Enforce legal non-commercial use  | Use **CC BY-NC** license for non-code assets only, add LICENSE manually |
| Promote scholarly citation only   | Use permissive license (e.g., MIT) + `CITATION.cff` file to encourage citation |
| Maximize reuse and adoption       | Use standard permissive licenses (MIT, Apache 2.0)     |

---

## Useful Links and References

- [GitHub Licensing Documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)  
- [Creative Commons Licenses](https://creativecommons.org/licenses/)  
- [Citation File Format (`CITATION.cff`)](https://citation-file-format.github.io/)  
- Morin, A., Urban, J., & Sliz, P. (2012). “A quick guide to software licensing for the scientist-programmer.” *PLoS Computational Biology*, 8(7), e1002598.  
  https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002598

---

## Example: Adding a `CITATION.cff` File

```yaml
cff-version: 1.2.0
message: "If you use this software, please cite it as below."
authors:
  - family-names: Suhermanto
    given-names: Mukhamad
    orcid: "https://orcid.org/0000-0003-1871-280X"
title: "Awesome Thermodynamics for Engineers"
version: "v1.0"
doi: "10.1234/yourdoi"
date-released: 2025-06-01
