### Recommender System based on Authors and Articles leveraging open-source LLMs
The objective of this project was to create a recommendation system for authors to be able to access the most similar authors that they could collaborate for future research based on their previous work. 

The authors and articles were converted into embeddings using an open-source LLM built specially for research atricle purposes. The title and abstract of each paper was taken as input. You can find the LLM here : https://huggingface.co/allenai/specter2

The similarity metric used for this analysis was the articles they had published over 20 years from 2002 to 2024. 

I have built a author-author recommendation system and also a graph representation of the authors to visualize their similarity!
