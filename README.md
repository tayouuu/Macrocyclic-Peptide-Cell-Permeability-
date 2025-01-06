  1.	Implement CAL Model on Macrocycle Database
	•	Acquire the macrocycle database from the article: https://www.nature.com/articles/s41597-024-03698-y.
	•	Ensure the data (macrocyclic peptides with conformers) is readily accessible for preprocessing.
	2.	Convert Molecules to Graph Representations
	•	Use the pysmiles tool to parse macrocycle SMILES into graph data structures.
	•	Verify node and edge feature assignments (e.g., atomic number, bond type, ring membership) are correct and consistent with the CAL model’s input format.
	3.	Train CAL Model on New Graphs
	•	Set up training scripts to run the CAL model using the newly generated graph dataset.
	•	Monitor training metrics (e.g., loss, accuracy) to ensure convergence and stability.
	4.	Compare Model Predictions with Experiment
	•	Gather experimentally reported permeability data from the database.
	•	Evaluate and compare the model’s predicted permeability values with the experimental references.
	•	Analyze discrepancies and performance metrics (e.g., RMSE, R², classification accuracy).
	5.	Explore “Dynamic” or Incremental Learning Approach
	•	Investigate methods for updating the trained CAL model with new data without full retraining.
	•	Consider incremental or continual learning techniques within GNN frameworks.
	•	Assess feasibility, complexity, and potential performance trade-offs for implementing a dynamic, adaptive model.

