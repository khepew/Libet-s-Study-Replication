# Replication of Results from [Libet's Experiment: A Complex Replication](https://pubmed.ncbi.nlm.nih.gov/30007132/) by Tomáš Dominik et al.

This project is a comprehensive replication of the results presented in the paper [Libet's Experiment: A Complex Replication](https://pubmed.ncbi.nlm.nih.gov/30007132/) by Tomáš Dominik et al. The purpose of this project is to faithfully replicate and validate the findings of Libet's original experiment, which examines the relationship between brain activity and conscious intention to perform voluntary actions.

## Project Structure

### 1. Data Collection
- The experiment was conducted on 8 participants (4 males, 4 females), divided into two groups.
- EEG and EMG data were recorded from specific electrodes, following the 10-20 system.
- Data was collected using a custom web-based program replicating Libet's clock, adhering closely to the original methodology.

### 2. Experimental Setup
- **Libet’s Clock**: A web-based program with a clock face was used, where a dot moves around the clock. Participants had to either perform a mouse click or wait for a stimulus and then report the position of the dot at the moment of their conscious intention or movement.
- **Tasks**: Participants were involved in multiple task series, including M, W, S, P, and Pv series, each varying slightly in their introspective task (e.g., reporting the moment they first felt the urge to move).

### 3. Data Analysis
- **EEG/EMG Processing**: Data was processed to identify readiness potentials (RP) and other significant brain activities. The EMG signals were used to identify the onset of muscle activity.
- **Statistical Analysis**: The grand average technique was used to analyze data across all participants, ensuring the robustness of the findings.

### 4. Results
- The results of the replication are detailed and visualized in the Jupyter Notebook included in this repository. The notebook provides a step-by-step analysis and comparison with the original findings by Tomáš Dominik et al.
- Key findings such as the timing of conscious intention relative to brain activity are discussed and visualized through plots and statistical analysis.

### 5. Replication Challenges
- **Methodological Differences**: Some modifications to the original experiment were necessary due to technical constraints and modern ethical standards. These changes are documented and discussed in the notebook.
- **Inter-individual Variability**: Significant differences were observed in introspective reports among participants, which suggests that individual differences play a crucial role in experiments of this nature.

## Conclusion

This project successfully replicates the original findings of Libet's experiment with minor methodological adjustments. The results reaffirm the complex relationship between brain activity and conscious intention, as originally proposed by Libet and further explored by Tomáš Dominik et al.

For further details on the experiment and findings, please refer to the Jupyter Notebook.
