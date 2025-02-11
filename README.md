## Transportation Data Science Project (TDSP)
TDSP is an initiative by the Northeast Big Data Innovation Hub (NEBDHub) and the National Student Data Corps (NSDC) in collaboration with the U.S. Department of Transportation. This project analyzes NYC OpenData transportation datasets to assess road safety and develop data-driven recommendations for improvement.
## Setup & Usage
This code was developed in Google Colab and requires mounting Google Drive for data access. If running in Google Colab, no changes are needed.

If running in another IDE (e.g., Jupyter Notebook), replace:

```
from google.colab import drive
drive.mount('/content/drive')
```
with
```
df = pd.read_csv("your_data_path.csv")
```

where `your_data_path.csv` is the local path to your dataset.

## Dataset Information

The dataset used is [NYC OpenData: Motor Vehicle Collisions - Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95).

⚠️ Note: The dataset is continuously updated. The results in this notebook reflect the data as of the time it was run, so values may differ if rerun with the latest data.
