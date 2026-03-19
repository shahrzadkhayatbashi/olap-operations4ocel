# Advancing Object-Centric Process Mining with Multi-Dimensional Data Operations

This repository accompanies the paper Advancing Object-Centric Process Mining with Multi-Dimensional Data Operations. It provides a running example that demonstrates the core concepts and methods proposed in the paper, as well as experiment results for the case study.

## Repository Contents
1. Running Example
The running-example/ folder contains:
* Code: Jupyter notebooks implementing the methods described in the paper using the running example, see [here](running-example/notebooks/demo.ipynb)
* Data: Example event logs that can be used to replicate the methods.

Explore the example to gain a hands-on understanding of how multi-dimensional data operations like drill-down, roll-up, fold, and unfold enhance Object-Centric Process Mining.

2. Experiment Results
Please look at the [case study summary](experiment-results/case_study_summary.md) for more  detailed report of the case study results, showcasing improvements in process model fitness and precision.

Note: Due to confidentiality, the full code and raw data for the case study are not provided.

3. Performance Evaluation using BPIC 2014, BPIC 2016, BPIC 207 and BPIC 2019
The code to run performance evaluation and analysis can be found at the [PerformanceEvaluation Section.](PerformanceEvaluation) folder, where you can rerun the evaluation by:
* downloading [Download BPICs OCELs](PerformanceEvaluation/DownloadBPICsOCELs.ipynb) notebook. 
* Running [Performance Evaluation](PerformanceEvaluation/PerformanceEvaluation.ipynb) notebook. 
* Running [Evaluation Result](PerformanceEvaluation/EvaluationResult.ipynb) notebook to compile the result.
If you only want to see the evaluation result, you can simply look at the [Evaluation Result](PerformanceEvaluation/EvaluationResult.ipynb) notebook. 
