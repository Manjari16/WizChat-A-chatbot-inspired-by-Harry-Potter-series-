# WizChat-A-chatbot-inspired-by-Harry-Potter-series-
WizChat answers all your queries about any of the 930 characters in the Harry Potter series

It was created using open source HuggingFaceEmbeddings, Facebook AI similarity search (FAISS), and LLM model ‘google/flan-t5-large’. It's not as good as OpenAI, but I wanted to make the project with open source packages.

Scraped tabulated data is available in [ChatBoxInfo_df](ChatBoxInfo_df.csv). Scraping took time (about 2-3 hours) so you can directly get started with this csv file.

If you want processed dataframe refer to [ProcessedDataForChatBot.csv](ProcessedDataForChatBot.csv).

[WizChat](WizChar.ipynb) uses FAISS (Facebook AI similarity search). The embedding process took time since the text was large, so I made to [Embeddings](Embeddings.csv) which you can directly import and skip steps.
