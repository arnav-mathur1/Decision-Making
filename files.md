## Project Files

### Pre-Internship Research

**Parallel Coordinates.ipynb**  
Initial exploration of parallel-coordinate plots for displaying multiple variables at once.

**Parallel Coordinates2.ipynb**  
Expanded the parallel-coordinate work with feature scaling, axis ordering, transparency, and interactive Plotly visualizations.

**Parallel Coordinates.png**  
Saved example of the parallel-coordinate visualization.

**ThemeRivers.ipynb**  
Explored stream-graph / theme-river visualizations for showing how category distributions change across a sequence.

**Theme Rivers.png**  
Saved example of the theme-river visualization.

**ThemeRivers2.ipynb**  
Applied the stream-graph approach to a real time-series dataset as an additional visualization experiment.

**WTI Price FOB.csv**  
Time-series dataset used for the ThemeRivers2 visualization experiment.

### June

**June28.ipynb**  
Compared the main visualization approaches used throughout the project, including parallel categories, parallel coordinates, and stream graphs.

**June29.ipynb**  
Compared parallel coordinates for continuous variables with parallel categories for discrete variables.

**auto.csv**  
Dataset used in June29.ipynb for visualization testing.

### July

**July07.ipynb**  
Loaded capture-the-flag gameplay data and explored how player positions and destinations could be visualized spatially.

**CaptureFlagBoard1.csv**  
Gameplay-style dataset containing sequential decisions and state information.

**July13.ipynb**  
Generated synthetic decision sequences and created early parallel-set visualizations combining decisions and game-state variables.

**SampleData.csv**  
Synthetic dataset created for the July13 visualization experiments.

**ParallelSetsPlot.png**  
Saved parallel-set visualization from the early synthetic-data experiments.

**July15.ipynb**  
Expanded the synthetic dataset to include multiple decisions and additional variables between stages.

**SampleData2.csv**  
Synthetic multi-stage decision dataset used by July15 and later visualization experiments.

**ParallelSetsPlot2.png**  
Saved visualization showing multiple decision stages in a parallel-set layout.

**July18.ipynb**  
Experimented with a bar-chart view for directly comparing decisions between stages.

**July19.ipynb**  
Created two similarly structured datasets and parallel-category plots to test side-by-side comparison of decision sequences.

**JointEvaluation.csv / SingleEvaluation.csv**  
Decision datasets used for the July19 visualization comparison.

**JointEvaluation.png / SingleEvaluation.png**  
Saved parallel-category plots used for the side-by-side comparison.

**July20.ipynb**  
Aggregated decision frequencies across several stages and visualized them with a stream graph.

**Streamgraph.png**  
Saved stream-graph visualization showing how the mix of decisions changes across stages.

**July21.ipynb**  
Small Decision Tree experiment on a generated decision dataset.

**DecisionTree.csv**  
Dataset used in the July21 experiment.

**July22.ipynb**  
Prototype for capturing mouse input for future interactive data collection.

**July25.ipynb**  
Prototype for a simple interactive grid interface using Tkinter.

**July26.ipynb**  
Made the parallel-category visualization interactive by allowing the user to choose the plot's color variable.

**July27.ipynb**  
Additional interactive parallel-category visualization experiment with a compact synthetic dataset.

**SampleData3.csv**  
Dataset generated for the July27 visualization experiment.

**July28.ipynb**  
Implemented a playable Tic-Tac-Toe game and recorded move sequences and outcomes to CSV files.

**tictactoe_moves_1.csv / tictactoe_moves_2.csv**  
Raw Tic-Tac-Toe move logs generated from the game.

**July29.ipynb**  
Cleaned and transformed Tic-Tac-Toe move logs into standardized decision sequences and visualized paths by outcome.

**X_TicTacToe.csv / O_TicTacToe.csv / TicTacToe.csv**  
Processed Tic-Tac-Toe datasets containing sequential moves and game outcomes.

**TicTacToe_plot.png**  
Saved parallel-category visualization of Tic-Tac-Toe decision paths.

### August — Gameplay Sequence Analysis

**Kaggle_TicTacToe.csv**  
Larger external Tic-Tac-Toe dataset containing thousands of move sequences and outcomes.

**August1.ipynb**  
Cleaned and transformed the larger Tic-Tac-Toe dataset into a standardized format and visualized full decision sequences.

**results_data.csv**  
Processed dataset produced by August1.ipynb.

**August1_v2.ipynb**  
Filtered the larger dataset to a specific opening sequence so later decision branches could be compared more clearly.

**player1_results.csv**  
Intermediate filtered dataset from the August1_v2 analysis.

**August2.ipynb**  
Compared a large full dataset with a smaller scenario-specific subset to show how filtering improves the readability of parallel-set visualizations.

**full_player1_results.csv / partial_player1_results.csv**  
Full and filtered datasets used in the August2 comparison.

**Full_player1.png / Partial_player1.png**  
Saved comparison showing the full visualization versus a filtered scenario.

**August3.ipynb**  
Compared two groups of Tic-Tac-Toe decision sequences and their outcome distributions.

**aug3_player1_data.csv / aug3_player2_data.csv**  
Processed datasets used in the August3 comparison.

### August — Grid Simulation

**August5.ipynb**  
Prototyped movement on a larger grid as a transition from Tic-Tac-Toe to more general sequential movement decisions.

**August8.ipynb**  
Generated a 16x16 grid random walk using eight movement directions and visualized direction, time, and health variables.

**aug8_grid_data.csv**  
Generated grid-movement dataset.

**August8_plot.png**  
Saved parallel-category plot from the grid simulation.

**August10.ipynb**  
Repeated the grid simulation as another baseline and experimented with displaying selected portions of the generated data.

**aug10_data.csv**  
Generated dataset from the August10 baseline.

**August11.ipynb**  
Introduced controlled movement probabilities so some directions were intentionally selected more often than others.

**aug11_data.csv**  
Generated weighted-direction dataset.

### August — Controlled Probability Experiments

**August15_east.ipynb / August15_north.ipynb / August15_south.ipynb / August15_west.ipynb**  
Tested whether a strongly favored movement direction would become visually obvious in the parallel-category plots.

**aug15_data_east.csv / aug15_data_north.csv / aug15_data_south.csv / aug15_data_west.csv**  
Datasets generated from the strongly weighted direction experiments.

**August16_30%.ipynb / August16_40%.ipynb**  
Tested how clearly the visualization exposed increasingly strong probability weighting toward one direction.

**aug16_30%.csv / aug16_40%.csv**  
Datasets generated for the 30% and 40% weighting experiments.

**Weighting1.png**  
Saved visualization showing a strong weighted-direction pattern.

**August17_15%.ipynb / August17_20%.ipynb**  
Tested smaller changes in movement probability to see how visible weaker differences were.

**aug17_15%.csv / aug17_20%.csv**  
Datasets generated for the 15% and 20% weighting experiments.

**Weighting2.png**  
Saved visualization from one of the lower-weight experiments.

## Images

The `Images/` directory contains saved versions of the main visualizations produced by the notebooks, including parallel sets, stream graphs, Tic-Tac-Toe paths, full-versus-filtered comparisons, and weighted-direction experiments.
