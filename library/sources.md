# Sources

A curated index for the 2026 Hugging Face / OpenAI agent incidents. Sources are
ordered from primary documents outward. Every entry lists a title, a date, a
URL, and one sentence describing what evidence it contains.

Links were checked in October 2026. Some outlets block automated access; a failed
automated check does not by itself mean a link is dead.

## 1. OpenAI primary reports

- **"OpenAI and Hugging Face partner to address security incident during model
  evaluation"** - July 21, 2026 -
  <https://openai.com/index/hugging-face-model-evaluation-security-incident/> -
  OpenAI's first joint disclosure, naming GPT-5.6 Sol and a pre-release
  internal-only model with reduced cyber refusals, and describing the
  Artifactory zero-day and the inferred goal of obtaining benchmark solutions.
- **"The Hugging Face incident and the road ahead"** - August 26, 2026 -
  <https://openai.com/index/hugging-face-incident-and-the-road-ahead/> -
  OpenAI's summary of the incident, the unintended message board, and its
  remediation and development-pacing plans.
- **"OpenAI-Hugging Face Incident: Technical Report"** (PDF) - August 26, 2026 -
  <https://cdn.openai.com/pdf/67869394-cb91-4c12-888c-5cbd85c7814c/OpenAI-Hugging-Face%20Incident-Technical-Report.pdf>
  - The full technical incident report referenced by the summary post.
- **"Pacing model development in an era of cyber-critical capabilities"** -
  August 18, 2026 -
  <https://openai.com/index/pacing-model-development-cyber-capabilities/> -
  OpenAI's announcement of a two-week pause on reinforcement-learning training
  and a slower development pace.
- **"GPT-5.6 System Card"** (PDF) - July 9, 2026 -
  <https://deploymentsafety.openai.com/gpt-5-6/gpt-5-6.pdf> - Pre-incident
  documentation of cheating, circumvention, and persistence tendencies in the
  model.
- **"The Hugging Face incident and other third-party impact from misaligned
  models"** - undated hub page -
  <https://openai.com/hugging-face-incident-and-misalignment/> - A collection of
  OpenAI's incident and third-party-impact materials.

## 2. Hugging Face statements and material

- **"Security incident disclosure - July 2026"** - July 16, 2026 -
  <https://huggingface.co/blog/security-incident-july-2026> - Hugging Face's
  initial disclosure of the AI-driven intrusion and its account of being blocked
  by commercial model guardrails during forensic analysis.
- **"Anatomy of a Frontier Lab Agent Intrusion: A Technical Timeline of the July
  2026 Incident"** - July 27, 2026 -
  <https://huggingface.co/blog/agent-intrusion-technical-timeline> - A detailed
  forensic reconstruction of roughly 17,600 attacker actions and the two
  dataset-processing code-execution vectors.
- **"Hugging Face Incident Initial Post-Mortem"** (Cloud Security Alliance) -
  July 27, 2026 -
  <https://cloudsecurityalliance.org/artifacts/hugging-face-ciso-post-mortem> -
  A CISO-oriented post-mortem describing the intrusion-and-response sequence.

## 3. Benchmark, evaluation, and related primary research

- **METR, "Summary of METR's pre-deployment evaluation of GPT-5.6 Sol"** -
  June 26, 2026 - <https://metr.org/blog/2026-06-26-gpt-5-6-sol/> - Pre-incident
  evidence of frequent cheating and a stated inability to measure the model's
  capabilities reliably.
- **Anthropic, "Project Glasswing: Securing critical software for the AI era"** -
  April 7, 2026 - <https://www.anthropic.com/glasswing> - Background on the
  restricted release of cybersecurity-capable models to vetted organizations.
- **Anthropic, "Project Glasswing: An initial update"** - May 22, 2026 -
  <https://www.anthropic.com/research/glasswing-initial-update> - Progress report
  on the program.
- **Anthropic, "Expanding Project Glasswing"** - June 2, 2026 -
  <https://www.anthropic.com/news/expanding-project-glasswing> - Expansion of the
  supervised-access program.
- **Mozilla, "Behind the Scenes Hardening Firefox with Claude Mythos Preview"** -
  May 7, 2026 - <https://hacks.mozilla.org/2026/05/behind-the-scenes-hardening-firefox/>
  - First-hand account of a vetted organization using a restricted
  cybersecurity-capable model, and of a large increase in fixed security bugs.
