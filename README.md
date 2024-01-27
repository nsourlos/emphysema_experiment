# Emphysema experiment files


[![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)]( https://github.com/nsourlos/emphysema__experiment)


> This repo contains the code needed to perform the emphysema experiment. The title of the paper is 'Effect of emphysema on AI software performance for lung nodule detection compared to a human reader in low-dose chest CT'.

# [Emphysema experiment](/reviewing_info_extract_emphysema.ipynb)

**For this experiment, the file that needs to be executed is the [reviewing_info_extract_emphysema](/reviewing_info_extract_emphysema.ipynb)**

This will also execute [patient_selection_emphysema_experiment](/patient_selection_emphysema_experiment.ipynb). In order for this to work we need the following folders:

- 2 folders named [emphysema_reviewed](/emphysema_reviewed) and [no_emphysema_reviewed](/no_emphysema_reviewed). The emphysema folder should contain 3 subfolders for each emphysema degree (advanced, confluent, moderate). Inside each of those subfolders, as well as in the main [no_emphysema_reviewed](/no_emphysema_reviewed) folder, there should be subfolders named with the participant IDs that were reviewed by a consensus panel of radiologists. In each of those subfolders txt files with the results of that review should exist. An example of such a txt file can be found [here](/emphysema_reviewed/advanced/197239/186fnlastfinal_gray01.txt)
- A [folder](/emphysema_exp_files) with the Excel files of the manual annotations/comparison between REDCap and AI (4 in total, one for each degree of emphysema).
- A [folder](/emph_csv) with the CSV REDCap extractions.

These folders are not provided due to privacy regulations.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

