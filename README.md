## Seismic Modeling and Analysis of Special Truss Moment Frames (STMFs)

#  Project Description
- This project investigates the **seismic performance of Special Truss Moment Frames (STMFs)** using
**OpenSeesPy**. The work emphasizes step-by-step model development, nonlinear simulation, and validation based on the **Performance-Based Plastic Design (PBPD)** methodology. Structural modeling was carried out by replicating Example 12 of Chao & Goel’s PBPD research, incorporating **realistic member configurations** and advanced nonlinear features.  

- The project culminates in a **validated nonlinear model** of a single-bay, single-story STMF using **fiber sections** and lays the computational groundwork for future expansion to **multi-bay, multi-story systems**. The study demonstrates a practical workflow for analyzing ductility, targeted yielding, and second-order effects in STMFs, providing an extendable modeling framework for seismic design research.

---

# Objectives
- Develop STMF models incrementally: **elastic single-bay → multi-story → nonlinear fiber-section** systems.
- Investigate **yielding behavior, ductility demand, and energy dissipation mechanisms**.
- Implement advanced analysis techniques: **P-Delta geometric transformations, Steel02 hysteretic materials, Lobatto section integration**.
- Establish a computational foundation for scaling to **5-bay, 9-story nonlinear STMFs**.

---

# Scope of Work (Current)
- Constructed and validated:
  - Elastic **single-bay, single-story** frame model.
  - Elastic **9-story** frame for scaling verification.
  - Nonlinear **fiber-section single-bay** STMF capturing plastic hinge formation.
- Applied **PBPD methodology** to member detailing and load patterns.
- Modeled realistic **vertical, diagonal, and chord member configurations**.
- Performed validation of connectivity, boundary conditions, and load distribution.

---

# Tools & Techniques
- **Software:** OpenSeesPy, Python, opsvis (visualization)
- **Element Types:** Elastic beam-column, force-based beam-column, fiber-section elements
- **Analysis Features:** P-Delta effects, Lobatto integration (5–7 points), Steel02 cyclic material modeling
- **Concepts:** PBPD methodology, nonlinear seismic analysis, second-order effects

---

# Future Extension
- Expand framework to **5-bay, 9-story nonlinear STMF**.
- Automate geometry and load generation.
- Conduct detailed seismic performance evaluation across multiple frame configurations.

---

#  Reference
- [Performance-Based Plastic Design of Special Truss Moment Frames (Chao & Goel, 2008)]( https://www.aisc.org/globalassets/product-files-not-searched/engineering-journal/2008/45_2_127.pdf)
