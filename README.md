# AIScientist_Text2SQL
This repository contains complete result bundles for three successful ideas that improved a Text-to-SQL benchmark using the AI-Scientist(Sakana-AI) workflow using GigaChat-Max.
The experiments test different optimization strategies, including Monte Carlo Tree Search (MCTS) and alternative approaches.

# Repository Structure
Root Directory
join_order_optimization_through_targeted_sampling_run_4_mcts/ Experiment run #4 for join order optimization with MCTS.

join_order_optimization_through_targeted_sampling_run_4_no_mcts/ Experiment run #4 for join order optimization without MCTS.

run_0_baseline_mcts/ Baseline experiment run with MCTS.
run_0_baseline_no_mcts/ Baseline experiment run without MCTS.

structured_query_decomposition_run_1_mcts/ Experiment run #1 for structured query decomposition with MCTS.

structured_query_decomposition_run_1_no_mcts/ Experiment run #1 for structured query decomposition without MCTS.

total_ideas.json - generated ideas across experiments.

README.md
This file.

Experiment Directory Contents
Each experiment directory (e.g., run_0_baseline_mcts/) contains:

bench.log: Detailed log of benchmark execution steps with question and sql, gold sql

predictions.sql: Generated SQL queries 

Notes
MCTS vs. Non-MCTS: Directories with _mcts use Monte Carlo Tree Search; others use alternative methods.

Baseline Runs: run_0_baseline_* serve as reference points for comparison.

Data Source: The file 250814150114__minibird_sqlite_ddl_stat_5t_10c__deepseek-coder-v2.zip in run_0_baseline_no_mcts/ likely contains dataset schema/statistics used for SQL generation.

Purpose
These experiments evaluate:

Join Order Optimization: Testing targeted sampling strategies.

Structured Query Decomposition: Breaking complex queries into simpler subproblems.

MCTS Impact: How Monte Carlo Tree Search influences SQL generation accuracy/efficiency.

# How to Use
Please contact me or any of the article's authors—we can provide the code and explain how to properly run the benchmark, prepare data from mini Bird, and reproduce the results.