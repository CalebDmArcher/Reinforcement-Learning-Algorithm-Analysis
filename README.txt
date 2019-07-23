hw4 reinforment learning

The code required for this project is in the folder hw4.
It is java code which is suggested ran in IntelliJ.
To run the code, BURLAP need to be download as well as Maven

************************
!       IMPORTANT      !
************************
The code is borrowed from OMSCS project back from 2015.
Thus the BURLAP required is not the latest version, it is version 2.1.0 or 2.1.2
which contains the 'oomdp' class. The newset BUTLAP will not be able to compile
the code!
================================================================================

The most important java file is in the path:
hw4/src/main/assignment4/EasyGridWorldLauncher.java
hw4/src/main/assignment4/HardGridWorldLauncher.java

-Running:
In above two file, by set the runValueIteration
                            runPolicyIteration
                            runQLearning
                        and showValueIterationPolicyMap
                            showPolicyIterationPolicyMap
                            showQLearningPolicyMap
will run and plot the corresponding resulted policy.

If you try to run the code with IntelliJ and 'Edit configuration' window pop up,
click 'Run' and then click 'Continue Anyway'.



-ALPHA & GAMMA modification:
In the path: hw4/src/main/assignment4/util/AnalysisRunner
parameters can be changed under ValueIteration()
                                PolicyIteration()
                                QLearning()

(There is also an FAQ.pdf file that has general introduction of the outputs.)




==============================
The figures in the anaysis paper is also stored in the file 'hw4plot.pptx'.
Datasets from the experiment are stored in 'hw4data.csv'
                                           'hw4data (2).xlsx'
                                           'hw4data2_QOL_Compare.xlsx'
