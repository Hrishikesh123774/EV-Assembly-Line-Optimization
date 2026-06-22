# EV Assembly Line Process Optimization & Simulation

## Project Overview
This project applies industrial process engineering principles combined with discrete-event simulation concepts to optimize a commercial Electric Vehicle (EV) manufacturing assembly line. 

Using Python, the simulation models a 4-stage vehicle production flow to identify structural bottlenecks, simulate Lean Manufacturing solutions, and quantify production throughput improvements.

## Core Manufacturing Problem
The assembly line experiences downstream starvation due to a severe cycle time mismatch at the battery pack integration stage.
* **Stage 1:** Chassis Assembly (Target: 45 mins)
* **Stage 2:** Battery Integration (**Bottleneck**: 75 mins)
* **Stage 3:** Powertrain Fitment (Target: 50 mins)
* **Stage 4:** Quality Inspection (Target: 30 mins)

## Solution & Lean Intervention
Implemented a simulated **Lean Six Sigma / Single-Minute Exchange of Die (SMED)** intervention aimed at reducing setup and alignment times at the Battery Integration station by 25%.

## Results & Impact
* **Throughput Increase:** Accelerated total factory production completion timelines by 25.74%.
* **Cycle Time Reduction:** Saved an average of 426.49 minutes per commercial vehicle unit.
* **Resource Optimization:** Eliminated downstream buffer idling times at the Powertrain and Quality QA stations.

## Tech Stack Used
* **Language:** Python 3
* **Libraries:** Pandas (Data structuring), Matplotlib (Bottleneck visualization), Random (Stochastic distributions)
