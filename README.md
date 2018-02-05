# Generating Reproducible Report to Compare Different Countries for the Characteristics of Peer Reviewed Articles in Pathology Journals


It is a very common practice to retrospectively analyse the number of peer reviewed articles written from a country to view the amount of contribution made to a specific scientific discipline.


These studies require too much effort, since the data is generally behind paywalls and restrictions.


I have previously contributed to a research to identify the Articles from Turkey Published in Pathology Journals Indexed in International Indexes; which is published here: http://www.turkjpath.org/summary_en.php3?id=1423 DOI: 10.5146/tjpath.2010.01006


This study required manually investigating many excel files, which was time consuming and updating the data and results also require a similar amount of effort.


In order to automatize this analysis, I have used PubMed data from National Library of Medicine (https://www.ncbi.nlm.nih.gov/pubmed/). This collection has the most comprehensive information about peer reviewed articles in medicine. It also has API (https://dataguide.nlm.nih.gov/), and R packages are available for getting and fetching data from the server.
Pathology Journal ISSN List data was retrieved from "in cites Clarivate", and Journal Data Filtered as follows: JCR Year: 2016 Selected Editions: SCIE,SSCI Selected Categories: 'PATHOLOGY' Selected Category Scheme: WoS

Using these data I would like to make reproducible reports and shiny apps, not only on pathology field but also in other areas of medicine. This will be very useful to compare disciplines and different nations.
