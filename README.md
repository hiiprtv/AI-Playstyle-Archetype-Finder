# AI-Playstyle-Archetype-Finder
Scouting system that instantly classify a player’s “DNA” of playstyle, just like chess engines classify openings.

Project Vision & Impact
This project implements a data-driven system to classify a player's inherent playstyle DNA using unsupervised machine learning. The goal is to move beyond simple statistics, enabling scouts and coaches to recruit players based on precise team fit and tactical role alignment.

This approach provides three core benefits:

Targeted Recruitment: Finding players who perfectly match specific tactical system needs.

Tactical Analysis: Understanding the current squad's distribution of playstyles.

Development Pathway: Tailoring training plans to enhance a player's natural archetype.

Core Data & Technology
The system clusters players based on four key decision metrics (simulated):

Pass Frequency (Volume of passes)

Shot Attempts (Aggressiveness in front of goal)

Risk Index (Complexity of decision-making)

Aggression Factor (Defensive work rate)

The project is built using Python with libraries including Pandas, NumPy, and Scikit-learn.

Implementation
We employ two clustering algorithms:

K-Means Clustering: Partitions players into a defined number of distinct Archetypes (e.g., k=4).

DBSCAN: Identifies natural, density-based clusters and flags highly unique players as Outliers.

All results are visualized in a clear 2D plot after dimensionality reduction via Principal Component Analysis (PCA).

How to Run the Project

Install Dependencies:
pip install numpy pandas scikit-learn matplotlib

Execute the Script:
python playstyle_archetype_finder.py

The script will print the statistical analysis of each archetype and generate the visualization plots.
