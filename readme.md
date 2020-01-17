# Social Network Analysis Term Project
------------------------------------------------------------

This paper introduces an experimental study on social network analysis and an approach that combines the graph analysis and machine learning implementations. We show how the graph embedding are useful to analyze and find relations between nodes in the networks via Node2Vec approach. To test the method, we performed several machine learning algorithms over the data gathered from Internet Movie Database (IMDb). Node2Vec was used to have embeddings of nodes and this is used in the models as feature set to predict collaboration between the actors and directors. The best model that is a logistic regression model is resulted in the ROC AUC score of 0.958, precision of 0.954 and recall of 0.956. As a result of the study, it is seen that the actors and directors that worked together in the past, tend to work together again. 

#### Keywords: 
Link Prediction, Social Network Analysis, Internet Movie Database, Machine Learning 1


#### Topic: 
IMDB Movie Cast and Producers Prediction by Node2Vec


In the project, you will see mainly 2 folders:
#### - Paper PDF
#### - Codes as Jupyter Notebooks
	a - TMDB_Collecting.ipynb:
	
		This notebook includes the code for The Movie DB API. However, we didn't use this notebook, since IMDb dataset has more edges, and more clear data. 
	
	b - SNA_Project.ipynb:
	
		This notebook includes all codes to collect the IMDb dataset and editing of the data by Node2Vec. You can get node embedding and edge embedding. Also, similarities between nodes.

	c - Apply_Models.ipynb:
	
		You can see the models that we apply to model to be able to predict future edges.
	
	d - Edit_Embeddings.ipynb:
	
		You can see how to edit embeddings.

@Mahsun_ALTIN [mail](mahsunaltin98@gmail.com)
@Serkan_KIDIR [mail](serkan.kidir@agu.edu.tr)
@Abdullah_Enes_CAN [mail](abdullahenes.can@agu.edu.tr)
