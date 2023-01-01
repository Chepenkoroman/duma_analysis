# Research of Shiftings in the Objects and Themes Discussed During the Sessions of the State Duma of the Russian Federation (1994-2022)

This research project aimed at understanding the shiftings in the objects and themes discussed during the sessions of the State Duma of the Russian Federation over time. To accomplish this, the transcripts of the meetings from 1994 to 2022 were analyzed, considering previous relevant research and compiling a corpus of speeches from these transcripts. A statistical analysis of the texts was conducted and LDA models were created for each year to help understand the changing discussions and priorities in the State Duma. 

In addition to this, the sentiment analysis of each statement was examined using a recurrent neural network with two LSTM layers. The sentiment analysis process involved training the neural network on a labeled dataset of statements and their corresponding sentiments, and also using this trained model to classify the sentiment of the statements in the corpus. This allowed the study understand not only the content of the discussions, but also the emotional tone and the potential impact on the audience.

The data analysis was accompanied by data visualization graphs to help illustrating the findings, and the results of the study present an interpretation of the identified shiftings and attempt to identify their possible causes. By understanding the shiftings in the objects and themes discussed in the State Duma over time this research project provides insights into the changing nature of the discussions and priorities in this important governmental body. It may also help to identify factors that may have contributed to these shifts, such as changes in the political climate or shifts in public opinion. Overall, this research project aims at deepen our understanding of the discussions and decision-making processes within the State Duma and their potential impact on the wider society.



1. The folder with the application code is stored in the repository
https://github.com/Chepenkoroman/duma_analysis/tree/main/code


2. Corpus of filtered speeches with additional information:
https://github.com/Chepenkoroman/duma_analysis/tree/main/data/corpus


3. An example of a graph of the distribution density of speeches on the example of 1994, the rest of the years are stored in the repository folder (kde) https://github.com/Chepenkoroman/duma_analysis/tree/main/kde

 ![page31image22175248](https://user-images.githubusercontent.com/35574101/210173932-39a2b3c6-a347-495a-bba6-f91777795ba1.png)



4. An example of a speaker frequency graph using the example of 1994, the rest of the years are stored in the repository folder (topSpeakers) https://github.com/Chepenkoroman/duma_analysis/tree/main/topSpeakers

 ![page32image22427248](https://user-images.githubusercontent.com/35574101/210173938-eb0c8fb1-d313-41fd-be0a-ca4a03ea6657.png)



5. Matrix of graphs with the chairman on the example of 1994, the rest of the years are stored in the repository folder (matrixWith) https://github.com/Chepenkoroman/duma_analysis/tree/main/matrixWith

![positivo](https://user-images.githubusercontent.com/35574101/210173969-0a9d84a8-3d35-4377-8e6b-a19869b7dbe3.png)

 

6. Matrix without presiding on the example of 1994, the remaining years are stored in the repository folder  (MatrixWithout) https://github.com/Chepenkoroman/duma_analysis/tree/main/MatrixWithout

![text_w_length](https://user-images.githubusercontent.com/35574101/210173979-47125ea4-8e4d-4370-ac05-ac69d2b6a483.png)



7. An example of a graph of the density of speeches per sentiment using the example of 1994, the rest of the years are stored in the repository folder (violinPlot) https://github.com/Chepenkoroman/duma_analysis/tree/main/violinPlot

![Negative](https://user-images.githubusercontent.com/35574101/210173986-b7ed769f-3862-4317-9e8d-7598af67b541.png)



8. An example of a graph of the ratio of speeches to the number of words with a regression line on the example of 1994, the rest of the years are stored in the repository folder (regplot) https://github.com/Chepenkoroman/duma_analysis/tree/main/regplot

![erformances](https://user-images.githubusercontent.com/35574101/210173991-bc9c0ddd-e576-4bc1-8d24-0597b9d687fa.png)



9. An example of a graph of the ratio of the probability of sentiment to the number of speeches on the example of 1994, the rest of the years are stored in the repository folder (positPerf) https://github.com/Chepenkoroman/duma_analysis/tree/main/postPerf

![positive](https://user-images.githubusercontent.com/35574101/210174007-3e930475-31d2-494e-b0e7-bc84d1a7d453.png)



10. An example of a graph of the ratio of the probability of sentiment to the number of words on the example of 1994, the rest of the years are stored in the repository folder (positWords) https://github.com/Chepenkoroman/duma_analysis/tree/main/postWords

![positive](https://user-images.githubusercontent.com/35574101/210174013-3fbe2965-f5ea-4146-a0fc-86bde82b5adb.png)



11. An example of a graph of the ratio of sentiment probability to the number of words (up to 1000 words in a statement) using the example of 1994, the rest of the years are stored in the repository folder (positWords1k) https://github.com/Chepenkoroman/duma_analysis/tree/main/postWords1k

![positive](https://user-images.githubusercontent.com/35574101/210174014-9ceae1b0-5ea6-451b-af89-348cd506c6bb.png)



12. An example of a graph of the ratio of the probability of sentiment to the number of words (up to 500 words in a statement) using the example of 1994, the rest of the years are stored in the repository folder (positWords500) https://github.com/Chepenkoroman/duma_analysis/tree/main/postWords500

![Negative](https://user-images.githubusercontent.com/35574101/210174015-a290e3eb-d0f6-4a81-b168-5ed604ad4c57.png)



13. An example of a graph of the frequency of certain words using the example of 1994, the rest of the years are stored in the repository folder (frequency_png) https://github.com/Chepenkoroman/duma_analysis/tree/main/postWords500frequency_pn g

![page39image22473904](https://user-images.githubusercontent.com/35574101/210174020-645fe59f-5249-4e77-bc63-62770984041a.png)



14. Interactive tone models // https://github.com/Chepenkoroman/duma_analysis/tree/main/lda
