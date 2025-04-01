# Info-CELS: Informative Saliency Map Guided Counterfactual Explanation for Time Series Classification
This is the repository for our work titled "[Informative Saliency Map Guided Counterfactual Explanation for Time Series Classification](https://www.mdpi.com/2079-9292/14/7/1311)" that was published in A special issue (Explainable Artificial Intelligence: Concepts, Techniques, Analytics and Applications) of Electronics (ISSN 2079-9292).

# Prerequisites and Instructions (python 3.8)
All python packages needed are listed in [pip-requirements.txt](pip-requirements.txt) file and can be installed simply using the pip command: pip install -r requirements.txt

# Run an single example in Coffee dataset
python3 main.py --pname A_Coffee --task_id 0 --run_mode single --jobs_per_task 10 --samples_per_task 10 --dataset Coffee --algo cf --seed_value 1 --enable_lr_decay False --background_data train --background_data_perc 100 --enable_seed True --max_itr 1000 --run_id 0 --bbm dnn --enable_tvnorm True --enable_budget True --dataset_type test --l_budget_coeff 1 --run 1 --l_tv_norm_coeff 1 --l_max_coeff 1

# Data
The data used in this project comes from the [UCR](https://www.cs.ucr.edu/~eamonn/time_series_data_2018/) archive.



