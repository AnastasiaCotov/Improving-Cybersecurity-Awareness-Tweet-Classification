# Improving-Cybersecurity-Awareness-Tweet-Classification
Improving Cybersecurity Awareness: Tweet Classification using Multilingual Sentence Embeddings and Contextual Features

The three datasets described in the paper: Improving Cybersecurity Awareness: Tweet Classification using Multilingual Sentence Embeddings and Contextual Features

	  Dataset I: The CVE identification numbers (file CVEs.xlsx) - used as cybersecurity-related posts
   
	  Dataset II: Training and Test Set (files: u2v_train.xlsx, u2v_test.xlsx)
   
 	  Dataset III: The CVEs ids and their type (file cve_by_type.xlsx); additional threats types malware, spam and ransomware (file: datasetIII_additional_lb.xlsx)


The presence of accounts managed by cybersecurity experts, professionals, and organizations makes social media a valuable source for computer security awareness. By regularly capturing and analyzing the posts on emerging cyber threats, individuals and organizations can timely understand potential dangers and effectively implement mitigation strategies. However, retrieving relevant and informative posts from a social network is challenging due to the high percentage of posts containing uninformative content. This paper proposes a novel approach based on supervised classifiers for selecting relevant social media posts and categorizing them according to different types of vulnerabilities. 

To accomplish this task, we designed a pipeline combining text classifiers in cascade, training them on manually labelled data. %With active learning, we optimized the labelling process, reducing manual effort while enhancing the accuracy of the classification model. 

We conducted an analysis of different neural network techniques, leveraging language-agnostic sentence-level embeddings and data related to past user activity. 
The validation of such techniques and hyperparameter tuning were performed in a cross-validation setup.
With an achieved accuracy of 87\%, our approach offers effective filtering and classification of social media posts, empowering cybersecurity professionals to stay informed and take appropriate measures.