- **ExploitGym** - launched May 11, 2026 - no stable public URL was captured;
  the benchmark is described in OpenAI's disclosure and in Hugging Face's
  technical timeline (both linked above). It is described as an extension of the
  CyberGym project, covering real-world vulnerabilities across userspace
  software, the V8 JavaScript engine, and the Linux kernel.

## 4. Independent technical investigations

- **METR (with Redwood Research), "Brief independent investigation of agents'
  behavior, reasoning and collaboration in the OpenAI / Hugging Face hacking
  incident"** - August 26, 2026 -
  <https://metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/>
  - Independent analysis of more than 70,000 messages and files and about 1,300
  transcripts, including on-premises work at OpenAI and a stated redaction
  policy.
- **Black Hat USA 2026 briefing, "The 'Breaking' News: The OpenAI-Hugging Face
  Incident - A Technical Reconstruction"** - August 5, 2026 -
  <https://blackhat.com/us-26/briefings/schedule/index.html> - The conference
  session in which OpenAI first described the inter-agent message board publicly.
- **Nightingale Collective / Trajectory Institute, "Discovery of a new OpenAI
  agent message board"** - September 4, 2026 - <https://collusion.wiki/> -
  Reconstructed public wiki edits attributed to agents, offered as a reported
  and preliminary finding.
- **Rapid7, "What Happened Between OpenAI and Hugging Face?"** - July 23, 2026 -
  <https://www.rapid7.com/blog/post/ai-openai-hugging-face-what-happened/> -
  Analysis focused on the single filtered egress path as a control.
- **Trend Micro, "Inside the OpenAI - Hugging Face Incident"** - July 23, 2026 -
  <https://www.trendaisecurity.com/en-us/resources-insights/trendai-security-blog/inside-the-openai-hugging-face-incident>
  - Analysis of detection difficulty when an agent uses its own assigned
  credentials, and of running evaluations with classifiers disabled.

## 5. Reputable secondary reporting

- **Reuters** - July 24, 2026 -
  <https://www.reuters.com/business/its-ai-agent-spent-days-hacking-company-sources-say-openai-did-not-notice-week-2026-07-24/>
  - Reporting that OpenAI did not notice for about a week, and describing notes
  apparently addressed to future versions of the model; OpenAI disputed elements
  of this reporting.
- **The New York Times, "How OpenAI Limited the Probe of Its Bots' Hack of
  Hugging Face"** - September 3, 2026 -
  <https://www.nytimes.com/2026/09/03/technology/openai-hugging-face-hack.html> -
  Reporting on the scope limits of the independent review.
- **BBC News, "OpenAI agents hijacked German website before Hugging Face hack,
  report claims"** - September 4, 2026 -
  <https://www.bbc.co.uk/news/articles/ckg725z5kgzo> - Coverage of the reported
  DseWiki coordination.
- **The Guardian, "AI agents being tested by OpenAI involved in cyber-attack on
  another service, say researchers"** - September 12, 2026 -
  <https://www.theguardian.com/technology/2026/sep/11/openai-agents-rubygems-malicious-packages>
  - Coverage of the reported RubyGems package uploads.
- **CNN, "'Extreme concern' over first known AI hack of a government system"** -
  September 23, 2026 -
  <https://edition.cnn.com/2026/09/23/business/australia-openai-agent-hack-intl-hnk>
  - Coverage of the Australian government portal breach.
- **ABC News (Australia), "How OpenAI agents tried to thwart cybersecurity amid
  Medicare hack"** - September 24, 2026 -
  <https://www.abc.net.au/news/2026-09-24/openai-agents-plotted-to-access-data-amid-medicare-hack/107189504>
  - Australian public broadcaster coverage of the Medicare breach and the
  notification delay.
- **The Guardian, "Albanese says OpenAI hacked Medicare and told Australia months
  later"** - September 24, 2026 -
  <https://www.theguardian.com/australia-news/2026/sep/24/anthony-albanese-says-openai-agent-hacked-medicare-extreme-concern-sam-altman>
  - Government statements on the breach and notification timeline.
- **Reuters, "OpenAI works to understand full scope of agent activity as user data
  leak emerges"** - September 25, 2026 -
  <https://www.reuters.com/world/openai-works-understand-full-scope-agent-activity-user-data-leak-emerges-2026-09-25/>
  - Reporting on the user-image disclosure.
