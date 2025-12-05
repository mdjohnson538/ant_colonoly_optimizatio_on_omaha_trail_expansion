# Ant Colony Optimization for Omaha Bike Route Planning  
**ISQA 8086: Special Topics in ISQA – Prescriptive Analytics**

This repository contains a class project exploring the use of **Ant Colony Optimization (ACO)** as a prescriptive analytics method for improving bike route planning in the Omaha metro area. The project applies a custom ACO implementation to GIS-based trail data to identify proposed trail segment expansions that are most optimal int erms of their connective value. 

---

## 📘 Project Overview
The goal of this project is to illustrate how ACO can be used to generate high-quality routes across a network of proposed and existing bike trails. The work includes:

- Preprocessing and cleaning Omaha trail network data  
- Implementing an ACO algorithm in Python  
- Defining cost functions based on geometry and segment attributes  
- Visualizing resulting paths and pheromone distributions  
- Demonstrating exploration vs. exploitation dynamics  
- Offering a prescriptive approach to evaluating future bike infrastructure

All analysis is performed in a Jupyter notebook (`AOC_Bike_Routes v2.ipynb`).

---

## 🗺️ Data Source
Trail and roadway GIS data were obtained from the Douglas County GIS Open Data portal:

**https://data-dogis.opendata.arcgis.com/**

Datasets were used solely for academic purposes within the context of this ISQA 8086 course project.

---

## 🐜 Ant Colony Optimization (ACO)
ACO is a nature-inspired metaheuristic where “ants” explore candidate solutions and deposit pheromones that guide future search iterations. This project includes:

- State transition rules  
- Pheromone update formulas  
- Evaporation dynamics  
- Parameter tuning and experimentation

The implementation demonstrates how algorithmic settings affect optimal route selection and convergence behavior.

---

## 🗂 Repository Contents
- `AOC_Bike_Routes v2.ipynb` — Main notebook with all preprocessing, ACO logic, tuning, and visualizations  
- `data/` (optional) — Placeholder for raw GIS data if added later  
- `plots/` (optional) — Output images such as route maps or convergence curves

---

## 📈 Results Summary
The notebook demonstrates:

- How different ACO parameter settings influence route selection  
- Optimized bike routes generated from the ACO run  
- Visualization of pheromone intensities and chosen paths  
- How prescriptive analytics techniques can support real-world planning applications

---

## 📚 Course Context
This project was completed for:

**ISQA 8086 – Special Topics in ISQA: Prescriptive Analytics**  
University of Nebraska Omaha  

The assignment required implementing a prescriptive method and applying it to a dataset selected by the student.

---

## ⚙️ Dependencies
- Python 3.10+  
- Jupyter Notebook  
- `numpy`  
- `pandas`  
- `networkx`  
- `geopandas`  
- `matplotlib`

Install dependencies with:

```bash
pip install -r requirements.txt
