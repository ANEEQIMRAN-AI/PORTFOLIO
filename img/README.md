# Aneeq Imran – Portfolio (upgraded)

Single-file site: `index.html` (plain HTML/CSS/JS, no build step).
Run: open `index.html` in a browser, or `python3 -m http.server` in this folder. Deploy by uploading the file (e.g. Vercel).
Needs internet for Google Fonts and the Lucide icon script (same as before).

## Maintain
All content lives in the data layer at the top of the `<script>`:
`SKILLS`, `XP`, `CERTS`, `PROJECTS`. Edit there; the page, the Ask Aneeq AI chatbot and the generated CV all update.
Add a project: append an object to `PROJECTS` (copy an existing one). Use `flow:[[label,sub],…]` for an auto-drawn workflow.

## Changed
- Experience, skills (10 categories), education and 8 certifications now match the updated CV exactly.
- Projects: 16 entries, category filters, search, 3 featured (FLEX AI, LinkedIn Automation, Scholarly Help), detail modal with problem, solution, features, workflow, stack, prev/next and deep links (`#proj-flex`).
- Chatbot, hero, about and CV download updated to the new data. Writely.AI is now Scholarly Help.

## Please confirm
- Resume Screening is in your CV and old portfolio but not in the 15-project list; kept as project 16.
- Leather Measurement (97% accuracy, Siddique Leather Works) and Resume Screening (~70% time reduction) come from the old portfolio, not the CV.
- Projects marked as overview-level (X-Ray, Deepfake, Security Monitoring, YOLOv11, Apple Stock, Business Assistant, RAG Chatbot, Conversational/Multi-Agent, Social Posting) use only what the CV supports. Send details, repos, screenshots or demo links to enrich them.
- Covers are generated illustrations, not screenshots. No repo/demo links were invented.
- Old portfolio's Symtera bullets not in the CV were removed.