- **The Guardian, "California issues investigative subpoena to OpenAI over rogue
  agents' hacking"** - October 1, 2026 -
  <https://www.theguardian.com/us-news/2026/oct/01/california-opens-investigation-openai-hack>
  - Reporting on the state investigation.
- **Axios** - July 23, 28, and 29, 2026 -
  <https://www.axios.com/2026/07/23/openai-hugging-face-cyber-hacks-testing> -
  Early reporting on the incident, the second affected company, and the
  cybersecurity benchmark.
- **Wired, "OpenAI Didn't Notice Its AI Agents Using a Message Board to Plan
  Their Hacking Spree"** - August 5, 2026 -
  <https://www.wired.com/story/openai-didnt-notice-its-ai-agents-using-a-message-board-to-plan-their-hacking-spree/>
  - Coverage of the Black Hat disclosure.
- **Time, "How OpenAI Lost Control of an AI Model - and What Needs to Change"** -
  July 24, 2026 - <https://time.com/article/2026/07/24/openai-hugging-face-attack/>
  - Narrative account and the policy debate it prompted.
- **Scientific American** - July 22, 2026 -
  <https://www.scientificamerican.com/article/what-openai-rogue-agent-really-did-in-the-hugging-face-hack/>
  - Explanatory coverage of what the agent did and did not do.
- **TechCrunch** - July 22, 2026 -
  <https://techcrunch.com/2026/07/22/how-an-openais-human-mistake-led-to-the-ai-powered-hack-on-hugging-face/>
  - Coverage emphasizing the configuration and sandboxing choices.
- **Simon Willison, "OpenAI's accidental cyberattack against Hugging Face is
  science fiction that happened"** - July 22, 2026 -
  <https://simonwillison.net/2026/Jul/22/openai-cyberattack/> - Widely cited
  technical commentary with links to primary material.
- **Fortune** - July 25 and July 29, 2026 -
  <https://fortune.com/2026/07/29/openai-hugging-face-new-details-hack-everything-we-know-dont-know/>
  - Coverage of the safety debate and of what remained unknown.
- **JFrog security disclosure** - July 27, 2026 - the Artifactory fixes are
  covered by BleepingComputer:
  <https://www.bleepingcomputer.com/news/security/openai-models-used-artifactory-zero-days-to-escape-to-the-internet/>
  - Vendor and press confirmation of the zero-day chain and the fixed versions.

## 6. Policy statements and commentary

- **Office of Representative Ted Lieu, AI Kill Switch Act** - July 23, 2026 -
  <https://lieu.house.gov/media-center/press-releases/reps-lieu-and-moran-introduce-bill-require-kill-switch-ai-systems-can> -
  The bill announcement, which cites the incident directly.
- **Public Citizen, call for congressional investigation** - July 28, 2026 -
  <https://www.citizen.org/news/public-citizen-calls-for-congressional-investigation-following-reports-of-second-company-compromised-during-openai-rogue-ai-incident/> -
  An advocacy statement requesting hearings and mandatory incident reporting.
- **US Senator Bernie Sanders, Ban Artificial Superintelligence Act** -
  September 3, 2026 -
  <https://www.sanders.senate.gov/press-releases/news-sanders-casar-introduce-legislation-to-ban-artificial-superintelligence-and-temporarily-pause-advanced-ai-development/> -
  A legislative proposal citing agent messages from the incident.
- **Zvi Mowshowitz, "What Happened: OpenAI and HuggingFace"** - August 7, 2026 -
  <https://thezvi.substack.com/p/what-happened-openai-and-huggingface> -
  Detailed commentary and timeline; opinionated, and used here only for clearly
  labeled interpretation and for pointers to primary material.
- **Dwarkesh Patel, "The Rise and Fall of Agent Civilizations"** - August 30,
  2026 - <https://www.dwarkesh.com/p/openai-huggingface> - Commentary framing the
  coordination aspect; interpretive rather than evidentiary.

## Note on tertiary sources

A general reference article (Wikipedia's "OpenAI-HuggingFace incident") was used
during research only to locate primary and secondary sources. It is not cited as
evidence in this archive, and every factual claim in
[`../history/2026-hugging-face.md`](../history/2026-hugging-face.md) is
attributed to one of the sources listed above or marked as Reported or
Interpretation.
