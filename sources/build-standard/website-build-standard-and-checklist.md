# BlackFox Studios Website Build Standard and Checklist (mirror)

| | |
| --- | --- |
| Source | Google Doc "BlackFox Studios Website Build Standard and Checklist", BlackFox Studios shared drive, Website folder |
| Drive doc id | 1V5vzPKHiSivaupSzS1teWeOL_e6EbS9qFcOnnY99-ZQ (opens only for people the Doc is shared with) |
| Date written in the Doc | November 11, 2026 (Version 1.0) |
| Drive dates | Created 2026-11-11, last modified 2026-11-11 |
| Copied | 2026-11-15 by Claude. The Doc's text was read through the Google Docs API and checked line by line against the November 11 markdown draft the Doc was made from. The words match; this file keeps the draft's markdown formatting (numbered lists, the Part 0 block and the Evidence Folder layout as code blocks). |

**The Doc is the record. This file is a mirror.** Edit the Google Doc, then copy it here again and update the date above. Never edit only this file.

**What it is:** The BlackFox Studios standard for building a client website. Intake questions that turn sections on or off, instructions to paste into an AI site builder, and pass or fail checks on rights and releases (photos, music, people's likeness, AI-made media), accessibility, privacy and tracking, email lists, donations, security and the domain, plus the launch gate, upkeep, the Evidence Folder and the sources behind each rule.

**Why it is here:** It is the legal, privacy and licensing layer under this playbook's own [twenty-point pre-launch checklist](../../mod-11.html). Module 11 covers phone, speed, search basics and the common accessibility checks; this standard covers what a site needs before it is safe to hand to a client. Keeping its text in the repo lets any person or AI read it without the Doc being re-sent.

**Reading notes:** It is a build standard, not legal advice; items marked LAWYER need a lawyer's review. It names no clients. Laws and figures are as of the Doc's date, with sources [S1] to [S41] at the end; the Doc says to review it every six months and whenever a law it cites changes.

A document's date is when an idea was recorded, not when it started.

---

Version 1.0 | Owner: BlackFox Studios | Written: November 11, 2026 | Review: every 6 months, and whenever a law below changes

This is not legal advice. It is a build standard. Items marked LAWYER need a lawyer's review before you rely on them for a specific client.

---

## How to use this document

1. Run the Intake Questions (Part 1) with the client before any build. The answers turn sections on or off.
2. Give Part 0 (the AI instructions) and Parts 2 to 8 to the AI or person building the site.
3. Before launch, run every check that applies. Each check is pass or fail. A site does not launch with a fail on any item marked MUST.
4. Save the proof of each check in the site's Evidence Folder (Part 9). The folder is what you hand a lawyer, a funder, or a demand-letter sender.
5. Re-run the checks after any major edit and at least once a year.

Order of the parts is deliberate. Protections against bad-faith actors come first (Part 2), because one unlicensed photo, one missing release, or one inaccurate claim about a person is the cheapest opening a bad-faith actor can find. The regular baseline (accessibility, privacy, fundraising, security) comes after.

Severity labels:
- MUST: launch blocker.
- SHOULD: fix before launch unless the client signs off in writing on the reason.
- IF: applies only when the intake answer turns it on.

## Who does what

| Step | Does it | Owns the result | Consulted | Told |
|---|---|---|---|---|
| Intake (Part 1) | BlackFox lead | BlackFox lead | Client | Builder |
| Rights Log and releases (2.1 to 2.3) | Client gathers, builder records | Client | BlackFox lead | |
| Content sourcing review (2.4, 2.5) | BlackFox lead | Client | Lawyer if LAWYER item | |
| Build (Parts 3 to 7) | Builder (person or AI) | BlackFox lead | | Client |
| Launch gate (8.1) | BlackFox lead | BlackFox lead | | Client |
| Claims and takedowns (2.6) | Client | Client | Lawyer | BlackFox lead |
| Upkeep (8.3) | Client, or BlackFox under a support agreement | Client | | |

## Exceptions

| Situation | What to do |
|---|---|
| Client insists on an image with no license | Do not publish it. Offer a licensed or owned replacement, or leave a placeholder. Note the refusal in the Evidence Folder. |
| Release cannot be found for a historical photo | Keep it off donate pages and ads, add a caption with context and source, record reliance on the historical exemption, flag LAWYER. |
| Platform cannot meet a WCAG item (for example, inside an embed) | Record it as a known limit in the accessibility statement, give an alternative format on request, and log it. |
| Client wants a tracking pixel for ads | Stop. Needs written client sign-off after a lawyer review, a consent mechanism that works before the tag loads, and a privacy policy update. Not available on Google Sites. |
| Client already owns a site with an overlay widget | Remove it as a compliance claim; run Part 3 checks as normal. |
| A demand letter or CCB notice arrives | Follow the procedure in 2.6. Do not reply or pay before a lawyer reviews. |
| Domain is in a former developer's name | Client requests transfer through the registrar; BlackFox does not build until the client controls it or accepts the risk in writing. |

## How we know it works

| Measure | Target | How measured |
|---|---|---|
| Assets matched to the Rights Log at launch | 100% | Launch gate count |
| MUST items failed at launch | 0 | Signed launch sheet |
| Automated accessibility errors at launch | 0 errors (warnings reviewed) | WAVE and axe exports |
| Takedown or correction requests acknowledged | Within 5 business days | Claims log |
| Sites re-checked in the last 12 months | 100% of active sites | Upkeep calendar |

---

## Part 0. Instructions to an AI site builder

Paste this block at the top of any AI build session, followed by Parts 2 to 8.

```
You are building a website to the BlackFox Studios Website Build Standard.
Rules you must follow:
1. Do not insert any image, video, audio clip, logo, font, or block of text unless it is listed in the site's Rights Log with a source and a license. If you need a placeholder, label it "PLACEHOLDER, NOT LICENSED" in visible text.
2. Do not generate or alter an image, video, or voice of a real, identifiable person. Do not "restore," colorize, upscale, or fill in a historical photo or film of a real person unless the Rights Log says the client approved it, and then label it on the page as altered.
3. Mark every AI-generated or AI-altered image, video, or audio with a visible caption, for example "Image created with AI" or "Photo restored with AI tools."
4. Do not state facts about real people (dates, roles, awards, relationships, causes of death, legal matters) unless a source is listed in the Rights Log or the client supplied the text. Keep a citation for every factual claim about a person or event.
5. Build to WCAG 2.2 AA. Every image gets alt text (or is marked decorative). Use real heading levels in order. Every form field gets a visible label. Every link says where it goes. Text contrast at least 4.5:1, large text at least 3:1.
6. Add no tracking pixels, ad tags, session-replay tools, chat widgets, or accessibility overlay widgets. If analytics are requested, stop and ask.
7. Every page footer links to: Privacy Policy, Accessibility Statement, Terms of Use, Corrections and Takedown Requests, Contact. Add Consumer Health Data Privacy Policy when the intake says health data is collected.
8. Do not write marketing claims that cannot be proven (for example "fully accessible," "100% secure," "the only," "the first").
9. Produce, with the build, a list of every asset you used and where it came from, so the Rights Log can be checked.
```

---

## Part 1. Intake questions (turn sections on or off)

Ask every client. Record the answers in the Evidence Folder.

| # | Question | If yes, turns on |
|---|---|---|
| Q1 | Will the site show photos, film, audio, or artwork the client did not create? | 2.1, 2.2 |
| Q2 | Will the site show identifiable people, living or dead? | 2.3 |
| Q3 | Will the site tell history or make claims about real people or organizations? | 2.4 |
| Q4 | Will any content be made or altered with AI? | 2.5 |
| Q5 | Can visitors upload, comment, or post anything? | 2.7 |
| Q6 | Does the client have a physical location (office, venue, program site, store)? | Raises Part 3 risk |
| Q7 | Does any funding come from federal sources, directly or passed through a state, county, or city? Which agency? | 3.9 |
| Q8 | Is the site built for or paid for under a government contract, or for a government program? | 3.9 |
| Q9 | Will any form ask about health, medications, allergies, disability, pregnancy, counseling, or similar? Is the client health-adjacent? | 4.3 |
| Q10 | Is any part of the site meant for children under 13, or will children use it? | 4.5 |
| Q11 | Will the client send email newsletters, or sell tickets, tuition, merchandise, or services by email? | 5.1, 5.2 |
| Q12 | Will the site ask for donations? Is the client a 501(c)(3), fiscally sponsored, or neither? | Part 6 |
| Q13 | Will the site take payments? | 6.4 |
| Q14 | Who owns the domain and the hosting account today? | 2.8 |

---

## Part 2. Bad-faith and content-liability protections (do these first)

Why first: image-licensing agents send demand letters for "thousands" of dollars with 14-day deadlines, often at premium commercial rates even for low-traffic nonprofit use [S1]. The Copyright Claims Board (CCB) lets a claimant bring a case for a small filing fee, and about two thirds of claimants have no lawyer; pictorial and graphic works are the largest category of claims (36%), and 2,304 claims had been filed by September 2026 [S2][S3]. Washington's personality rights law covers fundraising uses by nonprofits [S6]. Each item below closes one of those openings with a record.

### 2.1 Rights Log for every asset (MUST)

- What it is: one spreadsheet row for every photo, video, audio clip, logo, font, illustration, and long quote on the site.
- Why: without a license record, the only defense to a demand letter is to argue, and the CCB opt-out clock is 60 days [S4].
- Columns: Asset ID | File name | Page URL where used | Type | Creator | Owner of rights | Source (owned, commissioned, licensed, public domain, Creative Commons, AI-generated) | License name and link | License ID or receipt | Date obtained | Attribution text required | Release on file (Y/N, ID) | Expiry or limits | AI used (Y/N, how).
- Check: open the live site. Every visible asset matches a row. Every row with a license has the receipt or license text saved in the Evidence Folder. Pass only if zero unmatched assets.

### 2.2 Use only clean sources (MUST)

- Allowed sources, in order of preference: client-owned originals; work commissioned with a written assignment or license; public domain with the basis noted; licensed stock with the license saved; Creative Commons with the exact license and attribution recorded.
- Not allowed: images found in a web search, social media, news sites, or other organizations' sites; "royalty free" images without the license page saved.
- Music: a recording has two sets of rights, the sound recording and the underlying composition. Record both. Under the Music Modernization Act, sound recordings published in 1925 or earlier are now public domain; recordings published 1957 to February 15, 1972 stay protected until 2067 [S7]. The composition may have its own owner. LAWYER for any recording the client did not make.
- Film and family footage: record who shot it, who holds it now, and who gave permission to post.
- Check: every row in the Rights Log has an allowed source. Every Creative Commons asset shows the required credit on the page.

### 2.3 Releases for people shown (MUST if Q2)

Washington protects the name, voice, signature, photograph, likeness, and (since June 10, 2026) "forged digital likeness" of living and dead people. Use "for fund-raising or solicitation of donations" counts, whether or not the user is a nonprofit. Protection lasts 10 years after death for an individual and 75 years after death for a "personality" with commercial value. The penalty is $3,000 plus damages, and the winner gets attorney fees [S6][S8]. Cultural, historical, educational, and newsworthy uses are broadly exempt [S6].

Release tiers:
1. Living, identifiable person shown anywhere near a donate page, a fundraising appeal, merchandise, or an ad: signed written release on file.
2. Person who died within the last 10 years, or a well-known person who died within the last 75 years, used in fundraising or ads: written permission from the heir or estate.
3. Historical or archival display with a caption and context, kept off donate pages and ads: may rely on the historical and educational exemption. Note the reliance in the Rights Log. LAWYER if unsure.
4. Never: AI-made or AI-altered depictions of a real person that could pass as genuine.

- Check: every asset with a person has a release ID or a written note of the exemption relied on. No person's image appears on a donate page or appeal without a tier 1 or tier 2 release.
- Release form fields: name; what is covered (photo, video, voice, name); where it may be used (website, social, print, fundraising); duration; right to withdraw for future uses; signature and date; parent or guardian signature for minors.

### 2.4 Source citations and defamation-safe content (MUST if Q3)

- Rules for writing about real people and organizations:
  1. Every factual claim about a person or event has a source in the Rights Log or a "Sources" note on the page.
  2. State facts, not conclusions about character. Write "the court records show X," not "X was a fraud."
  3. Opinions are written as opinions and attributed.
  4. Quotes are exact, with a source and date.
  5. Do not repeat accusations, health details, or legal trouble of living people unless the client supplies a source and has a reason to publish it.
- Why: Washington recognizes defamation and false light claims; the limitation period for defamation is 2 years [S9]. Washington's anti-SLAPP law (the Uniform Public Expression Protection Act) lets a defendant sued over speech on a matter of public concern move to dismiss within 60 days of service, pauses discovery, and awards fees to a defendant who wins. It does not cover federal claims such as copyright [S10].
- Check: a reviewer can find a source for every factual sentence about a named person. Pass only if none are missing.
- LAWYER: any page that makes negative claims about a living person or a business.

### 2.5 AI-assistance disclosure (MUST if Q4)

- No federal or Washington law found that requires AI labels on an ordinary nonprofit or small business site as of November 2026. Labeling is a protective practice, not a mandate [S11]. Exceptions: Washington's election deepfake law requires the line "This (image/video/audio) has been manipulated" on synthetic media in electoral communications (now RCW 29B.35) [S12]; Washington's AI companion chatbot law (effective January 1, 2027) requires an AI disclosure for companion-style chatbots [S13].
- Why still label: it removes the "you passed off a fake as real" accusation, matters most where a viewer could mistake an AI-restored image for a historical record, and fits Washington's new forged digital likeness rule [S8].
- Copyright point: the U.S. Copyright Office says prompts alone do not make a person the author of AI output. AI-generated material the client did not shape by hand may not be protected by copyright, so others may be free to copy it [S14].
- Rules:
  1. Caption every AI-generated or AI-altered image, video, or audio on the page where it appears.
  2. Add a short "How we use AI" line on the About or Terms page: what AI was used for (drafting text, restoring images, translation) and that people reviewed it.
  3. Record in the Rights Log which tool was used and what a person changed.
- Check: every Rights Log row with "AI used = Y" has a visible caption on its page. The "How we use AI" line exists.

### 2.6 Copyright takedown, corrections, and contact policy (MUST)

- Page title: "Corrections and Takedown Requests." Link it in the footer.
- Contents:
  1. One email address and a postal address for requests.
  2. What to include: the page link, the content at issue, the requester's name and contact, and the basis (they own it, they are shown in it, it is inaccurate).
  3. What the client does: acknowledges within 5 business days; takes disputed copyrighted content down while reviewing; fixes errors and notes the correction date on the page.
  4. A statement that the client respects copyright and the rights of people shown.
- Internal procedure (write it in the Evidence Folder):
  1. Who opens mail from ccb.gov, from image agencies, and from lawyers.
  2. On receipt: take the image down, delete the file from the site's storage too (agents check the direct file link), and save a screenshot of the page before removal [S1].
  3. Put the CCB 60-day opt-out deadline on the calendar the day a claim arrives [S4].
  4. Do not admit fault or pay before a lawyer reviews. LAWYER.
- DMCA safe harbor: it protects only content posted by users, not content the client posts itself. It matters only if Q5 is yes (see 2.7) [S5].
- Check: the page exists, is linked from every page footer, and the address on it receives mail (send a test).

### 2.7 User-posted content (IF Q5)

- Prefer no uploads and no comments. If the client wants them:
  1. Register a DMCA designated agent with the U.S. Copyright Office ($6) and renew it at least every 3 years; a lapse removes the safe harbor for that period [S5].
  2. Post a repeat-infringer policy and community rules.
  3. Moderate before publishing.
- Section 230 protects a site from most claims over what users post, but not from federal intellectual property claims. LAWYER on any state right of publicity claim from user posts.
- Check: if uploads or comments are on, the designated agent shows as active in the Copyright Office directory, with the renewal date on the calendar.

### 2.8 Client owns the domain and every account (MUST)

- The domain registrant has the rights to use, renew, restore, and transfer it [S15]. A developer who registers the domain in their own name controls the client's web address.
- Rules:
  1. The domain is registered in the client's legal name, on an account the client controls, with a client email address that is not tied to one staff member (for example, an admin@ address).
  2. Hosting, Google Workspace, site builder, analytics, and form accounts are owned by the client. BlackFox Studios gets user or admin access, not ownership.
  3. Auto-renew is on. The renewal date is in the Evidence Folder.
  4. Two client people have recovery access.
- Check: the registrar's lookup shows the client as registrant. The account inventory (Part 9) lists owner, admin users, and recovery contacts for every account.

### 2.9 Records kept as evidence (MUST)

- Keep the Evidence Folder (Part 9) for the life of the site plus 3 years. Copyright claims generally have a 3-year limit, and the defamation period is 2 years.
- Take a dated full-page capture of every page at launch and after major changes.
- Check: the folder exists, is owned by the client, and has the launch captures.

---

## Part 3. Accessibility (ADA baseline)

Why: website accessibility suits in federal court rose from 2,452 in 2024 to 3,117 in 2025, 36% of all federal ADA Title III cases [S16]. Counting state courts, more than 5,000 suits were filed in 2025, and 64% of companies sued had revenue under $25 million [S17]. In the first half of 2026, the top 10 plaintiff firms filed 80.6% of cases [S18]. In the Ninth Circuit, which covers Washington, a website tied to a physical place is covered by Title III [S19]. A Seattle federal court found a website violated both the ADA and the Washington Law Against Discrimination [S20]. Demand letters are not counted and are likely the more common exposure for small organizations.

Target: build to WCAG 2.2 AA. Report against WCAG 2.1 AA where a federal rule asks for it. Every rule in force today uses 2.1 AA as the floor, and Washington state agencies must meet 2.2 AA from July 1, 2026 [S21].

### 3.1 Images and media (MUST)

- Alt text on every informative image, logo, and header image; decorative images marked decorative (WCAG 1.1.1).
- Prerecorded video has accurate, edited captions, not raw auto-captions (1.2.2). Audio-only content has a transcript (1.2.1).
- No media plays automatically with sound.
- Check: automated scan shows zero missing alt text; a person reads each alt text and confirms it says what the image shows; each video has captions checked by a person.

### 3.2 Color and contrast (MUST)

- Normal text at least 4.5:1. Large text (18 point, or 14 point bold) at least 3:1. Buttons, form borders, and icons at least 3:1 (1.4.3, 1.4.11).
- Do not copy Google's help page numbers (it lists stricter AAA levels as if they were minimums) [S22].
- Check: contrast checker on text over every background color and every header image. Low contrast is the most common failure on the web: 83.9% of top home pages fail it [S23].

### 3.3 Keyboard and focus (MUST)

- Every link, button, menu, and form works with the keyboard alone, in a logical order, with a visible focus outline (2.1.1, 2.4.3, 2.4.7). Focus is not hidden under sticky headers (2.4.11, WCAG 2.2).
- Check: unplug the mouse. Tab through home, contact, and every form page. Pass only if every control is reachable and visible.

### 3.4 Structure, links, and language (MUST)

- One H1 per page, headings in order, no skipped levels used for looks (1.3.1, 2.4.6).
- Every page has a unique title (2.4.2) and a page language set (3.1.1).
- No empty links or buttons. No "click here" without context (2.4.4, 4.1.2).
- Check: automated scan shows zero empty links, zero empty buttons, zero skipped headings.

### 3.5 Forms (MUST)

- Every field has a visible label tied to the field. Required fields marked in text, not only by color. Errors described in words (1.3.1, 3.3.1, 3.3.2).
- Do not ask people to re-enter information they already gave in the same process (3.3.7). No puzzle-type tests to log in (3.3.8).
- Check: fill and submit each form by keyboard and with a screen reader; trigger each error and confirm it is announced.

### 3.6 Zoom, mobile, and touch (MUST)

- Usable at 200% zoom and at 320 pixels wide with no sideways scrolling (1.4.4, 1.4.10). Touch targets at least 24 by 24 pixels (2.5.8).
- Check: zoom the browser to 200% and use a phone-width window.

### 3.6a Predictable behavior and time (MUST)

- Nothing changes page, opens a window, or submits a form just because a field gets focus (3.2.1).
- Any time limit can be turned off or extended (2.2.1). Moving or auto-advancing content (carousels, scrolling banners) can be paused (2.2.2).
- Pop-ups and menus close with Escape and do not trap the keyboard (2.1.2).
- Every custom control announces its name, role, and state to a screen reader (4.1.2).
- Check: tab into each field and confirm nothing jumps; pause every carousel; open and close each pop-up by keyboard.

### 3.7 No overlays (MUST)

- Do not install accessibility overlay or widget products as a compliance measure. The FTC ordered accessiBe to pay $1 million in 2025 and barred it from claiming its widget makes a site compliant without evidence [S24]. In the first half of 2026, 24% of website accessibility suits were against sites that already had a widget installed [S18].
- Check: no overlay script appears in the page code or on the page.

### 3.8 Accessibility statement and records (MUST)

- Page title: "Accessibility." Linked from every footer.
- Contents (W3C minimum plus): commitment; standard targeted (WCAG 2.2 AA); date of last review; known limits in plain language (for example, an embedded calendar from another company); how to get any content in another format; an email and a phone number for problems, with a response time [S25]. The W3C has a free generator [S25].
- Records for the Evidence Folder, per site: date; standard; automated results (WAVE plus axe or Lighthouse) saved as exports or screenshots; keyboard-only pass notes; screen reader pass (NVDA or VoiceOver) on home, contact, and every form; contrast check of the theme; caption check per video; list of known limits; a fix log with dates.
- Check: statement page is live; contact route works; the records exist and are dated within the last 12 months.
- Do not write "fully accessible" or "ADA compliant." Write "we aim to meet WCAG 2.2 AA."

### 3.9 Funding and contract triggers (IF Q7 or Q8)

- The DOJ Title II rule (WCAG 2.1 AA) covers state and local governments, including content they provide "through contractual, licensing, or other arrangements." After an April 20, 2026 rule change, the deadline is April 26, 2027 for governments serving 50,000 or more people and April 26, 2028 for smaller ones [S26]. A county-commissioned program site built by a contractor may be in scope. LAWYER.
- Recipients of HHS money must meet WCAG 2.1 AA under the Section 504 rule, now due May 11, 2027 for organizations with 15 or more employees and May 10, 2028 for fewer [S27]. Other federal funding can bring general Section 504 duties.
- Selling a site to a Washington state agency: expect WCAG 2.2 AA, human testing evidence, and a fix plan in the contract [S21].
- Check: the intake answer and the funding source are recorded; the grant or contract's accessibility clause, if any, is saved in the Evidence Folder.

### 3.10 Platform limits (SHOULD, Google Sites and site builders)

- On Google Sites the builder controls alt text, heading styles (Title, Heading, Subheading), link text, theme colors, and captions (added in YouTube before embedding). The builder cannot fully control the page language code, skip links, the keyboard behavior of built-in menus, carousels, and collapsible text, or anything inside an embed [S22]. These platform points come from general knowledge, not a verified source; test each on the live site.
- Rule: test every embedded item separately. Prefer native Google Forms over unknown third-party embeds. List any limit you cannot fix in the accessibility statement.
- Check: each embed has its own test note in the records.

---

## Part 4. Privacy, cookies, and tracking

### 4.1 Privacy policy (MUST)

- Washington has no general consumer privacy law as of November 2026 [S28]. A privacy policy is still required in practice, because any statement about data that turns out to be false is a deceptive practice under the Washington Consumer Protection Act and FTC rules.
- Contents: what is collected (forms, email signups, donations, analytics); why; who it is shared with by name (Google, payment processor, email tool); how long it is kept; how to ask for a copy or deletion; contact; date.
- Check: compare the policy against the real tool list (4.2). Pass only if every tool that receives data is named and nothing named is missing.

### 4.2 No tracking by default (MUST)

- Default build: no ad pixels (Meta, TikTok, LinkedIn), no session-replay tools (Hotjar, Microsoft Clarity, FullStory), no third-party chat or AI note-taker widgets.
- Why: privacy class actions over pixels and chat tools are active. California wiretap claims are now the main theory against sites with California visitors [S29]. Healthcare-sector pixel settlements have run from $1.76 million to $20.5 million [S29]. A case reported this October found that the Meta Pixel did not violate Washington's privacy act on a public hospital site, but left chat and messaging open; this comes from one law-firm summary and the opinion was not read [S30].
- If analytics are needed: Google Analytics 4 with Google Signals and ad features off, disclosed in the privacy policy, or a cookieless analytics tool. Google Sites has no built-in cookie consent banner, so on Google Sites skip analytics or keep it to that minimal setup [S22].
- Check: open the site with the browser's developer tools on the Network tab. List every third-party domain that loads. Pass only if each one is in the privacy policy and none is an ad or replay tool.

### 4.3 Washington My Health My Data Act (MUST if Q9)

- Applies to any legal entity doing business in Washington; nonprofits and small organizations are not excluded [S31]. "Consumer health data" is broad: it includes medications, allergies, disabilities, and inferences drawn from other data. A youth program registration form asking about allergies or medications is collecting it. Private lawsuits are allowed through the Consumer Protection Act [S31].
- Requirements:
  1. A separate page titled "Consumer Health Data Privacy Policy" covering: categories collected and why; sources; categories shared; third parties that receive it; how people use their rights [S31].
  2. A link to that page on the homepage (footer link is common) [S31].
  3. Collect only what is needed for the service the person asked for, or get clear, separate consent. Sharing needs its own consent, separate from consent to collect. Consent cannot be buried in general terms [S31].
  4. Selling the data needs a signed authorization. Do not do it.
  5. No geofencing within 2,000 feet of a health care location [S31].
  6. Never send health form pages through analytics or ad tags.
- Check: the policy page exists and is linked from the homepage; health fields go only to the client's own form responses; no third-party tag loads on those pages.
- LAWYER: always, for any client in health, counseling, disability services, or reproductive services.

### 4.4 Terms of use (SHOULD)

- Contents: who runs the site; permitted use of site content; that content is owned by the client or used with permission; no warranties; link to the takedown page; governing law (Washington); date.
- Check: page exists and is linked from the footer.

### 4.5 Children (IF Q10)

- COPPA applies to operators who collect personal information online from children under 13. The amended COPPA rule's compliance date was April 22, 2026, and it requires separate parental consent before sharing children's data with third parties [S32]. FTC jurisdiction generally does not reach true nonprofits; for-profit businesses serving children are covered. LAWYER on coverage.
- Build pattern regardless: the site speaks to parents and guardians; a parent fills in registration; no child accounts, chat, comments, or uploads; no ad tags anywhere.
- Check: no form asks a child to enter their own information; no tags beyond those in 4.2.

---

## Part 5. Email and forms

### 5.1 Washington email law (MUST if Q11)

- Washington's Commercial Electronic Mail Act bans any false or misleading information in the subject line of commercial email to Washington residents, at $500 per message, without proof of harm. The Washington Supreme Court confirmed the broad reading in 2025, and a federal court held in January 2026 that federal law does not override it. Class actions over false-urgency subject lines ("Sale ends tonight" when it does not) are rising [S33].
- Rule: no subject line states a deadline, scarcity, or offer that is not true. Ticket sales, tuition, merchandise, and paid programs count as commercial. Pure donation appeals are arguably outside it, but follow the rule anyway.
- Check: review the template and the first three campaigns. Pass only if every factual claim in each subject line is true.

### 5.2 CAN-SPAM basics (MUST if Q11)

- Commercial email needs: true sender and header information; a non-misleading subject; the client's physical postal address; a working unsubscribe that is honored within 10 business days [S34]. This summary was not checked against the FTC page this session.
- Check: the email tool template has the address and unsubscribe link; a test unsubscribe works.

### 5.3 Forms (MUST)

- Collect only what the program needs. Each form says why the data is collected and links the privacy policy.
- Form responses go to an account the client owns.
- File uploads off unless needed.
- Check: each form field has a stated purpose in the build notes; the form owner is the client account.

---

## Part 6. Nonprofit and fundraising disclosures (IF Q12)

### 6.1 Washington charitable solicitation disclosure (MUST if the client must register)

- Washington requires charities that solicit to register with the Secretary of State unless exempt (a summary dated 2012 exempts groups raising under $50,000 run entirely by volunteers; confirm current figures) [S35].
- Electronic and mass solicitations must carry the statement that the registration is on file with the Secretary of State and the Secretary's contact for financial information. Allowed wording for the registration status: "Currently registered with the Washington state secretary of state as required by law." Never imply the state endorses the group [S36].
- The appeal must fully and fairly disclose who the money is for [S36].
- Check: donate page shows the disclosure; registration status confirmed on the Secretary of State's charity search and saved.

### 6.2 Tax status and fiscal sponsorship wording (MUST)

- State the exact status: "a 501(c)(3) nonprofit organization, EIN on request" or "a fiscally sponsored project of [Sponsor], a 501(c)(3) nonprofit." Do not call a project a 501(c)(3) if it is not one. Fiscal sponsorship wording is common practice, not an official form; LAWYER on the sponsor's required wording.
- Check: the status line matches the IRS Tax Exempt Organization Search or the sponsorship agreement.

### 6.3 Donation receipts (MUST)

- IRS rules: a written acknowledgment for any single gift of $250 or more; a quid pro quo disclosure for payments over $75 that are partly a gift (for example, a ticket with dinner) [S37]. Not checked against the IRS page this session.
- Form 990 and the exemption application must be provided on request, or posted on the web to meet the "widely available" rule [S38].
- Check: the donation tool's receipt template names the organization, the amount, and whether goods or services were given.

### 6.4 Payments (MUST if Q13)

- Use a hosted checkout (Stripe, PayPal, Givebutter, or the like) so card numbers never touch the site. This keeps the client on the lightest PCI self-assessment [S39].
- Check: the payment page address belongs to the processor, not the client site.

---

## Part 7. Security basics (MUST)

- HTTPS on every page.
- Multi-factor authentication on every admin account: registrar, Google Workspace, site builder, email tool, payment processor [S40].
- No shared passwords. Use a password manager with client-owned vault.
- Backups: export the site and form data quarterly; keep one copy outside the platform.
- Remove developer and contractor access at handoff, or reduce it to what the support agreement needs.
- Washington's breach law requires notice to affected residents within 30 days, and to the Attorney General if more than 500 residents are affected [S41]. Not checked against the statute text this session.
- Check: the account inventory shows MFA on for each account; the last backup date is within 3 months.

---

## Part 8. Launch, handoff, and upkeep

### 8.1 Launch gate (MUST)

Run in this order:
1. Rights Log complete, every asset matched (2.1 to 2.3).
2. Content sourcing review (2.4) and AI captions (2.5).
3. Footer links present on every page: Privacy Policy, Accessibility, Terms of Use, Corrections and Takedown Requests, Contact, plus Consumer Health Data Privacy Policy if Q9.
4. Accessibility checks (3.1 to 3.8) with records saved.
5. Tag check (4.2).
6. Form test submissions (5.3) and email test (5.1, 5.2).
7. Donation disclosures (Part 6).
8. Account and MFA inventory (2.8, Part 7).
9. Launch captures saved (2.9).
10. Client signs the launch sheet listing any SHOULD items not done and why.

### 8.2 Handoff package (MUST)

- Account inventory with owner, admins, recovery contacts, renewal dates.
- Rights Log and release files.
- Accessibility records and statement review date.
- Takedown and claim-intake procedure, with who opens what mail.
- A one-page "how to add content to the standard" guide for client staff: new photos go in the Rights Log first; new people get a release; AI use gets a caption.

### 8.3 Upkeep calendar (MUST)

| When | What |
|---|---|
| Each content change | Rights Log row; alt text; caption check |
| Quarterly | Backup; tag check; form test |
| Every 12 months | Accessibility re-test and statement date; policy review; launch captures refreshed |
| Every 3 years | DMCA agent renewal (if 2.7 on) |
| Domain renewal date | Confirm auto-renew and registrant |
| When a law here changes | Update this standard and re-check affected sites |

---

## Part 9. Evidence Folder (one per site, owned by the client)

```
[Client] Website Evidence/
  01 Intake answers
  02 Rights Log (sheet) and licenses
  03 Releases and permissions
  04 Sources and citations
  05 AI use log
  06 Accessibility records (scans, manual tests, fix log, statement versions)
  07 Privacy, terms, health data policy versions (dated)
  08 Tag and tracker checks
  09 Email and form tests
  10 Fundraising disclosures and registration proof
  11 Account inventory and MFA proof
  12 Launch and change captures
  13 Claims, takedowns, and correspondence log
  14 Signed launch sheet and handoff
```

---

## Risk register (summary)

| Risk | Likelihood | Impact | Level | Main control |
|---|---|---|---|---|
| Image or photo demand letter, CCB claim | High | Medium | High | 2.1, 2.2, 2.6 |
| ADA website demand letter or suit | Medium (higher with a physical location) | High | High | Part 3 |
| Personality rights claim over a person's image in fundraising | Medium | Medium | Medium | 2.3 |
| Defamation or false light claim over history or claims about people | Low | High | Medium | 2.4 |
| Accusation of passing AI content off as real | Medium | Medium | Medium | 2.5 |
| Privacy suit over pixels or chat widgets | Low for small nonprofits | High | Medium | 4.2 |
| Health data law claim | Low, High if health fields used | High | High when Q9 | 4.3 |
| Email subject-line class action | Medium if commercial email | Medium | Medium | 5.1 |
| Loss of domain or accounts to a former developer | Medium | High | High | 2.8 |
| Account takeover | Medium | High | High | Part 7 |

Likelihood levels are judgment calls drawn from the trends cited, not measured rates for nonprofits. No source tracked nonprofits as a separate group of defendants.

---

## Items marked LAWYER

- 2.2 Music and recordings the client did not make.
- 2.3 Reliance on the historical or educational exemption for a person's image.
- 2.4 Any negative claim about a living person or a business.
- 2.6 Any demand letter, CCB claim, or settlement.
- 2.7 Right of publicity claims from user posts.
- 3.9 Whether a government-funded or commissioned site falls under Title II or Section 504.
- 4.3 Every health-adjacent client.
- 4.5 Whether COPPA applies.
- 6.2 Fiscal sponsor wording.

---

## What could not be verified (November 11, 2026)

- The share of CCB claims that are photographs alone, CCB filing fees, and average awards.
- DMCA agent details came from a secondary source.
- Whether any Washington appellate court has applied the Washington Law Against Discrimination to a website, and the accessibility clauses in specific county or arts-funder grant agreements.
- Google Sites heading output, page-language setting, cookie behavior, and AI site builder features.
- The October 2026 Washington pixel ruling (one law-firm summary; opinion not read).
- IRS acknowledgment thresholds, CAN-SPAM details, PCI self-assessment level, breach-law timing, and other states' privacy-law thresholds were written from established knowledge and not re-fetched.
- Current Washington charitable solicitation exemption figures.
- No source named a small nonprofit as a defendant in pixel, wiretap, or video-privacy suits. That is a gap in sources, not proof none exist.

---

## Sources

- [S1] Heitner Legal, "The PicRights Playbook" (Apr 2026): https://heitnerlegal.com/2026/04/01/the-picrights-playbook-how-to-handle-a-2026-copyright-demand-letter/
- [S2] Copyright Claims Board, Statistics and FAQs (Sept 2026): https://www.ccb.gov/CCB-Statistics-and-FAQs.pdf
- [S3] IPWatchdog on the Copyright Office CCB report (Feb 2026): https://ipwatchdog.com/2026/02/16/copyright-office-report-copyright-claims-board-success-statutory-changes-needed-efficiency/
- [S4] CCB, respondent opt-out: https://ccb.gov/respondent/opt-out/ and CCB Handbook, Damages: https://www.ccb.gov/handbook/Damages.pdf
- [S5] DMCA designated agent guide (secondary): https://beancount.io/blog/2026/09/11/dmca-designated-agent-safe-harbor-takedown-repeat-infringer-guide
- [S6] RCW 63.60, Washington Personality Rights Act: https://lawfilesext.leg.wa.gov/Law/RCWPDF/RCW%20%2063%20%20TITLE/RCW%20%2063%20.%2060%20%20CHAPTER/RCW%20%2063%20.%2060%20%20COMBINEDCHAPTER.pdf
- [S7] Congressional Research Service on the Music Modernization Act schedule: https://www.everycrsreport.com/reports/LSB10181.html and UCSB Discography of American Historical Recordings, Public Domain Day 2026: https://adp.library.ucsb.edu/index.php/resources/detail/516
- [S8] Davis Wright Tremaine on SB 5886 (June 2026): https://dwt.com/insights/2026/06/washington-state-right-of-publicity-ai-replicas
- [S9] Eastwood v. Cascade Broadcasting (Wash. 1986): https://law.justia.com/cases/washington/supreme-court/1986/52387-8-1.html
- [S10] RCW 4.105, Uniform Public Expression Protection Act: https://lawfilesext.leg.wa.gov/Law/RCWPDF/RCW%20%20%204%20%20TITLE/RCW%20%20%204%20.105%20%20CHAPTER/RCW%20%20%204%20.105%20%20COMBINEDCHAPTER.pdf
- [S11] Holland and Knight, Operation AI Comply (Aug 2026): https://www.hklaw.com/en/insights/publications/2026/08/operation-ai-comply-2-years-later-continued-enforcement and Morgan Lewis on California AI disclosure rules (Aug 2026): https://www.morganlewis.com/pubs/2026/08/new-california-ai-disclosure-rules-become-operative
- [S12] RCW 42.62, synthetic media in campaigns: https://lawfilesext.leg.wa.gov/Law/RCWPDF/RCW%20%2042%20%20TITLE/RCW%20%2042%20.%2062%20%20CHAPTER/RCW%20%2042%20.%2062%20%20COMBINEDCHAPTER.pdf
- [S13] Hunton on Washington's AI companion chatbot law: https://hunton.com/privacy-and-cybersecurity-law-blog/washington-state-enacts-law-regulating-ai-companion-chatbots-with-private-right-of-action
- [S14] U.S. Copyright Office, Part 2 report on copyrightability (Jan 2025): https://copyright.gov/newsnet/2025/1060.html and Holland and Knight on the Thaler v. Perlmutter cert denial (Mar 2026): https://www.hklaw.com/en/insights/publications/2026/03/the-final-word-supreme-court-refuses-to-hear-case-on-ai-authorship
- [S15] ICANN, lost domain names: https://icann.org/resources/pages/lost-domain-names
- [S16] Seyfarth ADA Title III blog (Mar 2026): https://www.adatitleiii.com/2026/03/federal-court-website-accessibility-lawsuit-filings-bounce-back-in-2025/
- [S17] UsableNet, 2026 trends: https://blog.usablenet.com/ada-web-lawsuit-trends-2026
- [S18] EcomBack, 2026 mid-year report: https://www.ecomback.com/ada-website-lawsuits-recap-report/2026-mid-year-ada-website-lawsuit-report
- [S19] Venable on Robles v. Domino's (9th Cir. 2019): https://www.venable.com/insights/publications/2019/03/ninth-circuit-ruling-bolsters-ada-website
- [S20] Long v. Live Nation (W.D. Wash. 2018): https://law.justia.com/cases/federal/district-courts/washington/wawdce/2:2016cv01961/240504/50
- [S21] WaTech USER-01-01-S Digital Accessibility Standard: https://watech.wa.gov/sites/default/files/2025-01/USER-01-01-S%20Digital%20Accessibility%20Standard.pdf
- [S22] Google Sites Help, accessibility: https://support.google.com/sites/answer/7529116
- [S23] WebAIM Million: https://webaim.org/projects/million/
- [S24] FTC, final order requiring accessiBe to pay $1 million (Apr 2025): https://ftc.gov/news-events/news/press-releases/2025/04/ftc-approves-final-order-requiring-accessibe-pay-1-million
- [S25] W3C WAI, accessibility statements and generator: https://w3.org/WAI/planning/statements
- [S26] Federal Register, Title II compliance date extension (Apr 20, 2026): https://www.federalregister.gov/documents/2026/04/20/2026-07663/extension-of-compliance-dates-for-nondiscrimination-on-the-basis-of-disability-accessibility-of-web
- [S27] Deque on the HHS Section 504 deadline extension: https://www.deque.com/blog/hhs-section-504-deadline-extended-what-did-and-didnt-change-and-what-your-organization-needs-to-do/
- [S28] GeekWire on Washington's privacy bill (2026): https://www.geekwire.com/2026/washington-state-pioneered-a-privacy-model-for-the-nation-when-will-it-finally-pass-the-law-at-home/
- [S29] ConsentPixel, CIPA case watch (Oct 2026): https://consentpixel.com/blogs/cipa-case-watch-october-2026/
- [S30] Miller Nash on Washington and California pixel rulings: https://www.millernash.com/industry-news/washington-and-california-shut-down-meta-pixel-privacy-act-claims-but-dangers-remain
- [S31] RCW 19.373, My Health My Data Act: https://app.leg.wa.gov/RCW/default.aspx?cite=19.373&full=true
- [S32] Hunton on the COPPA rule compliance deadline: https://www.hunton.com/privacy-and-cybersecurity-law-blog/coppa-rule-amendment-compliance-deadline-approaches
- [S33] Faegre Drinker on Washington's email law (Jan 2026): https://www.faegredrinker.com/zh/insights/publications/2026/1/federal-court-upholds-washington-state-commercial-electronic-mail-act-against-can-spam-preemption-argument
- [S34] FTC CAN-SPAM compliance guide: https://www.ftc.gov/business-guidance/resources/can-spam-act-compliance-guide-business
- [S35] Washington Secretary of State, Charitable Solicitations Act summary: https://www.sos.wa.gov/_assets/charities/summary-of-washington-state-charitable-solicitations-act.pdf
- [S36] RCW 19.09.100: https://app.leg.wa.gov/RCW/default.aspx?cite=19.09.100
- [S37] IRS Publication 1771: https://www.irs.gov/pub/irs-pdf/p1771.pdf
- [S38] IRS, public disclosure of exempt organization returns: https://www.irs.gov/charities-non-profits/public-disclosure-and-availability-of-exempt-organizations-returns-and-applications-documents-subject-to-public-disclosure
- [S39] PCI Security Standards Council document library: https://www.pcisecuritystandards.org/document_library/
- [S40] CISA Cyber Essentials: https://www.cisa.gov/cyber-essentials and NIST small business cybersecurity: https://www.nist.gov/itl/smallbusinesscyber
- [S41] RCW 19.255.010: https://app.leg.wa.gov/RCW/default.aspx?cite=19.255.010
