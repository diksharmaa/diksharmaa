from pathlib import Path
import pypandoc

readme = r'''<div align="center">
  <img src="./portrait.png" alt="Illustrated portrait of Diksha Sharma" width="190" />

  <h1>Diksha Sharma</h1>

  <p><strong>SEO · AEO/GEO · Content · Brand & PR</strong></p>

  <p>
    <a href="https://www.linkedin.com/in/dikshasharma005/">LinkedIn</a>
    &nbsp;·&nbsp;
    <a href="https://diksharmaa.com">Website</a>
    &nbsp;·&nbsp;
    <a href="mailto:dikshas1404@gmail.com">Email</a>
  </p>
</div>

---

## About

Marketing professional working across **SEO, AEO/GEO, content, brand, and PR**. I build content strategies and systems that help brands become easier to discover across search and AI answer engines.

I enjoy exploring ideas, connecting strategy with execution, and turning useful insights into practical projects.

## Experience

| Role | Organisation | Highlights |
|---|---|---|
| Head of SEO and Content Marketing | London Taxi Adverts | Built an AEO/GEO content system; generated 31 AI citations and 7.9K+ impressions in 90 days. |
| Freelance SEO Consultant and PR Strategist | Out Of Office Creative Retreats | Achieved 12K+ impressions and 460+ clicks over 11 months; secured first-page rankings for core keywords. |
| Content Strategist | GetMega | Led content campaigns that generated 6.8M impressions and supported a 7.5% increase in organic traffic. |
| Freelance SEO Content Strategist and Marketer | Independent | Created SEO and integrated content for Capchase, FRR Forex, and American Healthcare Academy; supported corporate communications for Gulf Oil India and UGRO Capital. |

## Projects

*Projects coming soon — I'll add selected projects here as I build them.*

---

<p align="center"><sub>Building clearer content systems and better ways to be discovered.</sub></p>
'''
out = Path("/mnt/data/README.md")
pypandoc.convert_text(readme, "md", format="md", outputfile=str(out), extra_args=["--standalone"])
print(f"Updated README created at {out}")
