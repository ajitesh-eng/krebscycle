# krebscycle
krebs-cycle stimulation live and interactive web-page.
# 🧬 Interactive Krebs Cycle Explorer

An interactive, single-page educational web application that visualizes the **Krebs Cycle** (also known as the **Citric Acid Cycle** or **Tricarboxylic Acid [TCA] Cycle**). Designed for biology students, educators, and biochemistry enthusiasts, this tool brings cellular respiration inside the mitochondrial matrix to life with dynamic SVG animations, real-time stoichiometric tracking, and an integrated quiz engine.

---

## ✨ Key Features

* **🎡 Interactive SVG Metabolic Wheel:**
  * Clickable nodes for all **8 core metabolites** and **8 enzymatic steps**, plus the preparatory Acetyl-CoA entry feed.
  * Animated reaction pathways with glowing byproduct badges ($\text{NADH}$, $\text{FADH}_2$, $\text{GTP/ATP}$, and $\text{CO}_2$).
  * Visual indicators for irreversible rate-limiting steps vs. reversible reactions.
* **⚡ Real-Time Energy & Stoichiometry Tracker:**
  * Toggle between **1× Acetyl-CoA (1 Turn)** and **1× Glucose (2 Turns)** to observe how coenzyme and byproduct yields scale dynamically.
  * Automatic calculation of total **ATP equivalents** via Oxidative Phosphorylation (Electron Transport Chain conversions: $1\text{ NADH} \approx 2.5\text{ ATP}$, $1\text{ FADH}_2 \approx 1.5\text{ ATP}$).
* **🔬 Deep Biochemical Inspector:**
  * **Carbon-Backbone Visualizer:** Track carbon atoms ($6\text{C} \rightarrow 5\text{C} \rightarrow 4\text{C}$) across oxidative decarboxylation steps.
  * **Thermodynamics:** View standard Gibbs free energy changes ($\Delta G^{\circ\prime}$ in $\text{kJ/mol}$) for every reaction.
  * **Allosteric Regulation:** Inspect key activators ($\text{ADP}$, $\text{Ca}^{2+}$, $\text{NAD}^+$) and inhibitors ($\text{ATP}$, $\text{NADH}$, $\text{Succinyl-CoA}$, $\text{Citrate}$) governing cellular respiration.
* **⏯️ Playback & Keyboard Controls:**
  * Step through the cycle manually or use **Auto-Play** at adjustable speeds (*Slow*, *Normal*, *Fast*).
  * Full keyboard navigation support for seamless classroom presentations or study sessions.
* **🧠 Integrated Biochemistry Quiz Mode:**
  * Test your mastery of enzymes, substrates, decarboxylation steps, and energy yields with instant feedback and explanations.

---

## 🚀 Getting Started

Because this application is built as a self-contained single-page web app, no build tools, package managers, or external servers are required.

### Option 1: Direct Browser Launch
1. Download or clone this repository:
   ```bash
   git clone [https://github.com/your-username/interactive-krebs-cycle.git](https://github.com/your-username/interactive-krebs-cycle.git)
