=============================================================================================
Capturing Pertinent Symbolic Features for Enhanced Content-Based Misinformation Detection
=============================================================================================

|License| |PyPI pyversions|

Developed with 💛 at `Expert.ai Research Lab <https://github.com/expertailab>`__

-  License: ISC
-  Paper: `arXiv <https://arxiv.org/abs/2401.16285>`__

Content
---------------
This repository contains **code** and instruction to download **data** for the research paper titled *Capturing Pertinent Symbolic Features for Enhanced Content-Based Misinformation Detection*. It is organized as follows:

- **data/**: Contains instructions for obtaining the data necessary to run the experiments.
- **notebooks/**: Contains Jupyter notebooks for conducting paper experiments, or rather *preprocessing*, *analyzing*, *annotating* and *modeling* misinformation data.


Research work
---------------
In this work, we propose harnessing symbolic linguistic 
resources inspired by insights from social science 
research to automate the detection of content-based 
misinformation. Our experiments leverage a suite of 
off-the-shelf freely available 
`symbolic models <https://www.expert.ai/blog/symbolic-approach-nlp-models/>`__
tailored to identify layered linguistic attributes:

- `writeprint <https://docs.expert.ai/nlapi/latest/reference/output/detection/writeprint/>`__,
- `sentiment analysis <https://docs.expert.ai/nlapi/latest/guide/sentiment-analysis/>`__,
- `emotional traits <https://docs.expert.ai/nlapi/latest/guide/classification/emotional-traits/>`__,
- `behavioral traits <https://docs.expert.ai/nlapi/latest/guide/classification/behavioral-traits/>`__,
- `hate speech <https://docs.expert.ai/nlapi/latest/reference/output/detection/hate-speech/>`__,
- `radicalization narratives <https://ceur-ws.org/Vol-2342/paper5.pdf>`__,

This information is subsequently combined with 
the capabilities of language models. 
Our method is validated across a range of 
`datasets <https://github.com/expertailab/Capturing-Pertinent-Symbolic-Features-for-Enhanced-Content-Based-Misinformation-Detection/tree/main/data>`__, 
carefully selected and analyzed to represent the 
heterogeneous misinformation phenomenon.


.. Installation
.. ------------

.. The whole project is handled with ``make``, go to a terminal an issue:

.. .. code:: bash

..    make setup
..    ...

Reproducibility
---------------

**Data**: Follow the instructions in the README located within the *data/* directory to obtain both the raw and already preprocessed datasets required to conduct the experiments.

**Code**: Code to *preprocess*, *analyse*, *annotate* and *model* data is temporarily shared within Jupyter notebooks in the *notebooks/* directory.

.. To reproduce the results from the original paper, do:

.. .. code:: bash

..    make repro


.. Contribution
.. ------------

.. Contributions are welcome, and they are greatly appreciated! Every
.. little bit helps, and credit will always be given.

.. To contribute, have a look at `Contributing <./CONTRIBUTING.rst>`__

How to cite
-----------

To cite this research please use the following::

    @inproceedings{merenda2023capturing,
      title={Capturing Pertinent Symbolic Features for Enhanced Content-Based Misinformation Detection},
      author={Merenda, Flavio and Gomez-Perez, Jose Manuel},
      booktitle={Proceedings of the 12th Knowledge Capture Conference 2023},
      pages={61--69},
      year={2023}
    }

|Expert.ai favicon| Expert.ai
-----------------------------

At Expert.ai we turn language into data so humans can make better
decisions. Take a look `here <https://expert.ai>`__!

.. |License| image:: https://img.shields.io/badge/License-ISC-blue.svg
   :target: http://perso.crans.org/besson/LICENSE.html
.. |PyPI pyversions| image:: https://badgen.net/pypi/python/black
   :target: https://www.python.org/
.. |Docker| image:: https://badgen.net/badge/icon/docker?icon=docker&label
   :target: https://docker.com/
.. |Expert.ai favicon| image:: https://www.expert.ai/wp-content/uploads/2020/09/favicon-1.png
   :target: https://expert.ai
