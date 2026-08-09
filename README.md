# BinGo! - AI-Powered Recycling Made Simple

BinGo! is a modern, responsive landing page for an innovative mobile application dedicated to turning everyday recycling into an engaging, rewarding experience. Built with pure HTML5 and CSS3, the page features a clean, responsive layout designed to encourage users to download the app, explore features, and get involved in eco-friendly community guilds.

---

## 🚀 Features Highlighted

The landing page effectively showcases the app's primary value propositions:
*   **Smart Scan:** Powered by AI to instantly identify and log recyclables with a quick photo snapshot.
*   **The Treasure Map:** Directs users to the nearest eco-friendly drop-off points and reverse vending machines.
*   **Uber for Recycling:** An on-demand collection service that lets users summon a pickup right to their doorstep.
*   **Rubbish to Riches:** A gamified experience tracking plastic reduction while unlocking rewards at partner super-shops.
*   **Green Guilds:** A collaborative social feature allowing groups to pool points to plant trees in local parks.

---

## 🛠️ Project Structure

Your repository consists of the following structure:
*   `index.html` — The core entry point containing all semantic markup and embedded responsive styling.
*   `hero.png` — Visual graphic showcasing the primary app interface mockup.
*   `features.png` — Visual asset illustrating specific in-app capabilities.
*   `snap.png`, `choose.png`, `secure.png`, `claim.png` — Process icons depicting the 4-step user workflow.
*   `sdg9.png`, `sdg11.png`, `sdg12.png`, `sdg14.png` — SDG alignment identifiers showing commitment to global sustainability targets.

---

## 💻 Tech Stack & Customizations

*   **Markup:** Semantic HTML5 (`<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
*   **Styling:** Modern CSS3 utilizing custom properties (CSS variables) for consistent color branding, `clamp()` typography for fluid scaling, CSS Grid, and Flexbox for responsive component layouts.
*   **Accessibility (a11y):** Form fields mapped with explicit labels, hidden helper utilities (`.sr-only`), and `aria-label` elements detailing visual content and download triggers.
*   **Typography:** Dynamically embedded Google Fonts ("Inter").

---

## 🎨 How to Edit & Customize

### 1. Modifying the Theme / Colors
The site relies heavily on CSS variables declared in the `:root` pseudo-class. Open `index.html` and look for the following block to seamlessly adjust the color palette or curves:
```css
:root {
  --bg: #f5fbf6;
  --text: #12311f;
  --green-dark: #0f4a2d;
  --green-bright: #2fb86d;
  /* Adjust border-radius and shadows globally here */
}
