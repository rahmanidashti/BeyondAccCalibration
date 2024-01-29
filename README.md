# ‌Personalised Beyond-accuracy Calibration in Recommendation

## Dataset Preprocessing Pipeline

1. Downloading datasets raw files (`datasets/DatasetName/raw`)

2. Collecting required features and mapping IDs to range `0` - `N` (the number of users or items). To do this we provide each dataset a specific notebook (`datasets/DatasetName/DatasetName_dataset.ipynb`)

    - __Output_Files_1__: `DatasetName/raw/ratings.csv` and `DatasetName/raw/poi.csv`

    - __Output_Files_2__:: Here we create two file, one for the `rating` data which show a user's rating on an item, and another one is `cat` file. The `cat` file indicate the category of each item (`datasets/DatasetName/raw/DatasetName_data_map.txt` and `datasets/DatasetName/raw/DatasetName_cat_map.txt`)

3. `category_checker.ipynb`:

4. `dataset.ipynb`:

    - `datasets/DatasetName/DS_NAME_data.txt`
    - `datasets/DatasetName/DS_NAME_cat.txt`
    
5. `GoogleDrive/0_dataset_in_use.ipnb`:

    1. `datasets/DatasetName/DS_Name_Train`
    2. `datasets/DatasetName/DS_Name_Test`
    3. `datasets/DatasetName/DS_Name_Category`

## Datasets
- ClothingFit: 5-core
- MovieLens1M: 10-core
- Yelp

# Note
Will be update upon the acceptance of the paper.
