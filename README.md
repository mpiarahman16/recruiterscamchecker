# Recruiter Scam Checker

A small, private, browser-only tool for spotting fake recruiters on LinkedIn and fake job offers.

## What it does

1. **Recruiter check**: paste a recruiter's LinkedIn profile and their message. It flags common scam patterns:
   - requests to move to WhatsApp or Telegram
   - personal email addresses
   - fake-check or equipment-purchase schemes
   - requests for your SSN or bank details
   - chat-only interviews
   - fees and pressure tactics
   - thin profiles with few connections
2. **Job check**: enter the job title, company, pay and the link they sent. It flags:
   - lookalike or unrelated domains
   - short links and Google Forms
   - pay that is unrealistic for the role
   - vague descriptions

   It also gives you one-click lookups on the company's careers site, LinkedIn Jobs, Indeed, Glassdoor, salary data, scam reports, WHOIS (how old the domain is), ScamAdviser and Google Safe Browsing.
3. **Quick checks**: six yes/no questions based on LinkedIn's *About this profile* panel. This covers verification, account age, photo, mutual connections, activity, and whether the job appears on the official careers site.

You get a 0–100 risk score, a verdict, and a list of every red flag and positive signal it found.

## Privacy

Everything runs locally in your browser. Nothing you paste is sent or stored anywhere.

## Run it

Open `index.html` in any browser. You can also publish it with **GitHub Pages**: go to Settings → Pages, choose "Deploy from a branch", select `main` and `/ (root)`.

## Disclaimer

This is a heuristic screening aid, not proof. Always verify a role directly with the company before sharing personal information. To report fake profiles, use LinkedIn's Report option. In the US you can also report at reportfraud.ftc.gov.
