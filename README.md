# similarity_search_chroma
Small exercise to try ChromaDB similarity search

## Task 1: Set up a Chroma DB environment
On the main menu, select the Terminal tab and then select New Terminal.

Now open a new terminal and install chromadb in the environment to work with the Chroma DB vector database. Execute the following command in the terminal window and press Enter.

pip install chromadb==1.0.12

Then install one more dependency by executing the following command in the same terminal window where you installed the previous dependency.

pip install sentence-transformers==4.1.0

Note: Do not close the terminal where Docker is running.

## Task 2: Check the output
Next, check the output so that you can verify that the display shows the most similar items or data in the text array.

If the terminal window is not already open, open the terminal window. Then type or enter the following command and press Enter.

python3.11 similarity_search.py
