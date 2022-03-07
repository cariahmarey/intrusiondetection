# intrusiondetection
R Code to Test Intrusion Detection of Topic Model

1. Load all files from folder "Resources" into your R environment
2. Run function 
tm_word_intrusion() in file word_intrusion
4. Run function tm_topic_intrusion() in file topic_intrusion
5. Open new R file
6. Paste and run: 
tm_word_intrusion(beta = beta_df)
7. In your console, you will see a list of words. Type in the number of the word (the "intruder") that doesn't fit to the other words. This will be repeated 10 times.
8. After the 10 runs, save the performance statistic.
9. Now paste and run: tm_topic_intrusion(beta = beta_df, theta = theta, corpus = textdata_corpus)
10. In your console, you will see 4 lists of words and in your viewer window you will see some text. Select the number of the list that best fits the text of the document. This will be repeated 10 times.
11. After 10 runs, save the performance statistic.
12. Thanks.
