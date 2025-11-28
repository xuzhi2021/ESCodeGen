![Literature_Review_Overview](figures/Figure2_literature_review_overview.png)



## Files in folder **"Appendix1-Literature-Review"** are materials about the literature review:



**appendix - general search list.csv:** 100 papers from Cross-disciplinary General Literature Search. If you filter out those with excluded=1, you will get 55 candidate papers. If you check those with selected=1, you will get 45 relevant papers. We also put the related dimensions and phases for the 45 selected paper so that you can check where each dimension first appeared. Among the 100 papers, we found that after reading the top 51 papers, no new dimensions emerged.




**appendix - relevant paper 45 (general).csv:** 45 relevant papers from Cross-disciplinary General Literature Search. It contains labeled domains, dimensions, and relevant phases indicating the dimensions. 



**appendix - specific search list.csv:** 194 papers from Domain-Specific Literature Search. If you filter out those with excluded=1, you will get 136 candidate papers. If you check those with selected=1, you will get 17 relevant papers where we snowballed on.



**appendix - snowball backward (after searching).csv:** 258 papers got by searching keywords on 1037 candidate papers from backward snowballing. If you filter out those with excluded=1, you will get 160 candidate papers. If you check those with selected=1, you will get 8 relevant papers. It also contains a column "snowballing source title" indicating where each paper is snowballed from.



**appendix - snowball backward (after searching).csv:** 251 papers got by searching keywords on 7056 candidate papers from forward snowballing. If you filter out those with excluded=1, you will get 132 candidate papers. If you check those with selected=1, you will get 1 relevant paper. It also contains a column "snowballing source title" indicating where each paper is snowballed from.



**appendix - relevant paper 26 (specific).csv:** 26 relevant papers from 17 (specific search) + 8 (backward snowballing) + 1 (forward snowballing). It contains labeled dimensions, and relevant phases indicating the dimensions. 



**appendix - taxonomy and citations.csv:** complete list of references for each aspect under the dimensions. We also added a column ``first appeared in which general paper''.


**appendix - SEGRESS checklist.csv:** According to a reviewer's comment, we considered aligning our work with the highly influential PRISMA 2020 guideline [R1]. However, as noted by SEGRESS [R2], PRISMA 2020 is for quantitative systematic reviews, rather than mapping studies or qualitative reviews. Therefore, we filled TABLE 9
SEGRESS: The PRISMA 2020-Inspired Structured Checklist for Reporting SE Secondary Studies [R2] instead.


## **"survey (anonymized for review).pdf"**: 


The complete survey we sent to participants.




## Files in folder **"Appendix2-Survey"** are materials about the survey results:



**appendix2 - survey results.csv:** The complete and valid 32 survey responses.



**appendix2 - open-ended questions.csv:** The answers for 6 open-ended questions and our labels.



**appendix2 - relevance.csv:** The data for Figure 3 (Relevance of Dimension in Defining ES-CodeGen) in the paper.



**appendix2 - stages and artifacts.csv:** The data for Figure 4 (Dimensions and their applicable stages) and Figure 5 (Dimensions and their applicable artifacts) in the paper. Note that in the figure, we proportionally scale responses so that the selected options in each row sum to 100%. However, the data provided here are unscaled: each cell shows the percentage of participants who selected that specific stage (or artifact) for the corresponding dimension.



**appendix2 - acceptable trade-offs.csv:** The specific analytic data for Figure 6 (To what extent trade-offs are considered acceptable) in the paper.



**appendix2 - post-survey data.csv:** The analytic data for post-survey questions (whether the survey improved their understanding of ES-CODEGEN, whether the survey made them feel that the ethical sourcing issues are more important, generalizability of our definition(dimensions), and the dimensions they tended to ignore).



## **"figures" folder:**
Contains Figures 1 to 4 shown in our paper. Figure 2 shown above is the workflow of our literature review.




## Notes:
### **Exclusion Criteria for the Literature Review**:
1. Papers that are either not in English or not published in scholarly journals or conferences (This process is marked as “Exclude” in the workflow)

2. Irrelevant papers that: (This process is marked as as “Select” in the workflow):

    a. only reflect on the keywords in sections like “Discussion” or “Related Work” instead of discussing the keyword itself

    b. superficially mention the keywords, but do not focus on ethical sourcing issues
    

### **Inclusion Criteria for the Literature Review**:
1. Papers that are in English and already published in scholarly journals or conferences
2. Papers that are relevant to our topic


For the Cross-disciplinary General Literature Search, the keyword set used for excluding irrelevant papers is key1. 
For the Domain-Specific Literature Search, we used all three sets of keywords (key1, key2, and key3) for excluding irrelevant papers.

**key1 (synonyms of "ethically sourced")**: ethically sourced, ethical sourcing, ethically acquired, ethically procured, ethical acquisition, responsible sourcing, responsibly sourced, sustainable sourcing


**key2 (synonyms of "artificial intelligence")**: LLM, AI, artificial intelligence, LLMs, large language models

**key3 (synonyms of "code generation")**: code generation, code creation, generate code, code writing, code production, code correction, code quality

### Competing Interests

No conflicts.


## References

[R1] Page, M. J., McKenzie, J. E., Bossuyt, P. M., Boutron, I., Hoffmann, T. C., Mulrow, C. D., ... & Moher, D. (2021). The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. bmj, 372.

[R2] Kitchenham, B., Madeyski, L., & Budgen, D. (2022). SEGRESS: Software engineering guidelines for reporting secondary studies. IEEE Transactions on Software Engineering, 49(3), 1273-1298.
