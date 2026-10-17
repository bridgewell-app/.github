<div align="center">

<img src="assets/logo.png" alt="Bridgewell logo" width="100%">

# 🧬 Bridgewell

**Matches you can trust.**

A map of rare disease collaboration that finds the communities sharing your biology and shows the proof behind every link.

[![Live App](https://img.shields.io/badge/Live_App-bridgewell.faizath.com-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white)](https://bridgewell.faizath.com)
[![API](https://img.shields.io/badge/API-bridgewell--api.faizath.com-0366d6?style=for-the-badge&logo=fastapi&logoColor=white)](https://bridgewell-api.faizath.com/docs)
[![Demo](https://img.shields.io/badge/Demo-Google_Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/162n-b2BUXvLOmyCJf8jYGj6b-bZ8Mwdb/preview)

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Cytoscape.js](https://img.shields.io/badge/Cytoscape.js-map-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-API-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-Extract%20%7C%20Explain-412991?style=for-the-badge&logo=openai&logoColor=white)

</div>

---

## 🎬 Demo

<div align="center">
  <a href="https://drive.google.com/file/d/162n-b2BUXvLOmyCJf8jYGj6b-bZ8Mwdb/preview">
    <img src="assets/bridgewell.webp" alt="Bridgewell demo" width="100%">
  </a>
  <br>
  <sub>▶ Click to watch the full demo on Google Drive</sub>
</div>

---

## 🔍 What is Bridgewell?

Bridgewell is a map of rare disease collaboration for patient organisation leaders, clinicians and
researchers. Maria leads a group for SCN2A DEE11, a rare epilepsy with no approved treatment. She
types her gene into one search box and gets three answers, each with sources: which communities share
the same broken biology, which look-alikes are *not* matches, and what existing registries, studies
and animal models she could reuse instead of building from zero.

Underneath, 17,104 diseases, genes, studies, groups and papers sit in one graph with 31,525 cited
links. Matches are scored by shared mechanism, pathway and rarity-weighted symptoms, never by disease
name. Every link is labelled curated, extracted (with the verbatim quote) or inferred, and clicking it
on the map opens its proof. Routes to a partner, a cited collaboration brief and a time-saved estimate
come out the other end, and every generated sentence cites the links behind it.

### 🎯 Built for

Bridgewell was built for **[Hack-Nation's 7th Global AI Hackathon](https://luma.com/z3za7zow)**, under the *Challenge 5: Buffalo Initiative x OpenAI: AI Atlas for the World's Rare Diseases* track.

---

## ❓ Problem → 💡 Solution

| ❓ Problem | 💡 How Bridgewell solves it |
|---|---|
| **Communities cannot find each other** — two diseases with different names can share the same broken biology and could share a study, but nothing connects them. | **Mechanism beats gene name** — neighbours are scored on shared mechanism and its direction, so SCN8A DEE13 is SCN2A DEE11's top match at 63% through the same sodium channel gain of function. |
| **Searching by name misleads** — the same gene can cause diseases that need opposite treatments, and a name search puts them side by side. | **Counterexamples are a feature** — look-alikes with opposite biology get red "Not a match" cards with PubMed sources and can never share a cluster or a route. |
| **Claims come without proof** — a suggested partner without a source cannot convince a board, a clinician or a funder. | **Nothing without a source** — every link is curated, extracted with its quote, or marked inferred; generated sentences cite their links, and a citation that does not resolve is removed. |
| **Time is the scarcest resource** — a natural history study built from scratch takes years. | **Reuse verdicts and a timeline** — each registry, study or model gets a reuse verdict, and the brief compares 31 months from zero with 11 by joining a partner. |
| **"Nothing found" usually means silence** — a tool that cannot connect two diseases either guesses or says nothing. | **Honest dead ends** — with no supported route, Bridgewell says so and shows what was searched, what is missing and what to test next. |

---

## 📸 Screenshots

<table>
<tr>
<td width="33%" align="center"><b>The atlas</b><br><br><img src="assets/screenshots/1.webp" alt="The atlas of 25 biology groups, with the cursor hovering the Neuronal excitability group and its tooltip showing" width="100%"></td>
<td width="33%" align="center"><b>One gene, several diseases</b><br><br><img src="assets/screenshots/2.webp" alt="Search results for SCN2A listing the diseases it causes, with SCN2A developmental and epileptic encephalopathy about to be picked" width="100%"></td>
<td width="33%" align="center"><b>Matches by mechanism</b><br><br><img src="assets/screenshots/3.webp" alt="Five matches for SCN2A DEE11 led by SCN8A DEE13 at 63%, with that disease's node hovered on the map" width="100%"></td>
</tr>
<tr>
<td width="33%" align="center"><b>Not a match</b><br><br><img src="assets/screenshots/4.webp" alt="Four look-alikes listed in red as same gene or same system with the opposite problem, one of them hovered on the map" width="100%"></td>
<td width="33%" align="center"><b>Clicked on the map</b><br><br><img src="assets/screenshots/5.webp" alt="SCN8A DEE13 selected on the map with its shared-mechanism links drawn in blue and its card open on the left" width="100%"></td>
<td width="33%" align="center"><b>The route</b><br><br><img src="assets/screenshots/6.webp" alt="A five-step route from SCN2A DEE11 to the International SCN8A Alliance drawn on the map, with one link hovered" width="100%"></td>
</tr>
<tr>
<td width="33%" align="center"><b>The proof</b><br><br><img src="assets/screenshots/7.webp" alt="The proof drawer for one route link: the PubMed quote, its age, its verification status and how sure the atlas is" width="100%"></td>
<td width="33%" align="center"><b>The brief</b><br><br><img src="assets/screenshots/8.webp" alt="A collaboration brief for SCN2A DEE11 and the International SCN8A Alliance, cited sentence by sentence" width="100%"></td>
<td width="33%" align="center"><b>Time saved</b><br><br><img src="assets/screenshots/9.webp" alt="Time saved card: 31 months from zero, 11 by joining the partner and 4 on a shared platform" width="100%"></td>
</tr>
</table>

---

## 📦 Repositories

| Repository | Description | Tech Stack | Deployment |
|---|---|---|---|
| [**bridgewell-web**](https://github.com/bridgewell-app/bridgewell-web) | The map-first frontend: one full-screen graph, floating cards for matches, look-alikes, reuse, the brief and time saved, and a proof drawer. | TypeScript · React · Vite · Tailwind CSS · Cytoscape.js | [bridgewell.faizath.com](https://bridgewell.faizath.com) |
| [**bridgewell-api**](https://github.com/bridgewell-app/bridgewell-api) | The evidence graph and reasoning API: match scoring, counterexamples, evidence routes, reuse verdicts, cited briefs and timelines. | Python · FastAPI · Pydantic · NetworkX · OpenAI SDK | [bridgewell-api.faizath.com](https://bridgewell-api.faizath.com/docs) |
| [**bridgewell-data**](https://github.com/bridgewell-app/bridgewell-data) | The collected and curated dataset, where every reviewed row quotes its source, plus the scripts that fetch and rebuild it. | Python · Bash · Firecrawl · PubMed · ClinicalTrials.gov | — |
| [**.github**](https://github.com/bridgewell-app/.github) | This organization profile and its assets. | Markdown | — |

---

<div align="center">
<sub>© 2026 Bridgewell Team</sub>
</div>
