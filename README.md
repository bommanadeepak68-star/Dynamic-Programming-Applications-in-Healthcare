# Dynamic-Programming-Applications-in-Healthcare
This research project explores the application of Dynamic Programming (DP) techniques to healthcare decision-making. It focuses on developing optimal decision policies for healthcare scenarios by modeling sequential decisions, evaluating possible outcomes, and optimizing resource utilization. 

Overview

This project investigates how Dynamic Programming (DP) can support sequential healthcare decision-making. It uses a Markov Decision Process (MDP) formulation and backward induction to identify optimal treatment decisions over a finite planning horizon.

Objectives

Formulate healthcare treatment decisions as a finite-horizon MDP.
Implement backward induction using Python and NumPy.
Compare the optimal policy against four fixed treatment strategies.
Analyze the effects of treatment side-effect costs and planning horizons.
Compare the computational performance of dynamic programming and exhaustive policy enumeration.

Key Results

The DP policy achieves 7.061 expected QALYs for a patient starting in the Mild state, compared with 6.950 for the best fixed treatment strategy.

At a six-year horizon, dynamic programming finds the same optimal value as exhaustive enumeration, taking approximately 0.09 milliseconds compared with 18.7 seconds.

The experiments demonstrate how treatment decisions can depend on both the patient's disease state and the remaining planning horizon.
