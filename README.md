# COVID-19 Drug Repurposing Analysis

This project explores **drug repurposing for COVID-19** by simulating the docking of FDA-approved drugs against key SARS-CoV-2 proteins.  
The goal is to identify potential inhibitors that could be repurposed for COVID-19 treatment.

---

## 📖 Project Workflow
1. **Dataset Creation**: A curated list of FDA-approved drugs and viral protein targets (Main Protease, Spike Protein RBD, RNA Polymerase).  
2. **Molecular Docking Simulation (Dummy)**: Binding energies were simulated in the range `-5 to -11 kcal/mol` to represent realistic docking scores.  
3. **Analysis**: The best candidate drugs were identified for each protein target.  
4. **Visualization**: Binding energies compared across all drugs using bar plots.  
5. **Results Export**: Findings saved in `covid19_docking_results.csv`.

---

## 📊 Example Results
- **Main Protease (Mpro)** → Ritonavir (Best hit)  
- **Spike Protein RBD** → Remdesivir (Best hit)  
- **RNA Polymerase (RdRp)** → Favipiravir (Best hit)  

*(Results are simulated and for demonstration only.)*

---

## 🚀 Tech Stack
- **Python**  
- **Pandas, Numpy** (data analysis)  
- **Matplotlib, Seaborn** (visualization)  

---

## 📌 Note
This is a **dummy demonstration project** for showcasing skills in **bioinformatics and drug discovery pipelines**.  
No actual molecular docking software (AutoDock, PyRx, etc.) was used — results are synthetic but realistic.  

---

## 🔗 Usage
```bash
git clone https://github.com/your-username/covid19-drug-repurposing.git
cd covid19-drug-repurposing
jupyter notebook covid19_drug_repurposing.ipynb
