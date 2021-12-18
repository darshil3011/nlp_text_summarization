# Automatic Abstractive Text summarization

Text summarization means converting long paragraphs or even pages into a short peice of text. Apps like Inshorts summarize long news stories into a 60 word small articles. AI can understand long chunks of text and convert it into an excerpt. 

In this repo, I have used huggingface T5 transformers and trained it with news article dataset. You can download the dataset from the link given below. The only reason to use pretrained models is because they are trained with millions of pages of text corpus which is very difficult for us to get and train with limited computational resources. 

# How to use this repo

1. You can just replace the dataset in the given notebook with your dataset
2. Keep only two columns - text and summary. Drop all other columns
3. Run the below cells as it is given
4. Hardly training your model for 2-3 epochs will give you relevant results
5. Remember the model will summarize based on your data. For instance, If you train it with news articles, it will summarize in the form of news headlines. If you train it with arxiv research paper dataset, it will summarize in the form of research paper titles. So make sure to use relevant dataset as per your requirement.

Dataset link: https://www.kaggle.com/sunnysai12345/news-summary

Refer to my medium blogs to study more exciting stuffs related to AI - https://thinkinbytes.medium.com/
