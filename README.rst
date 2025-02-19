ETA Factory Climate Room
===============================

The *ETA Factory Climate Room (ETA CR)*, developed by the team of the `ETA-Fabrik <https://www.ptw.tu-darmstadt.de>`_ at Technical University of Darmstadt, is a TwinCat 3 project implementing the automation system of the climate room at ETA Research factory.

Project structure
-----------------

The library *ETA RC* consists of three packages for DUTs, POUs and GVLs. DUT and POU package are structured in the following subpackages:

- The **01 Acuators** package holds implementations for single components (e.g. energy converters and storages).
- The **02 Sensors** package holds implementations for complex and unique sensor components which are not implemented within the project *ETA Factory Automation Base Classes*.
- The **03 Storages** package holds implementations for thermal storages.
- The **04 Systems** package holds implementations for systems consising of a main components (e.g. energy converter) and sub-components (e.g. pumps, valves and sensors).

The *.tsproj* file is not pubslished for safety reasons as they hold safety-critical network information.