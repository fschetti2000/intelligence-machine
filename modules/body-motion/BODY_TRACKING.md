# Body Tracking Module

## 1. Overview

The **Body Tracking** module is a software component designed to support
motion analysis through computer vision and body pose information. The
module combines body/pose tracking, facial detection, motion-related
angle analysis, and a graphical user interface into a single application
workflow.

The project is organized into independent Python components, each
contributing to a specific part of the overall system. The graphical
interface provides the user-facing layer, while the processing
components support the acquisition and analysis of body-motion
information.

The module is intended to provide a structured framework for monitoring
human movement, with particular attention to upper-limb motion and elbow
flexion.

------------------------------------------------------------------------

## 2. Module Structure

The Body Tracking module is composed of the following files:

  -----------------------------------------------------------------------
  File                                Purpose
  ----------------------------------- -----------------------------------
  `FaceDec_func.py`                   Component dedicated to face
                                      detection

  `angle_flex.py`                     Component related to elbow-angle
                                      thresholds and flexion analysis

  `pose_estimation_flex.py`           Component dedicated to pose
                                      estimation and body-tracking
                                      processing

  `requirements.txt`                  List of Python libraries and
                                      dependencies required by the
                                      project

  `v1.0_GUI_motion.py`                Main graphical user interface

  `v1.0_GUI_motion_scalable.py`       Scalable version of the graphical
                                      user interface
  -----------------------------------------------------------------------

The files are organized so that the computer-vision and motion-analysis
components can operate as the processing layer, while the GUI provides
the interaction and visualization layer.

