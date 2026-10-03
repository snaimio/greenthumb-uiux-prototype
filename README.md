# 🌱 GreenThumb — UI/UX Design System & Interactive Prototype

[![Figma](https://img.shields.io/badge/Figma-Design%20Files-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com)
[![Platform](https://img.shields.io/badge/Platform-Web%20%26%20Mobile%20(iOS%2FAndroid)-2ea44f?style=for-the-badge)](./design)
[![UI/UX](https://img.shields.io/badge/Design%20Phase-Wireframes%20%E2%86%92%20Hi--Fi%20Prototype-blue?style=for-the-badge)](./screenshots)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

**GreenThumb** is a comprehensive, human-centered digital gardening platform and companion application engineered to empower urban gardeners, houseplant enthusiasts, and community growers. From intelligent plant diagnosis and real-time care schedules to neighborhood plot reservations and nursery marketplaces, GreenThumb connects botanical knowledge with intuitive interface design.

---

## 🎨 Design System & Component Architecture

The visual architecture is anchored in organic, earthy tones balanced with crisp typography and modern accessibility standards (WCAG AAA).

![GreenThumb Design System Tokens](screenshots/design_system_tokens.jpg)

### Color Palette & Design Tokens
* **Primary Brand:** Deep Emerald (`#144D37`), Forest Leaf (`#2C8B59`), Sage Mint (`#85C19C`)
* **Warm Accents:** Terracotta (`#E76F51`), Golden Sand (`#F4A261`), Neutral Slate (`#264653`)
* **Typography Hierarchy:** Poppins / Inter scale ranging from Display H1 (`32px/Bold`) down to Caption (`12px/Regular`).
* **Micro-Components:** Rounded status chips (`Optimal 96%`, `Water Soon`, `Needs Light`), moisture telemetry rings, and interactive bottom navigation.

---

## 📱 Mobile App Experience & Screen Flows

A native iOS/Android experience crafted with ergonomic thumb-zone navigation, clean card hierarchies, and augmented reality interactions.

| 1. Onboarding & Welcome | 2. Home Dashboard & Health | 3. Plant Profile & Care Guide |
| :---: | :---: | :---: |
| <img src="screenshots/mobile_onboarding.jpg" width="280" alt="Onboarding Screen"/> | <img src="screenshots/mobile_dashboard.jpg" width="280" alt="Home Dashboard"/> | <img src="screenshots/mobile_plant_detail.jpg" width="280" alt="Plant Detail"/> |
| *Personalized onboarding & botanical introduction.* | *Live garden health index, weather sync & daily task feed.* | *Real-time moisture gauge, sunlight tracker & care log.* |

<br/>

| 4. AR / AI Plant Identification | 5. Community Gardens & Feed | 6. Plant Care Tracker Banner |
| :---: | :---: | :---: |
| <img src="screenshots/mobile_ar_scanner.jpg" width="280" alt="AR Plant Scanner"/> | <img src="screenshots/mobile_community.jpg" width="280" alt="Community Gardens"/> | <img src="screenshots/plant-care-banner.png" width="280" alt="Plant Care Banner"/> |
| *Camera viewfinder with instant 98% species recognition.* | *Local urban plot waitlists, harvest posts & discussions.* | *Modular telemetry card for hydration & nutrients.* |

---

## 💻 Web Platform & Responsive Desktop Portal

A data-rich responsive desktop dashboard connecting users to neighborhood gardening networks, marketplace supplies, and masterclass schedules.

### Desktop Hub & Operational Dashboard
![Web Desktop Dashboard](screenshots/web_desktop_dashboard.jpg)

### Web Modules Breakdown

| Interface Module | High-Resolution Capture | UX Capabilities & Features |
| :--- | :---: | :--- |
| **Landing & Discovery Portal** | <img src="screenshots/web-landing-hero.png" width="450" alt="Landing Hero"/> | Hero showcase with smart search, seasonal care tips, and curated botanical collections. |
| **Plant Care Encyclopedia** | <img src="screenshots/web-plant-care-guide.png" width="450" alt="Plant Care Guide"/> | Comprehensive directory filterable by sunlight, indoor/outdoor suitability, and soil type. |
| **Community Gardens Network** | <img src="screenshots/web-community-gardens.png" width="450" alt="Community Gardens"/> | Neighborhood garden map, plot reservation management, and volunteer coordination. |
| **Marketplace & Local Nurseries** | <img src="screenshots/web-marketplace-plants.png" width="450" alt="Marketplace"/> | Direct-to-grower plant shop, organic fertilizers, seed kits, and verified seller ratings. |
| **Events & Workshop Calendar** | <img src="screenshots/web-events-calendar.png" width="450" alt="Events Calendar"/> | Community planting workshops, pruning masterclasses, and RSVP schedules. |

---

## 🔄 Project Evolution & Deliverables

```
┌─────────────────────────────────┐      ┌─────────────────────────────────┐      ┌─────────────────────────────────┐
│   Phase 1: Low-Fi Wireframes    │ ───► │  Phase 2: Hi-Fi Web Prototype   │ ───► │ Phase 3: Mobile Native System   │
│   (SheikhNaim_Assignment2)      │      │  (Prototype_Assignment3)        │      │ (AppPrototype_Assignment4)      │
└─────────────────────────────────┘      └─────────────────────────────────┘      └─────────────────────────────────┘
```

| Milestone | Deliverable File | Focus Areas | Visual Board |
| :--- | :--- | :--- | :---: |
| **Phase 1: Wireframes & Architecture** | [`SheikhNaim_UI_UX_Assignment2.fig`](design/SheikhNaim_UI_UX_Assignment2.fig) | Information architecture, user flows, responsive grid systems. | <img src="screenshots/web-wireframes-overview.png" width="220" alt="Wireframes Board"/> |
| **Phase 2: Interactive Web Prototype** | [`Prototype_Assignment3_UIUX_SheikhNaim.fig`](design/Prototype_Assignment3_UIUX_SheikhNaim.fig) | Full interactive web application, e-commerce flow, events calendar. | <img src="screenshots/web-prototype-overview.png" width="220" alt="Web Prototype Board"/> |
| **Phase 3: Mobile App & Design System** | [`AppPrototype_UIUX_Sheikh_Assignment4.fig`](design/AppPrototype_UIUX_Sheikh_Assignment4.fig) | Native iOS/Android design tokens, AR camera scanner, micro-interactions. | <img src="screenshots/mobile-app-prototype-overview.png" width="220" alt="Mobile Prototype Board"/> |

---

## 📂 Repository Structure

```
greenthumb-uiux-prototype/
├── design/
│   ├── AppPrototype_UIUX_Sheikh_Assignment4.fig     # Mobile App Prototype & Design System
│   ├── Prototype_Assignment3_UIUX_SheikhNaim.fig    # High-Fidelity Web Prototype & Flows
│   └── SheikhNaim_UI_UX_Assignment2.fig             # Responsive Web Wireframes & Architecture
├── screenshots/
│   ├── design_system_tokens.jpg                     # High-res design tokens & component library
│   ├── mobile_onboarding.jpg                        # High-res mobile onboarding & welcome screen
│   ├── mobile_dashboard.jpg                         # High-res mobile home dashboard & care feed
│   ├── mobile_plant_detail.jpg                      # High-res plant profile & moisture gauge
│   ├── mobile_ar_scanner.jpg                        # High-res AR plant camera viewfinder
│   ├── mobile_community.jpg                         # High-res community garden feed & plot waitlists
│   ├── web_desktop_dashboard.jpg                    # High-res desktop web application hub
│   ├── web-landing-hero.png                         # High-res web discovery landing
│   ├── web-plant-care-guide.png                     # High-res plant care encyclopedia
│   ├── web-community-gardens.png                    # High-res community garden network
│   ├── web-marketplace-plants.png                   # High-res marketplace catalog
│   ├── web-events-calendar.png                      # High-res workshop & event calendar
│   ├── plant-care-banner.png                        # Mobile telemetry card
│   ├── mobile-app-prototype-overview.png            # Board thumbnail preview
│   ├── web-prototype-overview.png                   # Board thumbnail preview
│   └── web-wireframes-overview.png                  # Board thumbnail preview
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 How to View and Run the Figma Prototypes

1. **Clone the repository:**
   ```bash
   git clone https://github.com/snaimio/greenthumb-uiux-prototype.git
   ```
2. **Open [Figma](https://www.figma.com/)** (Desktop app or web browser).
3. **Import the files:**
   - In Figma, click **Import** or drag and drop any file from the [`design/`](./design) directory.
4. **Launch Presentation Mode:**
   - Press `Cmd + Option + Enter` (macOS) or `Ctrl + Alt + Enter` (Windows) to run interactive prototype transitions, overlays, and smart animations.

---

## 👤 Author & Designer

**Sheikh Naim (Tanjin Sufi)**  
- GitHub: [@snaimio](https://github.com/snaimio)  
- Figma Prototype: [GreenThumb on Figma](https://www.figma.com)
