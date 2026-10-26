# Consent and informational privacy in the Supreme Court of India, 2021 to 2026

**Live page:** https://astitvaaaaaaaaaaa-hub.github.io/consent-privacy-judgments/

## Team

- Astitva Agrawal, Division C
- Anmol Kumar Sinha, Division C
- Sahil Islam, Division D
- Khushi Gurm, Division B

## Topic

We study when the Supreme Court lets a person's consent, or their control over their body and personal information, win against the State, a family member or the public's right to know. The question matters because the Digital Personal Data Protection Act, 2023 makes consent the default basis for processing personal data. We wanted to see what the Court has been saying about consent since *Puttaswamy*.

## How we found the judgments

We searched Indian Kanoon, LiveLaw and Supreme Court Observer for "right to privacy", "informational privacy", "consent", "narco-analysis", "DNA test", "advance directive" and "Article 21", limited to Supreme Court decisions between 1 September 2021 and 31 August 2026. We kept a judgment only if it was reasoned and a privacy or consent argument was central to the result. Every case was then read and coded from the official copy on the Court's website (sci.gov.in or Digital SCR), which is linked in `data.csv`. Secondary sources were used only to find cases. That gave 13 judgments. The "Main provision" column gives pinpoint paragraph references to the official copy.

Beyond the template columns, each judgment carries two labels of our own: a **strand** (informational privacy & surveillance; compelled tests: narco & DNA; bodily autonomy & consent) and whether the **privacy or consent argument prevailed** or yielded to another interest.

## What the data shows

![Privacy and consent outcomes over time, by strand](chart1-over-time.png)

**Over time.** Before the DPDP Act was passed in August 2023, the privacy or consent argument won all four judgments in our set. After it, the record is five wins to four losses. None of the losses is a win for State power. Each came where privacy met another person's right: voters' right to know (electoral bonds), a child victim (POCSO), a spouse proving cruelty, and a son seeking his paternity. What surprised us most was the DNA line, where each case builds on the last. *Aparna Firodia* (2023) treated DNA tests of children as near-barred. *Ivan Rathinam* (January 2025) set two hurdles: insufficient other evidence, and a balance of interests in favour of the test. *R. Rajendran* (November 2025) added proportionality and a nexus to the offence. *Chaturbhuj Pradhan* (2026) then ordered a test once those conditions were met.

![Did the privacy or consent argument win? By strand](chart2-by-strand.png)

**By strand.** Privacy or consent prevailed in 9 of 13 judgments. Compelled tests are the strongest strand (4 of 5). *Amlesh Kumar* (2025) restated *Selvi*: a forced narco test is never permissible. Bodily autonomy follows (3 of 4). *Common Cause* (2023) simplified the living-will procedure, and *Harish Rana* (2026) applied it to a patient who could not consent. Informational privacy is split two and two, because both losses set privacy against another person's right to information or to prove a case.

![Who brought the case, and who won](chart3-who-won.png)

**Who won.** Individuals brought 10 of the 13 cases and won 10. The State's only win, in the POCSO adolescents case, rested on protecting a child, not on any power to intrude. We expected the State to win more often. Instead, in the electoral bonds case the State relied on donor privacy and lost.

## The doctrinal trend

Consent works almost as a trump against direct State coercion: narco tests, location tracking on bail, spyware. Against other people's rights it is weighed under a proportionality test that the Court has been steadily refining. The DPDP Act's "legitimate uses" let the State and others process data without consent. The case law suggests courts will police that strictly where the State reaches into a person's body or phone, and will balance it elsewhere. None of the 13 judgments turns on the DPDP Act, so how courts will apply that law is still untested.

## Limits

Thirteen judgments from one court cannot show a statistical trend. The set is a selection of cases where privacy was central, not every case that mentions it. The strand labels and the "prevailed" coding are our own judgment calls. The Supreme Court mostly hears appeals, so the set says nothing about High Courts or the Data Protection Board.

## AI-use declaration

We used Claude (Anthropic) to help build the web page and charts, draft first versions of the one-line issue and holding summaries, and cross-check the dataset against the official copies. That check caught two judgments we had wrongly coded as narco-analysis cases (*Manoj Kumar Soni*, 2023, and *Vinobhai*, 2025, which concern s 27 Evidence Act disclosure statements), and we replaced them. The team member named under "Coded by" checked each entry, citation, link and paragraph pinpoint against the official judgment. The strand coding and analysis are the team's own.

## Files

- `index.html`: analysis and visualisation page (published with GitHub Pages)
- `data.xlsx`: completed Dataset template
- `data.csv`: the Data sheet as CSV
- `chart1-over-time.png`, `chart2-by-strand.png`, `chart3-who-won.png`: charts used above
