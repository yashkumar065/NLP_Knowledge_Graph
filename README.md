# NLP_Knowledge_Graph

Construction of Knowledge Graph for a website data

1. Although the primary goal is to construct KG for our college website, we tried to create a pipeline for toy data ActorsDataSet which will be preprocessed(Corefence Resolution and removal of unnecessary symbols) and stored in ActorsPreprocessedDataSet.

2. The ActorsPreprocessedDataSet will be used to extract the Named Entities using(NER(Named Entity Recognition) commented code) and Triples would be extracted as SVO(Subject-Verb-Object) which would be used while generating the Knowledge graph.

3. Finally,  we have to make pre-defined rules to process the actual data for Entity Linking phase while constructing the graph.

Once, the primary pipeline is constructed we will focus on scraping the data as no matter how accurate our data is on toy data we have to ultimately work on the website data. The next phase will be extracting the data from the college website and employing the same via our pipeline.

Project paper(on toy data) Link with all the references : uploaded in the Paper folder 

Most of the coding was done on Colab, thus the results are uploaded all at once here in the repository.
