# Identifying Real Code Authors over Time: An Empirical Study

## Project summary

Identifying code authors is important in various research topics, and various approaches (e.g., [1]) have been proposed. 
Although these approaches achieve promising results on their datasets, their true effectiveness is still in question. 
To the best of our knowledge, only one large-scale study (e.g., [2]) was conducted to explore the impacts of factors (e.g., the temporal effect and the distributions of files per author).
Although their research questions are interesting, we have low confidence on their answers, since their settings have flaws. 
To improve our understanding on this research problem, we evaluated their approach on more realistic settings. 


In this study, we conduct an empirical study to explore the time effect and the impacts of author distributions. We select the state-of-the-art approach [3] as our subject, but we introduce more carefully designed projects. While the prior study [3] mainly uses Google Code Jam programs, we collected real
source files from 5 Apache projects, and our dataset contains 14,657 commits over twenty years.


Our dataset is stored in the dataset file.



## Reference
[1] Aylin Caliskan-Islam, Richard Harang, Andrew Liu, Arvind Narayanan, Clare Voss, Fabian Yamaguchi, and Rachel Greenstadt. 2015. De-anonymizing programmers via code stylometry. In Proc. USENIX Security. 255¨C270.

[2] M. Abuhamad, T. AbuHmed, A. Mohaisen, and D. Nyang. Large-scale and language-oblivious code authorship identification. In Proc. CCS, pages 101–114, 2018.

[3] M. Abuhamad, T. Abuhmed, D. Nyang, and D. Mohaisen. Multi-𝜒: Identifying multiple authors from source code files. In Proc. PETS, pages 25–41, 2020.
