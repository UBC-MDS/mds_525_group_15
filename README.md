# Predicting daily rainfall in Australia

The goal of this project is working with big data. In particular, we will build and deploy ensemble machine learning models in the cloud to predict daily rainfall in Australia on a large dataset (~6 GB), where features are outputs of different climate models, and the target is the actual rainfall observation.

## Milestone 1 discussion

1. Discuss any challenges or difficulties you faced when dealing with this large amount of data on your laptops. Briefly explain your approach to overcome the challenges or reasons why you could not overcome them.

The biggest challenge was the high time-consuming process to run the entire code. This database is quite huge and our personal computers took a long time to process the code chunks. We couldn't avoid this type of problem since we weren't using online tools for big data and we couldn't improve our computers due to the high cost of powerful machines to run this size of data. We need to wait for each code chunk to run, and some of them took more than 15 minutes to run. It goes to show that it is quite complex to deal with big data on the personal computer since any changes in the process or any updates would cost a lot of time to be accomplished.

2. Comparisons for the time taken to combine data CSVs and loading the combined CSV to memory to perform EDA

| Team Member | Operating System              | RAM   | Processor      | Is SSD | Time taken - Combining data CSVs (CPU time / Wall time) | Time taken - EDA (CPU time / Wall time) |
|-------------|-------------------------------|-------|----------------|--------|:--------------------------------------------------------:|:-----------------------------------------:| 
| Josh        | macOS Big Sur Version 11.5.2  | 8GB   | Apple M1       | TRUE   | 6min 59s / 7min 12s                                     | 3min 43s / 3min 49s                     | 
| Aldo        | Windows 10 version 10.0       | 16GB  | intel core i-7 | TRUE   | 8min 29s / 8min 31s                                     | 5min 2s / 5min 36s                     | 
| Arijeet      | macOS Big Sur Version 11.6    | 8GB   | Apple M1       | TRUE   | 9min 19s / 9min 26s                                     | 3min 37s /  3min 57s                     | 

From the table above we can conclude that the time taken to combine the csv files is high in comparison with EDA and also any other step that we observed during the entire process. There is a difference in CPU time and wall time. Wall time measures how much time has passed as if you were looking at the clock on your wall. CPU time is how many seconds the CPU was busy and for both measures, the time taken to combine data CSVs is large and any updates or changes in this step would be a time-consuming process. Generally speaking, we also observe that macOS with Apple M1 performed better than Windows with intel i-7 for both combining CSVs and EDA.

You can check further information about the code in the `notebooks/milestone1.ipynb` file within this repository.
