---
title: "OPTIMAL-EM Software Tool"
excerpt: "A software tool designed to optimise the web accessibility evaluation process through representative pages.<br/><img src='/images/portfolio/portfolio-5.png'>"
collection: portfolio
---

The OPTIMAL-EM tool supports a research framework initially outlined in [this short paper](https://doi.org/10.1145/3493612.3520452). The algorithm is outlined in [this WWW '23 paper](https://doi.org/10.1145/3543507.3583508). 

An overview of the OPTIMAL-EM Software Tool is provided in [this W4A Accessibility Challenge paper](https://doi.org/10.1145/3587281.3587962). 

The software is designed to optimise the web accessibility evaluation process through representative pages. Web accessibility evaluation is often performed through a combination of user evaluation and automated tools, and is supported by methodologies such as the Web Content Accessibility Guidelines (WCAG) and the Website Accessibility Conformance Evaluation Methodology (WCAG-EM). Whilst there is prior art for automated and manual accessibility evaluation, page selection is based on heuristics and understanding, meaning that pages are generally selected on an ad-hoc basis. The OPTIMAL-EM tool aims to address this whilst optimising the web accessibility evaluation process by providing auditors with pages that have been statistically analysed and systematically selected. This will reduce the risk of discrepancies in the results and lower the human cost of the evaluation.

![Picture: A diagram of the OPTIMAL-EM software tool.](/images/portfolio/portfolio-5.png)

The OPTIMAL-EM Software Tool is conceptually split into three stages. In the first stage, web pages are sourced and downloaded, processed and clusters are produced. More specifically, the tool will: 
1. Source pages. This may be from a log file, through crawling, or an alternative approach such as the Common Crawl. 
2. Download pages. Alternatively, a predownloaded population of .HTML pages may be inputted into the tool. 
3. Process pages using BeautifulSoup.
4. Create a Vector-Space Model (VSM) using CountVectorizer. 
5. Cluster using DBSCAN.

Then, the software calculates the complexity and cluster variance, before determining a sample size and generating a report. 