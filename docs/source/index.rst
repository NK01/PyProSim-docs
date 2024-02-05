.. PyProSim documentation master file, created by
   sphinx-quickstart on Sat Feb  3 21:49:13 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to PyProSim's documentation!
====================================

Process simulation is a powerful tool for enabling the optimization of an existing process and the development of new processes at a relatively low cost.
A new platform for process simulation called **PyProSim** is developed to assist the process simulation based on the local equilibrium concept using
Effective Equilibrium Reaction Zone (EERZ) model. PyProSim has four simple modules to create the process flowsheet of any complex reactor and continuous processes,
and employs the accurate and reliable FactSage thermodynamic databases and Gibbs Energy Minimizer to perform complex multicomponent chemical reactions.
The simulation of a simplified Basic Oxygen Furnace (BOF) process is presented here as an example of PyProSim.

.. image:: /images/title.PNG
   :width: 800

Optimization of existing metallurgical processes and development of new processes through experiments and plant trials requires a lot of time and resources,
therefore modeling becomes an indispensable tool. Process simulation is a powerful tool for modeling the whole life cycle of a process, from
initial material insertion to final product output, making the integration of simulation tools necessary. Process Simulation is based on models, and the model
should try to replicate the thermochemistry of the process as accurately as required. However, the main drawbacks of the existing process simulation platforms is
the lack of reliable thermodynamic databases. For instance, Aspen HYSYS, which is a workflow-oriented simulation software, has a weak pyrometallurgy database,
limiting its use to oil and gas industries. Similarly, HSC chemistry, which has multiple calculation modules for process units, lacks alloy and solution databases.
In some cases, the need for expertise in programming, such as for the SimuSage3 software package, which was developed as the extension for Delphi programming environment,
making them unsuitable for general users to make process modeling.

In order to make process calculations without any coding, we have developed a new flowsheet program “PyProSim” for process simulation applications.
PyProSim software employs the accurate and reliable thermodynamic databases from FactSage Thermochemical Software and Gibbs Energy Minimizer (ChemSage) though
ChemApp to perform complex multiphase, multicomponent equilibrium calculations. PyProSim uses an intuitive flowsheet diagram approach to model the process with modules,
which interact with each other through the flow of materials. It is designed with a drag-and-drop approach, providing a user-friendly interface with no coding required.

Check out the :doc:`installation_guide` section for further information, including how to
:ref:`install <installation>` the project.

.. note::

   This project is under active development.

.. toctree::
   :maxdepth: 3
   :caption: Contents:

Contents
--------

.. toctree::
   installation_guide
