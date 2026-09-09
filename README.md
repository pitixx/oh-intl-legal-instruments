# One Health Instruments Inventory

An interactive, lightweight web application designed to map and explore global policy instruments, treaties, standards, frameworks, and resolutions relevant to the One Health approach. 

This tool provides a consolidated, searchable interface for navigating complex international frameworks spanning human, animal, and ecosystem health, making it easier to analyze governance roles, operational boundaries, and interlinkages across multilateral agreements.

## 📜 Attribution & Acknowledgments
The substantive mapping, research, and analysis of the instruments within this database were conducted by **Gianluca Burci**. 

This inventory is a product of the **One Health High-Level Expert Panel (OHHLEP)**, developed to support global coordination and implementation of One Health principles.

## ✨ Features
* **Dynamic Search & Filtering:** Instantly filter the database by keyword or by specific instrument categories (Treaty, Standards, Framework, Strategy, Codes of Conduct, Resolution).
* **Detailed Analytical Views:** Click on any instrument to open a comprehensive modal containing:
  * Official descriptions and governing bodies.
  * Alignment with One Health Foundational Principles and Action Tracks.
  * The instrument's specific role in One Health governance.
  * Scope limitations and operational boundaries.
  * Key interlinkages with other international instruments.
* **Responsive Design:** Built with Tailwind CSS to ensure seamless viewing across desktop and mobile devices.
* **Local Data Architecture:** Powered by a clean, easily updatable `data.json` file, requiring no complex backend databases.

## 🛠️ Technical Stack
* **Frontend:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (via CDN)
* **Data Storage:** JSON (`data.json`)

## 🚀 Getting Started

To run this project locally, you only need a basic local web server (to avoid CORS policy restrictions when fetching the JSON file).

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/one-health-inventory.git](https://github.com/your-username/one-health-inventory.git)
   cd one-health-inventory
