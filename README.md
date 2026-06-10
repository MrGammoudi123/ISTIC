# AcademiQ — ISTIC Rattrapage Dashboard

An interactive web dashboard for ISTIC students to simulate and track **rattrapage (makeup exam)** grades for Semester 1 and Semester 2.

## Live Demo

**[https://mrgammoudi123.github.io/ISTIC/](https://mrgammoudi123.github.io/ISTIC/)**

## Features

- **Semester Selector** — Choose S1 or S2 from the landing page; grades are saved independently per semester
- **Grade Simulator** — Drag sliders or type any decimal value (e.g. `10.66`) to project your average in real time
- **Smart Prediction** — Best / Realistic / Worst case scenarios with pass probability
- **Goal Simulator** — Set a target grade and see the exact average needed across remaining subjects
- **Required Grades Table** — What you need per objective from 9/20 to 14/20
- **Performance Charts** — Radar chart and bar chart (Notes vs Crédits), update in real time
- **Editable Fixed Grades** — Unlock and adjust non-retake subject grades
- **Dark / Light theme** + 4 accent colors (blue, purple, cyan, emerald)
- **Export screenshot** of the full dashboard as a high-resolution PNG

## Subjects Covered

### Semestre 1 — 30 credits · 7 rattrapage subjects

| Subject | Coef | Type |
|---|---|---|
| Atelier de Prog 1 | 3 | Fixed |
| Anglais 1 | 2 | Fixed |
| Tech de Communication | 2 | Fixed |
| Analyse 1 | 3 | Rattrapage |
| Algèbre 1 | 3 | Rattrapage |
| Algo et Structure | 4 | Rattrapage |
| Électricité Électronique | 4 | Rattrapage |
| Propagation et Rayonnement | 2 | Rattrapage |
| Sys d'Exploitation 1 | 4 | Rattrapage |
| Système Logique | 3 | Rattrapage |

### Semestre 2 — 29 credits · 8 rattrapage subjects

| Subject | Coef | Type |
|---|---|---|
| Atelier de Prog 2 | 1 | Fixed |
| Culture Comp. Numérique | 1 | Fixed |
| Anglais 2 | 1 | Fixed |
| Tech de Communication 2 | 1 | Fixed |
| Analyse 2 | 1 | Rattrapage |
| Algèbre 2 | 1 | Rattrapage |
| Init. Traitement du Signal | 1 | Rattrapage |
| Fonction Électronique | 1 | Rattrapage |
| Transmission de Données | 1 | Rattrapage |
| Architecture Ordinateurs | 2 | Rattrapage |
| Algo. Struct. de Données | 2 | Rattrapage |
| Système d'Exploitation 2 | 2 | Rattrapage |

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `T` | Toggle dark / light theme |
| `R` | Reset all grades |
| `E` | Export screenshot |
| `1–4` | Switch accent color |

Shortcuts are disabled when a text input is focused.

## Tech Stack

- Pure HTML / CSS / JavaScript — no build tools, no frameworks, no dependencies to install
- [Chart.js 4.4](https://www.chartjs.org/) — radar and bar chart visualizations
- [html2canvas 1.4](https://html2canvas.hertzen.com/) — screenshot export

## Institution

**ISTIC** — Institut Supérieur des Technologies de l'Information et de la Communication  
Université de Carthage · Tunisie · 2025–26
