# 2019.04.17

The first meeting of this project was held between Luca, Dimitar and
Kostas over Skype. During the meeting we discussed the objectives of
this collaboration.

## Description of the project

Establish an open-source pipeline for rapid prototyping of
subject-specific musculoskeletal (MSK) and finite element (FE) models
from MRI with emphasis on the knee joint mechanics, but without loss
of generality. The main objectives of this study are:

1. minimize modeling effort and enhance automation in model creation
2. establish a set of open-source tools to address the sub-problems
3. bridge the gap between extraction of boundary conditions (BC) from
   MSK models (e.g., kinematics, joint loads and muscle forces) and
   application in the FE models
4. compare pipeline against generic and subject-specific modeling with
   respect to the FE analysis (e.g., contact pressures, etc.)
5. exchange know-how

## Description of technologies from ICL

(Luca maybe you can update this)

## Description of technologies from UPAT

(TODO Dimitar)

## Next steps

1. Two-weeks or monthly meetings depending on the availability and
   progress.
2. Check if MOCAP data can be shared and under what terms. *Luca*
3. Create a private repository on GitHub.
4. Create a tutorial video on automatic segmentation and
   knee geometry preparation (publication on IEEE Access). *Dimitar*
6. Resolve technical issues regarding application of point forces
   (muscles) in FEBio. *Kostas, Dimitar*
7. Are joint loads enough or should we include muscle forces? Check
   the approach of the guy from CAMS. (Luca we appreciate your thoughts
   here)
8. Include patella in the FE model. *Kostas*
9. Improve muscle line of action plugin. Possibly compute force and
   direction at intermediate muscle path points. *Luca, Dimitar*
