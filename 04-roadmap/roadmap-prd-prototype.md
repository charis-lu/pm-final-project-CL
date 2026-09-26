# Roadmap, PRD & Prototype (Module 4)

## Your strategic anchors
- **Persona (M2), who are you solving for?:** Priya (UXR-01), the plateauing loyalist. A 14-year heavy viewer whose long tenure makes her the retention base the hook is most worried about protecting.
- **Primary success metric (M3), your leading indicator:** Search-to-play conversion rate (the percentage of content searches that result in a play start) because t directly measures whether Spotlight is closing the discovery gap of turning “I’m looking for something to watch” into “I found something and started watching.” The current baseline is 34%, down from 41% six months ago, so will need to increase the share of discovery attempts that convert into viewing, rather than prolonged browsing with no play.
- **Moment of misery (M2), the specific friction blocking the goal:** She scrolls for roughly twenty minutes, watches nothing, and closes the app — the exact "engagement plateau" the hook names, since the session itself looks active while producing zero viewing. Her stated resolution was to go back to a DVD, meaning the 15,000-title library actively lost to physical media she already owned.
- **Guardrail metric (M3), what must not drop or break:** 30+ minute session rate (the percentage of sessions reaching at least 30 minutes) because Spotlight should improve discovery without reducing meaningful engagement among StreamLine’s existing viewers. The current baseline is 11%, down from 19% six months ago, so the 30+ minute session rate must not decline further as Spotlight adoption grows.

## Scan the backlog & set a human baseline
- **My instinctive “quick wins” before touching the AI (2 to 3 feature IDs + why):** A1-Spotlight Curated Rail - This provides a focused homepage surface and reduces the choice overload

A2-"Why You’ll Love This” Label - This cut decision paralysis and supports the decision rather than having a whole new search page

## Audit, override & decide
- **Where did you override the AI? (feature + old vs. new score + why):** A2 · 'Why You'll Love This' Label - Old score was value 3, effort 4, time sinker. New score is value 4, effort 2, quick win because this directly attacks decision paralysis by giving Priya a reason to choose, but AI matching/reason generation adds meaningful engineering complexity.

A5	Personalized Spotlight Queue - Old score was value 2, effort 5, time sinkers. New Score value 4, effort 5, Major project because this could strongly personalize discovery, but building reliable taste-based recommendations is too large a bet for a 3-week sprint.
- **Did the AI over-value a Sales/Eng request your M2 interviews don’t support?:** No - AI values them as a 1 and time sinkers.
- **Did it underweight something your M3 cohort/funnel data strongly supports?:** Yes - AI underweighted the quantitative evidence around retention and segment impact. Wanderers are 41% of the user base, the largest segment but AI was prioritizing Priya's qualitative pain as the entire target.

## Generate your interactive roadmap
- **My “Now” lane (this sprint), the 2 to 3 quick wins I’ll build first:** A1 Spotlight Curated Rail and A2 “Why You’ll Love This” Label
- **What I cut, and the “no” I’m protecting the scope from:** A7 Curator Profiles, A8 Watch Party (Spotlight), A9	Advanced Filter Engine, and A10 Offline Download
- **Prototype/roadmap screenshot link (paste into your deliverables):** https://claude.ai/artifact/4fwMCiVXEdnCu82QMtVNVU
