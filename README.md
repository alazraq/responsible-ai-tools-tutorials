# Responsible AI tools tutorials

<img src="responsible_ai_tools_tutorials.png" alt="Repository logo" width="800"/>


This repository contains hands-on tutorials for Microsoft's most prominent Responsible AI tools.
It is primarily designed for developers and data scientists to provide them with jump-start guides for using each tool in the form of jupyter notebooks. 

Responsible AI is still an underrated subject among data scientists and AI practicionners more broadly and today a huge gap between principles and practices exists when it comes to implementing AI systems in a more responsible manner. These tutorials are meant to accompagny the whitepaper "Putting Responsible AI into practice for your AI-based solutions" which tackles exactly this issue and can be found under the whitepaper folder.

## Overview of the available hands-on tutorials

We investigate three categories of Responsible AI tools:

* Tools to understand the behaviour of AI systems. These in turn fall into two categories:
    - Tools to assess and mitigate fairness issues. Here we focus on **Fairlearn**.
    - Tools to understand and explain AI systems predictions. Here we focus on **InterpretML** and **Error Analysis**.
* Tools to protect AI systems data: 
    - Data anonymization using **Presidio**.
    - Differential privacy with the **SmartNoise** system.
* Dashboards and user interfaces grouping such Responsible AI tools together under a single roof. Here we will look at **Responsible-AI-Widgets**.

## Links to complete notebook samples 

Please be aware that the notebooks provided here are simplified versions of sample notebooks provided as examples in each tool's repository. The goal is to provide minimal working code for each tool and to aggregate these guides under one roof. 
If you would like to go further and access more complete demos, we provide the links to the original notebooks below:

- [Fairlearn] (https://github.com/fairlearn/fairlearn/blob/main/notebooks/Binary%20Classification%20with%20the%20UCI%20Credit-card%20Default%20Dataset.ipynb)
- [InterpretML](https://github.com/interpretml/interpret-community/blob/master/notebooks/explain-binary-classification-local.ipynb)
- [Error Analysis](https://github.com/microsoft/responsible-ai-widgets/blob/main/notebooks/erroranalysis-dashboard-multiclass.ipynb)
- [Presidio](https://github.com/microsoft/presidio/blob/main/docs/samples/python/presidio_notebook.ipynb)
- [SmartNoise](https://github.com/opendp/smartnoise-samples/blob/master/whitepaper-demos/2-reidentification-attack.ipynb) 