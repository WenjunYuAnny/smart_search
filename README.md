# Smart Search: Image-text Multimodal for Large Image Archives
The project is to develop an efficient search function for large loads of image data. The user is able to input keywords and retrieve images that include related content to the keywords in real time. The project focuses on cross-modal retrieval and utilizes distributed computing for efficiency and scalability.  
## Architecture
![image](https://github.com/user-attachments/assets/2da6135c-52de-43e2-9eff-8569fc967254)  
- Model for embedding images and search prompt texts: CLIP
- Distributed computing for scalability: Dask
- Vector dababase and vector retrieval: ChromaDB

Image dataset source: Flickr Image Dataset. https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset
