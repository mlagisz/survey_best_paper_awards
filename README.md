# Cross-disciplinary survey of access and assessment criteria of "best paper" awards  

**Our mission statement:** *Making "best paper" awards for young researchers more equitable and open.* 🌟  

  

(If you are reading this on GitHub, you can also see this repository as a webpage [here](https://mlagisz.github.io/survey_best_paper_awards/)🌍).   

## 🔖 Background   
Research awards can propagate existing biases in academia in terms of rewarding novel results rather than robust and transparent research. They can also contribute to the “Matthew Effect” where already privileged groups become rewarded. As such, revealing which awards do/do not provide equitable access and evaluation can lead to systemic change in how publications, especially these by early career researchers, are assessed and recognised.   

## 🏹 Aims and approach  
This project aims to conduct a survey of current practices in awarding “best papers” awards by research journals and other organisations. Such awards are usually given to early career researchers, potentially influencing their futre academic career trajectory. In this project, we will evaluate accessibility, assessment criteria and historical biases in the lists of past awardees. Evaluation will be performed on a sample of awards from most respected journals and organisations across disciplines. Our findings will be openly available and disseminated in the research community.      

## 🪓 Impact  
We expect that our findings will contribute to culture change fostering more equitable and open science.    

## 💛 Contributing  
We invited early- and mid-career researchers across disciplines to contribute to the project. The project is almost completed and we do not accept new contributors for now, but you are welcome to join our future projects!      

Overall, when you work with us:   
- We welcome researchers with all backgrounds and walks of life o contribute to any Stage of this project (see below).   
- You do not need any speciall research skills - just attention to detail, Internet access and some time available.   
- Fill in the Expression Of Interest (EOI) form at: [https://forms.gle/J3WPWMTAyWJy3k1v9](https://forms.gle/J3WPWMTAyWJy3k1v9)
- We already had in-person and virual hackathons (information and feedback meetings) in November/December 2022, but we can schedule mor virtual meetings if you feel like you would like to chat with the leaders or other project participants. Send your suggestions!  
- We can do all the work asynchroniously online until we complete all Stages of the project (see below).    
- For more details on how to contribute and how we deal with recognising everybodys' contributions see our [CONTRIBUTION GUIDE](/CONTRIBUTING.md).  
- We expect all project contributors to familiarise themselves and follow our [CODE OF CONDUCT](/CODE_OF_CONDUCT.md).   
- If you would like to comment on this project or provide suggestions to improve it, feel free to open an issue on GitHub or reach directly to us via a dedicated Slack channel (invites will be sent to  project participants who filled in the EOI form: [https://forms.gle/J3WPWMTAyWJy3k1v9](https://forms.gle/J3WPWMTAyWJy3k1v9) or via email (losialagisz@gmail.com).  

## 🗺️ Roadmap   
The project has main 4 Stages:  

### Stage 1: Planning   
- Preparing protocol.  
- Piloting.  
- Registration.  
- Feedback on the protocol (we are currently here!).   
- Hackathon preparation.   

### Stage 2: Screening   
- Screening journal lists from 27 Scimago Subject Areas rankings.   
- Creating award shortlists.   
- Checking shortlists.  

### Stage 3: Data extraction  
- Main data extraction for included awards.   
- Collecting additional data on past winners.    
- Data cross-checking.   
- Preliminary analyses.    

### Stage 4: Analyses and writing   
- Final analyses.   
- Draft report.  
- Contributors feedback.   
- Final report.  
- Sharing data and code in a GitHub repository.  
- Preprint in [BioRxiv](https://www.biorxiv.org/content/10.1101/2023.12.11.571170v1).    
- Manuscript.  
- Published in a journal.


## 🚉 Current status    
Stage 4: Manuscript.    


## 🚀 Protocol   
Final protocol is publicly archived on OSF at [https://osf.io/93256](https://osf.io/93256).    

## 🚚 Supporting information 
Supporting information, including all code, is available [here](/R/SI_methods_results.html).  

## 💻 Data and code files      
This repository hosts a copy of our final data and code files.   

Data:     
 - *BP_awards_lists_SHAREDCOPY - indiv_winners_20230915.csv* - data on the extracted characteristics of past individual award winners (focus on gender, and country of affiliation). Meta-data is provided in a separated .csv file.  
 - *BP_awards_lists_SHAREDCOPY - indiv_winners_meta-data.csv* - meta-data file for the data on individual winners (BP_awards_lists_SHAREDCOPY - indiv_winners_20230915.csv).  
 - *BP_awards_lists_SHAREDCOPY - people_tasks log.csv* - record of the researcher contributions to the project. First columns includes researcher names and the last two columns show the authorship order and position, respectively. Numerical columns with "(SA)" in the name represent counts of Subject Areas researcher contributed to, e.g., by screening or extracting award data. All other numerical columns are binary variables, where 1 stands for "yes" (i.e., "contributed""), and 0 stands for "no" (i.e., "not contributed").   
 - *BP_awards_lists_SHAREDCOPY - scimagojr_2021_SA.csv* - list of 27 SCImago Subject Areas (SA) with progress and contributions records. The records include dates and names of contributors for different stages of the project workflow.   
 - *duplicated_main_extractions.csv* - a subset of extracted award characteristics where data was extracted by at least two independent researchers. Meta-data is the same as for the main dataset provided in the file Survey-Best_paper_awards (Responses)_SHAREDCOPY_checked.xlsx.  
 - *scimagojr 2021  Subject Areas_screening.xlsx* - lists of journals for each of 27 SCImago Subject Areas (SA) with associated SCimago 2021 data and records of screening decisions and comments. Each SA is provided in a separate Excel tab, with the first tab providing meta-data.    
 - *scimagojr country rank 2021.csv* - SCImago Country Rank data for 2021 downloaded from https://www.scimagojr.com/countryrank.php. The list of 235 countries with their data on: SCImago Rank, Country	Region,	Documents, 	Citable documents,	Citations,	Self-citations,	Citations per document,	H-index. For information on the SCImago data sources see https://www.scimagojr.com/help.php?q=FAQ.    
 - *Survey-Best_paper_awards (Responses)_SHAREDCOPY_checked.xlsx* - raw data extracted via Google Form and saved as a spreadsheet. The extracted data has been cross-checked and supplemented with comments, corrections and final inclusion decisions. Meta-data is provided in the second tab of the file.    


R Code:   
 - *SI_methods_results.Rmd* - R code and markdown file with all analyses and visualisations.   
 - *SI_methods_results.html* - knitted code and results html file for the website.   

The archived award descriptions are publicly available in a dedicated [OSF repo](https://osf.io/yzr7a/). Individual pdf files are compressed into a single file (awards_pages_pdf.zip) there.   

## ⏰ Code of Conduct   
We expect all project contributors to familiarise themselves and follow our [CODE OF CONDUCT](/CODE_OF_CONDUCT.md).      

## 🔧 Maintainer(s)
* [Losia Lagisz](https://github.com/mlagisz).   

## 🖍️ License 
This work is licensed under a [Creative Commons Attribution 4.0 International License (cc-by)](/LICENSE.md).   
