# SEMoLa
Simple easy modelling language
SEMoLa (Simple, Easy to use, MOdelling LAnguage) is a non-procedural meta-language to build simulation models for continuous/event driven, deterministic/stochastic, state/individual based systems.
The SEMoLa language has been developed at the Department of Agricultural, Food, Environmental and Animal Sciences (DI4A), University of Udine (Italy) and can be used to represent any system. It is particularly suit to represent biological, ecological and agricultural systems, at different scale and complexity level.
SEMoLa implements the system analysis concepts (Forrester, 1968; Jørgensen, 1994) through a non-procedural declarative logic that makes the code of the model easy to build and read, self-explaining and easy to debug.

The language is managed by a model builder application (SemBuild.exe) that translates the SEMoLa code into Basic code (FreeBasic). This Basic can be compiled by FreeBasic to generate executable models. To this purpose, a static link library (LinModFB.a) is also developing.

SEMoLa models can be run an managed in a simulation framework (SEMoLa.exe) that simplifies the tasks of model building, simulation and documentation; moreover it provides facilities for sensitivity analysis, calibration, validation, data management, statistical analysis, neural network building, unit verification and others. In the framework, all the available features can be activated using a GUI or by commands, in interactive or batch mode. Models can be created using a specific text editor (SemEdit) or other text editors or by the visual environment SemDraw.
