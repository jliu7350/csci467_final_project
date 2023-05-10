# csci467_final_project
Code for final project for CSCI 467: Introduction to Machine Learning.

- To generate results, run the notebooks 1, 2, and 3, in that order. Cells that need to be executed are marked with a comment at the top, saying \# \*EXECUTE\*. Other cells are used to generate graphs (e.g. for the report) or other miscellaneous verification/debugging things.
  - Note that Notebook 1 scrapes a lot of web pages, so it's recommended to either use a VPN or use the dataset I have already provided. This took me a couple hours to run, and may cause errors. If that happens, I just manually merged the dataframes.
  - Notebook 2's code could potentially take a while to run; I did this a long time ago and I recall waiting for multiple hours for it to finish.
  - Notebook 3's code takes about the same amount of time, but requires a GPU. It took me around 4 hours on a RTX 3070 Ti. I have included the weights for the final best model, but keep in mind that running that will take time as well.
- The dataset is from https://www.kaggle.com/datasets/trolukovich/steam-games-complete-dataset, but a downloaded version is stored already as data/steam_games.csv. The code will help you generate the data, but I have also uploaded a copy (dataset_draft.csv) so you can skip notebook 1 and move on to notebook 2.
