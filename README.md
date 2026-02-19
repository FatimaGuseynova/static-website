# Passport - Multi-Page Travel Agency Portal

A robust, multi-page frontend implementation for a travel and tourism service. This project demonstrates advanced CSS layout techniques, cross-page navigation logic, and a structured approach to styling scalable web interfaces.

## ⚙️ Technical Specifications

* **Architecture:** Multi-page application (MPA) structure consisting of Home, About, and Services modules.
* **Layout Engine:** Heavy reliance on CSS Flexbox for complex alignment within the navigation systems and service grids.
* **Typography:** Global implementation of the **Work Sans** typeface family with fallbacks to system sans-serif stacks.
* **Iconography:** Integration of **Font Awesome 7.0.1** for scalable vector interface elements and social branding.
* **Component Patterns:** Shared UI components including a global transparent-to-solid navigation bar, hero sections with linear-gradient overlays, and a multi-column footer.

## 📂 Project Structure

```text
├── css/
│   ├── reset.css       # Meyer-based normalization to eliminate browser-specific inconsistencies
│   └── style.css       # Centralized design system including global variables and page-specific logic
├── img/                # Optimized photographic assets and branding identity
├── index.html          # Primary landing module
├── about.html          # Corporate information and team module
└── services.html       # Service catalog and feature grid module
```

## Implementation Details
CSS Methodology
Layering: Backgrounds utilize linear-gradient overlays on hero_1.jpg to ensure high contrast for foreground typography.

Navigation Logic: Implementation of a CSS-only dropdown system with transition effects and precise positioning.

Standardization: Strict container width of 1300px enforced across all modules to maintain visual alignment.

Interactivity: Unified transition speed (0.4s) applied to all pseudo-classes (:hover, :active) for consistent tactile feedback.

Key Content Blocks
Service Grid: A repeatable card system (.cardi) designed for modular expansion of features.

Hero Section: Full-viewport (100vh) introductory blocks with centralized content positioning.

Social Integration: Standardized social icon set in the footer with circular background-clip and hover color shifts.

## Execution & Deployment
Repository Setup:

## Bash
```git clone https://github.com/FatimaGueynova/static-website.git```
Environment: No compilation or build steps required. The project is designed for static serving.

Observation: Open index.html via a local environment to verify relative pathing between the About and Services modules.

Technical frontend implementation developed as part of a professional portfolio.
