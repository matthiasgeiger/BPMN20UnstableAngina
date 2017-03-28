## Fork description

*This repository is a fork of the original Repository [TUe-IS/BPMN20UnstableAngina](https://github.com/TUe-IS/BPMN20UnstableAngina).*

The purpose of this fork is to provide better access to the model stored in the file "CP UA @ CHE (2015-08-10).bpmn" which combines 40 different process models.
Due to the file size, and the usage of the advanced feature of storing more than one `BPMNDiagram` in a single file, the models cannot be displayed in various modeling tools. 
To overcome this issue, the [Signavio](https://www.signavio.com) process editor has been used to extract those diagram to independent files.
During the transformation all SubProcesses with defined `BPMNDiagram`s are extracted in 40 BPMN files.
Apart from changing from `subProcess` to `process` definitions and some minor ID changes the models itself are unchanged.

The extracted models can be found in the folder `Model\CP UA @ CZE - .bpmn\Extracted Models CP UA @ CHE`

**All extracted models are Apache 2.0 licensed as the original models stored in "CP UA @ CHE (2015-08-10).bpmn".**

The original description of the research projects follows: 

# BPMN20UnstableAngina
This repository is an online supplement to the research paper "Towards a library of detailed BPMN Models for Care Coordination: the Unstable Angina Pathway of a Dutch teaching hospital". Abstract: Abstract Managing the coordination of care between different stakeholders is becoming an increasingly recognized research topic. Care coordination is needed to address the worldwide need to increase care quality while reducing expenditures at the same time. All kind of process models (e.g., of care pathways and clinical guidelines) are developed to gain insight in the care processes. Such models enable organizations to reason about redesigns before implementing them and share related information efficiently. Unfortunately, most research results on Care Coordination and Care Pathway modeling focuses on the process of model development. While previous works have refrained from sharing the actual outcome of the modeling efforts, this article contributes its actual model as an open source artifact in an open exchange format. Although the model is based on a case study of just one hospital, it is of considerable quality and size such that it may serve as a valuable input to the modeling efforts of others.

The research paper is currently under review but we aim at making it available through open access.