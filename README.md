TTECTrA
=======
Tool for Turbine Engine Closed-loop Transient Analysis


The introduction and description of TTECTrA is taken from the User's Guide, which is part of the TTECTrA release and published separately as NASA TM 2014-216663  ("Tool for Turbine Engine Closed-loop Transient Analysis (TTECTrA) User's Guide," Csank, J.T., and Zinnecker, A.M.)

## Introduction
The Tool for Turbine Engine Closed-loop Transient Analysis (TTECTrA) is a semi-automated control design tool for subsonic aircraft engine simulations. At a specific flight condition, TTECTrA produces a simple closed-loop controller designed to meet user-defined goals and containing only the fundamental limiters that affect the transient performance of the turbine engine. The purpose of this tool is to provide the user a preliminary estimate of the transient performance of an engine model without the need to design a full nonlinear controller. Development of this tool began under the NASA Fixed Wing’s Systems Analysis and Integration project.

## Description
TTECTrA has been developed in the MATLAB®/Simulink® (The Mathworks Inc.) environment which allows users to access a standard library of functions and to add on toolboxes, such as the Control System Toolbox®. This toolbox includes functions that help to simplify the control design process and is required for use TTECTrA to operate. This user’s guide is written assuming familiarity with MATLAB and Simulink.

TTECTrA contains custom MATLAB functions which perform control design calculations and interact with the user’s Simulink engine model. The tool also contains the TTECTrA Simulink Block (in the TTECTrA_block.mdl file), which implements a scheduled proportional integral (PI) controller with the designed setpoints, gains, and limiters, and supplies the fuel flow input to the user’s engine model.

TTECTrA has been tested and verified using MATLAB Version 8.0 (R2012b), Simulink Version 8.0 (R2012b), and the Control System Toolbox® Version 9.4 (R2012b). The tool integrates with an engine model written in Simulink and requires a piecewise linear state space model of the engine to be available. The TTECTrA software is released under the Apache V2.0 license agreement.

## Getting Started
Stable releases of TTECTrA are located under the releases tab. It is encouraged to download the most up to date version using the appropriate software download button (green button). Installation instructions are detailed in the user's manual which is included within the package.

TTECTrA is an open collaboration. To become a developer, the software maybe forked at any time via the main page link.
