# NLP_Knowledge_Graph

Construction of Knowledge Graph for a website data

1. Although the primary goal is to construct KG for our college website, we tried to create a pipeline for toy data ActorsDataSet which will be preprocessed(Coref and removal of unneccasry symbols) and stored in ActorsPreprocessedDataSet.

2. The ActorsPreprocessedDataSet will be used to extract the Named Entities using(NER(Named Entity Recognition) commented code) and Triples would be extracted as SVO(Subject-Verb-Object) which would be used while generating the Knowledge graph.

Once, the primary pipeline is constructed we will focus on scraping the data as no matter how accurate our data is on toy data we have to ultimately work on the website data. The next phase will be extracting the data from the college website and employing the same via our pipeline.

Project paper(toy data) Link with all the references : uploaded in the Paper folder 
