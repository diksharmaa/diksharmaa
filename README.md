from pathlib import Path

readme = '''<div align="center">

# Diksha Sharma

**SEO · AEO/GEO · Content Strategy · Brand & PR**

[LinkedIn](https://www.linkedin.com/in/dikshasharma005/) &nbsp;·&nbsp; [Website](https://diksharmaa.com) &nbsp;·&nbsp; [Email](mailto:dikshas1404@gmail.com)

*Making brands easier to discover across search and AI answer engines.*

</div>

---

## About

I’m a marketing professional working across SEO, AEO/GEO, content, brand, and PR. I enjoy connecting strategy with execution—building content systems, testing ideas, and turning insights into useful work.

## Experience

### Head of SEO and Content Marketing
**London Taxi Adverts** · Remote · July 2025–Present

### Freelance SEO Consultant and PR Strategist
**Out Of Office Creative Retreats** · Remote · 2025

### Content Strategist
**GetMega** · Remote · Oct 2024–Feb 2025

### Freelance SEO Content Strategist and Marketer
**Independent** · Remote · 2022–Present

## Selected Highlights

<table>
  <tr>
    <td align="center" width="25%"><h2>31</h2><strong>AI citations</strong><br/><sub>In 90 days</sub></td>
    <td align="center" width="25%"><h2>7.9K+</h2><strong>Impressions</strong><br/><sub>In 90 days</sub></td>
    <td align="center" width="25%"><h2>12K+</h2><strong>Impressions</strong><br/><sub>Over 11 months</sub></td>
    <td align="center" width="25%"><h2>6.8M</h2><strong>Impressions</strong><br/><sub>Content campaigns</sub></td>
  </tr>
</table>

- **AI search visibility:** Built an AEO/GEO content system with 90 AI-optimised blogs, structured data, internal-linking clusters, and citation tracking across ChatGPT, Perplexity, and Claude.
- **Content operations:** Built an automated workflow using Nimbalyst, Google Sheets, and the Semrush API, reducing publishing QA to under 20 minutes per week.
- **Organic growth:** Achieved 460+ clicks over 11 months and first-page rankings for core target keywords within 45 days.
- **Campaign performance:** Supported a 7.5% increase in organic traffic through guest-post campaigns, web stories, and promotional content.
- **B2B communications:** Produced content for Capchase, FRR Forex, and American Healthcare Academy, and developed corporate communications for Gulf Oil India and UGRO Capital.

## Projects

*Selected projects will be added here as I build and publish them.*

---

<div align="center">
<sub>Strategy-minded. Curious by default. Focused on useful outcomes.</sub>
</div>
'''
out = Path("/mnt/data/README_CLEAN.md")
out.write_text(readme, encoding="utf-8")
print("Created clean Markdown README: " + str(out))
