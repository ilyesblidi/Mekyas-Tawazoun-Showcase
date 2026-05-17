<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.16+-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-3.2+-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-iOS%20%7C%20Android-6C5CE7?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" />
</p>

<h1 align="center">
  ⚖️ Mekyas Tawazoun<br/>
  <sub>مقياس التوازن الشخصي</sub>
</h1>

<p align="center">
  <strong>Personal Balance & Self-Development Companion</strong><br/>
  Evaluate your life dimensions, visualize harmony, and take actionable steps toward a more balanced you.
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-architecture">Architecture</a> •
  <a href="#-installation">Installation</a> •
  <a href="#-author">Author</a>
</p>

---

## 📖 Introduction

**Mekyas Tawazoun (مقياس التوازن الشخصي)** is a modern Flutter application designed to help individuals assess and improve their personal balance across multiple life dimensions — from career and health to relationships and spirituality.

Inspired by the Arabic concept of *"Tawazoun"* (balance), the app provides an intuitive diagnostic tool, generates smart recommendations, and helps users create structured action plans to close gaps in underperforming areas. Whether you're feeling overwhelmed or simply striving for continuous improvement, Mekyas Tawazoun turns self-reflection into measurable progress.

---

## ✨ Key Features

| Category | Features |
| :--- | :--- |
| 📊 **Diagnostic** | Multi‑dimensional life assessment with weighted questions |
| 🎯 **Balance Visualization** | Radar chart, progress bars, and numeric balance score |
| 💡 **Recommendations** | Personalized suggestions based on weak dimensions |
| 📝 **Action Plans** | Create, track, and complete tasks with due dates |
| 📈 **Analytics** | Historical score tracking and dimension trends over time |
| 👤 **Profile** | User management, avatars, and preference settings |
| 🔐 **Authentication** | Secure onboarding and local/cloud data sync |
| 🌗 **Theme Support** | Light & dark mode with RTL/LTR flexibility |

---

## 📱 Screenshots

<p align="center">
  <strong>User Journey — From Assessment to Action</strong>
</p>

| Home Dashboard | Diagnostic Page | Results Visualization |
| :---: | :---: | :---: |
| <img src="screenshots/home_page.png" width="240" alt="Home Page"/> | <img src="screenshots/diagnostic_page.png" width="240" alt="Diagnostic Page"/> | <img src="screenshots/results_page.png" width="240" alt="Results Page"/> |
| *Overview of balance score and quick actions* | *Multi‑dimensional questionnaire* | *Radar chart + numeric breakdown* |

| Recommendations | Action Plan | Profile |
| :---: | :---: | :---: |
| <img src="screenshots/recommendations_page.png" width="240" alt="Recommendations"/> | <img src="screenshots/action_plan_page.png" width="240" alt="Action Plan"/> | <img src="screenshots/profile_page.png" width="240" alt="Profile Page"/> |
| *AI‑inspired personalized tips* | *Task list with progress tracking* | *User settings & history* |

| Statistics & Trends | Onboarding | Dark Mode Preview |
| :---: | :---: | :---: |
| <img src="screenshots/statistics_page.png" width="240" alt="Statistics"/> | <img src="screenshots/onboarding_page.png" width="240" alt="Onboarding"/> | <img src="screenshots/dark_mode.png" width="240" alt="Dark Mode"/> |
| *Weekly/monthly balance evolution* | *Smooth first‑time experience* | *Consistent visual experience* |

> 💡 *All screens are fully responsive and support both Arabic & English interfaces.*

---

## 🧭 App Workflow / User Journey

```mermaid
graph LR
    A[Onboarding/Login] --> B[Diagnostic Test]
    B --> C[Balance Results + Radar Chart]
    C --> D[Smart Recommendations]
    D --> E[Create Action Plan]
    E --> F[Track Tasks & Progress]
    F --> G[Re‑evaluate & Improve]
    G --> B
