# CasePro IQ: Premium Strategy Workbench

**CasePro IQ** is an advanced, AI-driven business strategy and case interview preparation platform for Android, built with Kotlin, Jetpack Compose, and the Gemini API. Designed with a **unified glassmorphic UI architecture**, it features a fully reactive aesthetic where the entire application—dock, screens, cards, and styling—is organically derived from a global animated environment layer.

## 🚀 Key Features

*   **Dynamic Business Case Studies:** Test your strategic thinking through progressively difficult scenarios (Easy, Medium, Difficult) powered dynamically by the Gemini API. Real-time feedback, grading, and actionable insights to refine strategy frameworks automatically.
*   **Strategy Workbench:** A dedicated module for crafting, analyzing, and stress-testing strategy frameworks before entering the simulations.
*   **Analytics Dashboard:** Visual insights tracking your progress across different attempt profiles, giving a detailed breakdown of core competencies over time.
*   **Multi-Stage Simulation Engine:** A complete pipeline featuring progression gates (landing -> prep -> testing -> evaluation -> final summary), state synchronization, and historical tracking mechanisms utilizing Room database persistence.

## 🎨 Unified Glass Environment Architecture

The visual identity of **CasePrep AI** steps away from flat, layered surfaces. It implements a fully continuous **environmental glass design system**:

*   **Continuous Glass Field:** UI components are not floating "on top" of a background; they are embedded like glass lenses *within* a unified light field. The application utilizes a global blur and diffusion engine where everything references the animated "aurora" under-layer.
*   **Wallpaper-Driven Theming:** The environment is generated dynamically based on base themes (e.g., Cosmic Aurora, Dark Forest, Sunset Glow). The `PremiumGlassEnvironmentProvider` dynamically computes:
    *   Base tints and accent highlights from the background light source.
    *   Shadow colors and reflection gradients based on background temperatures.
*   **Immersive Dock & Navigation:** The `PremiumGlassDock` is not an opaque bottom bar. It acts as a condensed light-bending region in the unified environment, providing tactile, responsive feedback on interaction.
*   **Tactile Animations:** Every interaction features custom springs, ripples, and scale states, blending the material physics of high-quality glass with responsive application use. 

## 🛠 Tech Stack & Architecture

*   **Language:** Kotlin
*   **UI Framework:** Jetpack Compose (100% declarative Compose UI)
*   **Architecture:** MVVM (Model-View-ViewModel) + StateFlow for seamless reactive UI updates.
*   **Local Persistence:** Room Database for offline storage of attempt history, answers, and analytics data.
*   **AI Integration:** Server-side Gemini API calls via HTTP abstractions, fetching real-time case studies, feedback loops, and grading mechanisms.
*   **Theming & Visuals:** Deeply custom implementation of `GraphicsLayer`, `drawBehind` Canvas APIs, layered Blur techniques, and Compose Animation APIs.

## 💡 What it's made for 

This app is primarily designed for:
1.  **Consulting Candidates & Executives** attempting to drill cases locally or dynamically via AI-driven mock interviews.
2.  **Modern AI Integration Patterns** demonstrating how a multi-turn, stateful evaluation can be conducted reliably through prompt-engineering pipelines attached to Android ViewModels.

## ⚙️ Getting Started

### Prerequisites
* An Android Device running **Android 8.0 (API 26)** or higher (needed for the system overlay service).


### Installation
Just Dowload the Apk and install as a normal app.
