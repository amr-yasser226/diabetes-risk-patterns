# DSAI 307: Statistical Inference - Final Course Project
## Project Title: Analyzing Diabetes Dataset

### Overview
This project focuses on analyzing the publicly available Pima Indians Diabetes dataset to investigate health trends and factors contributing to diabetes onset. The analysis emphasizes statistical rigor and effective communication through principles of **"Storytelling with Data."**

---

### Phase 1: Exploratory Analysis (20%)
The exploratory phase involves investigating physiological differences and distributions across the dataset. Every analysis point must include concise commentary and at least one appropriate visualization.

**Key Investigation Points:**
1. **Glucose Levels:** Average levels among cohorts.
2. **Age Distribution:** Comparative analysis of patient ages.
3. **Blood Pressure:** Interactions across groups.
4. **BMI Comparisons:** Diabetic vs. non-diabetic metrics.
5. **Global Prevalence:** Overall diabetes rates in the sample.
6. **BMI Distribution:** Frequency analysis of body mass values.
7. **Pedigree Function (DPF):** Genetic predisposition analysis.
8. **Maternal History:** Relationship between pregnancies and occurrence.
9. **Glucose/BMI Correlation:** Linear interaction analysis.
10. **Metabolic Trends:** Tracking glucose against age progression.

---

### Phase 2: Hypothesis Testing (20%)
Assessment of medical claims using formal inferential statistics.

**Required Steps for Each Claim:**
- **Test Selection:** State and justify the statistical test used.
- **Formal Hypotheses:** Clearly defined null ($H_0$) and alternative ($H_a$) hypotheses.
- **Execution:** Report statistical results and p-values.
- **Conclusion:** Validate claims at the $\alpha = 0.05$ significance level.

---

### Phase 3: Monte Carlo Simulation (15%)
Investigation of confidence interval coverage and precision under varying sample sizes ($n$).

**Simulation Protocols:**
- **Trial 1:** 25 random samples of size $n=15$.
- **Trial 2:** 25 random samples of size $n=100$.
- **Trial 3:** 20 random samples of size $n=10$.
- **Objectives:** Observe CI width behavior and evaluate coverage proportions relative to the true population mean.

---

### Phase 4: Documentation & Reporting (25%)

#### 4.1 Technical Notebook
A code-focused document following these standards:
- **Preprocessing:** Step-by-step cleaning (e.g., handling impossible '0' values).
- **Visualization Logic:** Rationales for every plot type chosen.
- **Functionality:** Technical descriptions for help functions.
- **Conclusions:** Summary of computational results and patterns observed.

#### 4.2 Clinical Report (PDF)
A high-level narrative report excluding code, suitable for research dissemination:
- **Abstract & Introduction:** Problem statement and objectives.
- **Methodology:** Description of cleaning and analytical approaches.
- **Findings:** Visualizations with professional captions and expert interpretations.
- **Limitations:** Discussion of biases and demographic constraints.

---

### Deliverables
- **Notebook:** R implementation with Markdown documentation.
- **Technical Report:** Formal PDF summary.
- **Presentation:** PowerPoint slides summarizing key findings.