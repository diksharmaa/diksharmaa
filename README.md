from pathlib import Path

readme = '''<div align="center">

# Diksha Sharma

**SEO · AEO/GEO · Content Strategy · Brand & PR**

<a href="https://www.linkedin.com/in/dikshasharma005/">LinkedIn</a>
&nbsp; · &nbsp;
<a href="https://diksharmaa.com">Website</a>
&nbsp; · &nbsp;
<a href="mailto:dikshas1404@gmail.com">Email</a>

*Making brands easier to discover across search and AI answer engines.*

</div>

---

## About

I’m a marketing professional working across **SEO, AEO/GEO, content, brand, and PR**. I enjoy connecting strategy with execution—building content systems, testing ideas, and turning insights into useful work.

## Experience

| Role | Organisation | Focus |
|---|---|---|
| **Head of SEO and Content Marketing** | London Taxi Adverts | AEO/GEO strategy, content systems, AI visibility |
| **Freelance SEO Consultant and PR Strategist** | Out Of Office Creative Retreats | Organic growth, content, booking conversions |
| **Content Strategist** | GetMega | SEO campaigns, guest posts, web stories |
| **Freelance SEO Content Strategist and Marketer** | Independent | SEO content, integrated marketing, corporate communications |

## Selected Highlights

<table>
  <tr>
    <td align="center" width="25%">
      <h2>31</h2>
      <strong>AI citations</strong><br/>
      <sub>Generated in 90 days</sub>
    </td>
    <td align="center" width="25%">
      <h2>7.9K+</h2>
      <strong>Impressions</strong><br/>
      <sub>Within 90 days</sub>
    </td>
    <td align="center" width="25%">
      <h2>12K+</h2>
      <strong>Impressions</strong><br/>
      <sub>Organic campaign</sub>
    </td>
    <td align="center" width="25%">
      <h2>6.8M</h2>
      <strong>Impressions</strong><br/>
      <sub>Content campaigns</sub>
    </td>
  </tr>
</table>

- **AI search visibility:** Built an AEO/GEO system with 90 AI-optimised blogs, structured data, internal-linking clusters, and citation tracking across ChatGPT, Perplexity, and Claude.
- **Lean content operations:** Created an automated workflow using Nimbalyst, Google Sheets, and the Semrush API, reducing the publishing process to under 20 minutes of QA per week.
- **Organic growth:** Earned 460+ clicks over 11 months and secured first-page rankings for core target keywords within 45 days.
- **Content performance:** Supported a 7.5% increase in organic traffic through guest-post campaigns, web stories, and promotional content.
- **B2B and corporate communications:** Produced content for Capchase, FRR Forex, and American Healthcare Academy, and developed corporate communications for Gulf Oil India and UGRO Capital.

## Projects

*Selected projects will be added here as I build and publish them.*

---

<div align="center">
  <sub>Strategy-minded. Curious by default. Focused on useful outcomes.</sub>
</div>
'''
out = Path("/mnt/data/README.md")
out.write_text(readme, encoding="utf-8")
print(f"Clean README saved to {out}")
