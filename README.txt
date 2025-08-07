# Cipher-Breaker

Classical ciphers, though no longer used for secure communication, remain relevant in Capture the Flag competitions, escape rooms, geocaching, and educational settings. Traditional decryption methods—brute force, frequency analysis, and pattern matching—are often inefficient or fail when the cipher type is unknown or the ciphertext is noisy. 
This project reframes cipher-breaking as a language translation task using Transformer-based models like GPT-4o mini, with exploration into GPT-2 to be run locally.
Looking ahead, our long-term goal is to explore machine learning approaches to modern cryptography, particularly RSA. While breaking RSA is mathematically complex, we aim to investigate whether AI can support factorization and identify patterns
Moreover, this is a fun idea, to see , by using AI, how close we can get to breaking such encryptions that are mathematically so complex, that modern computers just cannot brute force their way in. 

Code Running Instructions:

Classical:
simply execute the main.py file. It contains all the necessary code to execute all others. 
NOTE: We used GPT4o's API (OpenAI Langchain), so might need a premium subscription. Fee free to use any other API. Results may vary

RSA:
Run the Data_create.ipynb file first to create a dataset. Takes <3s. Then Run the rsa.ipynb. No need to train (unless you want to) as finetune.txt is already saved.

Thank you.
