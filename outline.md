# Safety and Efficiency in Autonomous Vehicles through Planning with Uncertainty

## Introduction

### Autonomous Vehicles
### Multi-Objective Optimization
### Uncertainty
- Outcome
- Model
- State
### Markov Decision Processes
- MDPs
- Continuous MDP Solution Methods
    - Approximate Value Iteration
    - Monte Carlo Tree Search with Double Progressive Widening
- POMDPs
- Online POMDP Solution Methods

## UAV Collision Avoidance

### Unique Challenges for Unmanned UAVs
- Commercial Manned Aircraft Collision Avoidance
- Performance Issues -> Horizontal Maneuvers
### Internal States
### Trusted and Optimized Collision Avoidance
- Trusted Resolution Logic
- MDP Optimization
- POMDP Optimization

## Autonomous Highway Lane Changing

### Driver Models and Internal States
- IDM
- MOBIL
- Signalling
### Bounds for Lane Changing Performance
- Fully Observable Upper Bound
- Assumed Static Parameter Lower Bound
### POMDP
- Most Likely MPC
- POMCP-DPW
- DESPOT
- POMCPOW

## POMCPOW: An online algorithm for continuous POMDPs

### Continuous POMDP Solution Methods
### Suboptimality of Modified POMCP-DPW
### POMCPOW
### Numerical Experiments

## POMDPs.jl

### Previous Frameworks
### Design
