# Data

The datasets used in this PySpark project are stored separately on **Google Drive** rather than directly inside this GitHub repository.

This is intentional because the project uses data files for hands-on PySpark transformation and cleaning exercises.

## Dataset Location

You can access the data used in this project here:

**Google Drive:**
[https://drive.google.com/drive/folders/1-QisBG_friPbCGWOlaC-aRunr-X6L3eW?usp=drive_link]

The Google Drive folder contains the source data used throughout the PySpark notebooks.

## Data Format

The current project uses **NDJSON (Newline Delimited JSON)** files.

Each line represents an individual record, allowing the files to be loaded directly into a PySpark DataFrame.

## How the Data Is Used

The data contains realistic data-quality issues that are useful for practicing PySpark transformations, including:

* Null values
* Duplicate records
* Unstandardized values
* Inconsistent categorical values
* Records requiring transformation and cleaning

The notebooks in this repository use these files as input and progressively transform the data using PySpark.

## Using the Data Locally

After downloading the required files from Google Drive, place them in the project's `data` directory:

```text
Pyspark_data_transformation/
│
├── data/
│   └── accounts.ndjson
│
├── notebooks/
│   └── ...
│
└── README.md
```

The exact file names and paths used by the notebooks may vary as the project develops.

## Note

The GitHub repository contains the **PySpark transformation work and notebooks**, while the Google Drive folder contains the **source datasets** used by those notebooks.

If you want to reproduce the transformations locally, download the required dataset files from the Google Drive folder before running the notebooks.
