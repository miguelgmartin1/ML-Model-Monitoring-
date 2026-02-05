# Multimodal RAG System using AWS Bedrock and FAISS
This project aims to design and implement a Multimodal Retrieval-Augmented
Generation (RAG) system for a restaurant aggregator app, enhancing its capability to
deliver precise food recommendations tailored to individual preferences and dietary
needs. The system will integrate and process multiple data types—textual descriptions
and visual content—from restaurants to generate personalized suggestions. Utilizing
technologies such as Amazon S3 for data storage, Amazon Bedrock for image
summarization, and FAISS for efficient similarity search, the system will encode and
retrieve vectorized data representations. A user interface powered by Streamlit will
facilitate interactive and user-friendly querying, ultimately leading to dynamic and
context-aware recommendation generation.

Data Description
The dataset comprises a CSV file containing detailed information on menu items from
various restaurants, including identifiers, names, cuisine types, nutritional values,
dietary warnings, vegetarian status, image paths, ratings, serves, and prices.
Additionally, there is a corresponding folder of images for each menu item, enhancing
the multimodal aspect of the data for analysis and recommendation system training.
Tech Stack
➔ Language: Python 3.10.4
➔ Libraries: boto3, awscli, pandas, langchain, langchain-community, faiss-cpu,
streamlit, streamlit-chat
➔ Model: Claude-Sonnet Multimodal Model, AWS Titan Embeddings from AWS
Bedrock
➔ Cloud Platform: Amazon Web Services (AWS)
