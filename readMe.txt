Data analysis of the 11th Measuring Broadband America (MBA) Report

Andreas Freund, Internet Real-Time Lab, Columbia University, Department of Computer Science

Overview: 
-The analysis was performed on the MBA's 11th report's validated dataset for fixed-broadband. 
-The validated dataset from the 11th report contains test results for September-October 2020 for a variety of ISPs and throughput tiers. 
-The analysis was performed using BigQuery, Google Cloud Storage, Jupyter Notebooks, and Python
-The analysis and charts in this repository were used in a Reply Comment and presented in two Ex Parte meetings with the FCC as part of the CG Docket No. 22-2: Empowering Broadband Consumers Through Transparency proceeding (cited below).
-The research is ongoing and will be presented as a paper at the TPRC Conference in Washington DC in September, 2022: http://www.tprcweb.com/accepted-papers

Repo Structure: 
1. Download and upload metric analysis for multiple concurrent TCP connections on IPv4
2. Download and upload metric analysis for multiple concurrent TCP connections vs single TCP connection results on IPv4
3. Latency data analysis on IPv4
4. Reliability (ping, DNS resolution, contiguous UDP packet loss) analysis on IPv4
5. Spatial & temporal analysis on selected tiers using 95% consistency speed during peak hours for selected tiers


FCC Reply Comment: 
-https://www.fcc.gov/ecfs/search/search-filings/filing/10325135839677

FCC Reply Comment Addendum: 
-https://www.fcc.gov/ecfs/search/search-filings/filing/1032725547909

FCC Ex Parte Notice 1: 
-https://www.fcc.gov/ecfs/search/search-filings/filing/10411036932837

FCC Ex Parte Notice 2: 
-https://www.fcc.gov/ecfs/search/search-filings/filing/1041895940875

FCC Reply Comment & Ex Parte Authors:
-Henning Schulzrinne, Internet Real-Time Lab, Department of Computer Science, Columbia University
-Walter Johnston, Danu Consulting
-Andreas Freund, Department of Computer Science, Columbia University



11th MBA Report:
-https://www.fcc.gov/reports-research/reports/measuring-broadband-america/measuring-fixed-broadband-eleventh-report	

11th MBA Report Dataset, Unit Profile, Data Dictionary, and Statistical Averages: 
-https://www.fcc.gov/reports-research/reports/measuring-broadband-america/validated-data-measuring-fixed-broadband-0

11th MBA Report Technical Appendix: 
-https://data.fcc.gov/download/measuring-broadband-america/2021/Technical-Appendix-fixed-2021.pdf

11th MBA Report Charts:
-https://www.fcc.gov/reports-research/reports/measuring-broadband-america/charts-measuring-fixed-broadband-eleventh

Acknowledgements: 
-Henning Schulzrinne, Department of Computer Science, Columbia University
-Walter Johnson, Danu Consulting 
-Victor Eyo, Senior Data Analyst, AuditBoard (query structure and optimization) 
