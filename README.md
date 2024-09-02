### Recommender System based on Authors and Articles leveraging open-source LLMs

### Problem Statement: 
In the academic and research community, identifying potential collaborators with similar research interests is crucial for fostering innovation and advancing knowledge. However, the process of finding suitable co-authors based on prior work can be time-consuming and inefficient, particularly when dealing with a vast body of literature. The objective of this project was to create a recommendation system that allows authors to easily discover and connect with other researchers whose work closely aligns with theirs, thereby facilitating meaningful collaborations for future research.

### Solution Overview:
To solve this problem, I developed an author-author recommendation system that leverages the power of embeddings generated from research articles. Using an open-source LLM specifically designed for research purposes, known as SPECTER2, I converted the titles and abstracts of articles into high-dimensional embeddings that capture the essence of the authors' research focus. The dataset consisted of published articles spanning over two decades, from 2002 to 2024, providing a comprehensive view of each author's contributions.

The similarity between authors was calculated using the cosine similarity of their respective embeddings, enabling the identification of researchers with closely aligned interests. In addition to the recommendation system, I created a graph representation of the authors, which visually maps out their similarities, making it easier to identify potential collaborators. This system not only streamlines the process of finding co-authors but also enhances the visibility of relevant research work within the academic community.


<img width="808" alt="Screenshot 2024-08-30 at 2 02 27 AM" src="https://github.com/user-attachments/assets/61fbbada-93ca-4a33-9daa-7d04d35d575d">
