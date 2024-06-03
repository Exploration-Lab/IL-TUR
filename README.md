# IL-TUR: Benchmark for Legal Text Understanding and Reasoning


This repository contains the official release of the following paper:

**IL-TUR: Benchmark for Legal Text Understanding and Reasoning**<br>

**Authors:** Abhinav Joshi, Shounak Paul, Akshat Sharma, Pawan Goyal, Saptarshi Ghosh, Ashutosh Modi <br>

**Abstract:** 
*Legal systems worldwide are inundated with exponential growth in cases and documents. To streamline the legal system, there is an imminent need to develop NLP and ML techniques for automatically processing and understanding legal documents. However, evaluating and comparing various NLP models (e.g., LLMs) developed specifically for the legal domain is challenging. This paper address this challenge by proposing IL-TUR: Benchmark for Legal Text Understanding and Reasoning. We propose various domain-specific tasks that address different aspects of the legal domain from the point of view of understanding and reasoning. We also present baseline models for each task, outlining the gap between the LLM-based models and ground truth. A public leaderboard has been created where the research community can upload and test legal text understanding systems on various metrics, thus fostering research in the legal domain.*


## IL-TUR Leaderboard

Please find the updated leaderboard along with tasks details on the [🔗 IL-TUR Leaderboard Page](https://cse.iitk.ac.in/users/ashutoshm/IL-TUR/).


## Tasks

Table below shows **Tasks** currently available in the IL-TUR benchmark.


| Task | Links to dataset files | Evaluation Metric | More Links | 
| :-----       | :---              | :-----   | :-----   
| L-NER |   [ 🔗 L-NER-Data ](https://1drv.ms/f/s!AuBOJ2hW9Gimgbl0-UY_ydhQvfF7_g?e=vcrHPD)   | Strict m-F1 | [[Model]](https://1drv.ms/f/s!AuBOJ2hW9GimgfwveSvzz6lwu0GrPQ?e=GC53SB)[[Code]](https://1drv.ms/f/s!AuBOJ2hW9Gimgo0U74qC4QIAk31Kjg?e=Ya458K)[[Evaluation Script]](https://1drv.ms/f/s!AuBOJ2hW9Gimg6JhZWRMXL79k9Suig?e=1J4C6o) |
| RR |   [🔗 RR-Data](https://1drv.ms/f/s!AuBOJ2hW9GimgboYOG7ZQ99lKJg4Rg?e=Fui1GV)   | m-F1 | [[GitHub]](https://github.com/Exploration-Lab/Rhetorical-Roles)[[Evaluation Script]](https://1drv.ms/f/s!AuBOJ2hW9Gimg6JwZM61cExMmMAUig?e=pBlXK1) |
| CJPE    |  [ 🔗 ILDC](https://1drv.ms/f/s!AuBOJ2hW9GimgbsPCVlE80TSfjk7Ig?e=pyCkAc)   | m-F1, ROUGE-L | [[GitHub]](https://github.com/Exploration-Lab/CJPE)[[Evaluation Script]](https://1drv.ms/f/s!AuBOJ2hW9Gimg6Jd2JJu22FzzlwGWA?e=DXm20B) |
| BAIL     |      [🔗 HLDC](https://1drv.ms/f/s!AuBOJ2hW9Gimgbol9ZZbin4eMxnp6g?e=DKo12s)   | m-F1 | [[GitHub]](https://github.com/Exploration-Lab/HLDC)[[Evaluation Script]](https://1drv.ms/f/s!AuBOJ2hW9Gimg6JYHbhc7jVM5HTlUg?e=c8Op1j) | 
| LSI      |      [🔗 ILSI](https://1drv.ms/f/s!AuBOJ2hW9GimgblvnEV3H715vhgCZQ?e=2CnaV1)   | m-F1 | [[Model]](https://1drv.ms/f/s!AuBOJ2hW9GimgfIpwcYSJjsHUi87XA?e=0Aiv4C)[[Code]](https://1drv.ms/f/s!AuBOJ2hW9GimgodqCD2mIZVQIRMbdg?e=YmIFUX)[[Evaluation Script]](https://1drv.ms/f/s!AuBOJ2hW9Gimg6JrvpZm-7AlhGX0lQ?e=yVCItn) |
| PCR     |       [🔗 IL-PCR](https://1drv.ms/f/s!AuBOJ2hW9GimgbotGnN0nwbXPUzg5Q?e=KDezhw)   | &mu;-F1@K | [[GitHub]](https://github.com/Exploration-Lab/IL-PCR)[[Evaluation Script]](https://1drv.ms/f/s!AuBOJ2hW9Gimg6J8QRx8t2BXu7k4Bw?e=CIe3SB) |
| SUMM     |          [🔗 In-Abs](https://1drv.ms/f/s!AuBOJ2hW9Gimgbl5s3AOFp54cTR1uQ?e=FcfR25)   | ROUGE-L, BERT-SCORE | [[GitHub]](https://github.com/Law-AI/summarization)[[Evaluation Script]](https://1drv.ms/f/s!AuBOJ2hW9Gimg6J2JD12QUwyQZ7pIQ?e=STAPV8) | 


## Submission
For submitting to the Leaderbaord see the details proivded at [🔗 IL-TUR Leaderboard Page](https://cse.iitk.ac.in/users/ashutoshm/IL-TUR/). 


## License
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
The CISLR dataset follows [CC-BY-NC](CC-BY-NC) license. Thus, users can share and adapt our dataset if they give credit to us and do not use our dataset for any commercial purposes.


