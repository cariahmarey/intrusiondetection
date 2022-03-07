# Intrusion Detection
R Code to Test Intrusion Detection of Topic Model

1. Load all files from folder "Resources" into your R environment
2. Run function 
```
tm_word_intrusion()
```
in file "word_intrusion"

3. Run function 
```
tm_topic_intrusion()
```
in file "topic_intrusion"

4. Open new R file
5. Paste and run:
``` 
tm_word_intrusion(beta = beta_df)
```
6. In your console, you will see a list of words. Type in the number of the word (the "intruder") that doesn't fit to the other words. This will be repeated 10 times.
7. After the 10 runs, save the performance statistic.
8. Now paste and run: 
```
tm_topic_intrusion(beta = beta_df, theta = theta_df, corpus = textdata_corpus)
```
9. In your console, you will see 4 lists of words and in your viewer window you will see some text. Select the number of the list that best fits the text of the document. This will be repeated 10 times.
10. After 10 runs, save the performance statistic.
11. Thanks.
