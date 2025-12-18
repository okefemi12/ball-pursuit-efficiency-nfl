# Ball Pursuit Efficiency (BPE)

**Track:** Analytics & Broadcast Visualization  
**Competition:** NFL Big Data Bowl 2026

## Overview
Ball Pursuit Efficiency (BPE) is a novel metric designed to quantify how efficiently an NFL player moves toward the projected landing point of the football after the quarterback releases the ball. The metric captures player discipline, reaction quality, and pursuit effectiveness using tracking data and machine learning.

## Methodology
- Player tracking data from the NFL Big Data Bowl
- Physics-based baseline trajectory using player velocity and direction
- Ensemble XGBoost model to estimate optimal ball landing position
- Sequence-based deep learning model to capture player movement dynamics
- BPE score computed as deviation from the optimal pursuit path

## Applications
- Player evaluation and scouting
- Coverage and route effectiveness analysis
- Scheme and alignment assessment
- Broadcast analytics and storytelling

## Reproducibility
The full pipeline is implemented in a Kaggle notebook and can be run end-to-end in the Kaggle environment.

## Author
Oke Precious
