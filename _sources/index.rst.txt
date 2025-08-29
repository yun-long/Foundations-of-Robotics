Foundations of Robotics
===================================================

.. image:: ./images/diagram_gray.png
   :alt: Description of the image
   :width: 100% 

The goal of this project is to provide a comprehensive introduction and overview
to the foundations of robotics. I will mainly focus on the theoretical foundations of
robotics, including kinematics, dynamics, control, motion planning, perception,
and nowdays, machine learning, deep learning, reinforcement learning, and other
modern techniques. I stand on the shoulders of giants, and I will try to provide
a comprehensive overview of the field, but only focusing on the most important 
concepts and theory.

.. .. raw:: html

..     <embed src="./pdfs/reinforcement_learning.pdf" width="100%" height="850px"/>


..     <a href="./pdfs/reinforcement_learning.pdf" target="_blank">PDF.</a>

.. toctree::
   :maxdepth: 2
   :caption: Basics:

   sections/basics/linear_algebra.rst
   sections/basics/robot_dynamics.rst

.. toctree::
   :maxdepth: 2
   :caption: Control:

   sections/control/control_theory.rst
   sections/control/oc.rst
   sections/control/numerical_oc.rst

.. toctree::
   :maxdepth: 2
   :caption: Learning:

   sections/learning/ml.rst
   sections/learning/dl.rst
   sections/learning/rl.rst

.. toctree::
   :maxdepth: 2
   :caption: Vision:

   sections/perception/dl4cv.rst
   sections/perception/v4mr.rst

.. toctree::
   :maxdepth: 2
   :caption: Planning:

   sections/planning/motion_planning.rst
   sections/planning/optimization.rst

.. toctree::
   :maxdepth: 2
   :caption: Case Studies:

   sections/cases/quadrotor.rst
   sections/cases/manipulator.rst
   sections/cases/legged.rst


