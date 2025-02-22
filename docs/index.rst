.. pymdp documentation master file, created by
   sphinx-quickstart on Fri Oct 29 13:27:58 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to pymdp's documentation!
=================================

``pymdp`` is a Python package for simulating active inference agents in
discrete space and time, using partially-observed Markov Decision Processes
(POMDPs) as a generative model class. The package is designed to be modular and flexible, to
enable users to design and simulate bespoke active inference models with varying levels of
specificity to a given task.

.. toctree::
   :maxdepth: 1
   :caption: Installation & Usage

   installation
   notebooks/pymdp_fundamentals
   notebooks/active_inference_from_scratch
   notebooks/using_the_agent_class

.. toctree::
   :maxdepth: 1
   :caption: Examples

   notebooks/tmaze_demo
   notebooks/cue_chaining_demo
   
.. toctree::
   :maxdepth: 2
   :caption: Modules

   inference
   control
   learning
   algos/index


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
