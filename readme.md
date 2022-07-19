# Lungs CT-based Classification for COVID19-vs-Non COVID19
## Description
During the outbreak time of COVID-19, computed tomography (CT) is a useful manner for diagnosing COVID-19 patients.
Due to privacy issues, publicly available COVID-19 CT datasets are highly difficult to obtain, which hinders the research
and development of AI-powered diagnosis methods of COVID-19 based on CTs. To address this issue, UC San Diego and UC Berkeley 
have build an open-sourced dataset COVID-CT [1], which contains 349 COVID-19 CT images from 216 patients and 463 non-COVID-19 CTs.
The utility of this dataset is confirmed by a senior radiologist who has been diagnosing and treating COVID-19 patients since the outbreak
of this pandemic.
## Material
The dataset is available and can be downloaded from GitHub. The COVID-CT-Dataset has 349 CT images
containing clinical findings of COVID-19 from 216 patients. They are in ‘./Images-processed/CT_COVID.zip’.
Non-COVID CT scans are in ‘./Images-processed/CT_NonCOVID.zip’. The meta information (e.g., patient
ID, patient information, DOI, image caption) is in COVID-CT-MetaInfo.xlsx. The images are collected from
COVID19-related papers from medRxiv, bioRxiv, NEJM, JAMA, Lancet, etc. CTs containing COVID-19
abnormalities are selected by reading the figure captions in the papers. All copyrights of the data belong
to the authors and publishers of these papers. The dataset details are described in this preprint: https://arxiv.org/pdf/2003.13865.pdf
## Aim
Aim is to perform binary image classification (i.e. ‘COVID-vs-NonCOVID’) using Transfer Learning and then optimizing the results.