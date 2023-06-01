# PubScrub
PubScrub: concisely summarizing PubMed abstracts using a webscraper and the openAI api

# Description:
PubScrub is a tool that scrapes and summarizes all abstracts from PubMed that relate to a prompt provided by the user. It starts by scrubbing all article titles, publication years, and abstracts from PubMed, and then hands the abstracts off to the openai api (model: gpt-3.5-turbo) to summarize each in three sentences. Lastly, it combines all titles, years, and “ChatGPT” summarized abstracts into a word document for the user to view. This can be useful if the user wants a collection of concisely summarized abstracts to more easily choose which articles they should prioritize reading more thoroughly.![image](https://github.com/eddin022/PubScrub/assets/67563125/f6741dca-c247-4fec-86ee-e3569ce46f3e)
