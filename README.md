# Lab: Misc. data analytics tools

We will be exploring [`Polars`](https://www.pola.rs/), [`DuckDB`](https://duckdb.org/) and [`RAPIDS`](https://rapids.ai/). These tools represent somewhat of a shift from horizontal scaling to vertical scaling i.e. relying on the improvements in the underlying compute and also making better use of that compute.

Note: remember you need to be on the **Saxanet** wifi if you are on campus.

## Activity 1: NYC Taxi dataset analysis using Polars

In this lab we will do some analysis the famous [NYC TLC](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) dataset using Python Polars. 

1. We will start by doing some analysis using Pandas and then compare the time taken to do the same analysis using Polars.

1. We will follow it up with an exercise to find anomalies in the dataset using Polars.

## Activity 2: NYC Taxi dataset analysis using DuckDB

In this lab we will do some analysis the famous [NYC TLC](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) dataset using Python Polars. 

1. We will start by doing some analysis using Pandas and then compare the time taken to do the same analysis using DuckdB.

1. We will follow it up with an exercise to find the most frequent pickup and dropoff locations using DuckDB.

## Activity 3: `RAPIDS`, left as an exercise for the curious student [OPTIONAL]

Watch the video for setting up an Amazon SageMaker Notebook ([link](https://georgetown.instructure.com/courses/172712/discussion_topics/1135473)) and create a SageMaker Notebook with an `ml.g4dn.xlarge` instance type and `100 GB` disk space. Open Jupyter Lab and then a new terminal and create a new conda environment using the following command `conda create--solver=libmamba -n rapids-24.02 -c rapidsai -c conda-forge -c nvidia rapids=24.02 python=3.9 cuda-version=12.0 dask-sql jupyterlab`. Creating this conda environment usually takes 15 to 20 minutes. Now run the [`RAPIDS`](rapids.ipynb) notebook. This activity is optional, to be done by interested students on their own time, there is nothing to submit for this activity.

## Submitting the Activity

Make sure you commit and push your repository to GitHub!

The files to be committed and pushed to the repository for this lab are:
* `polars.ipynb`
* `ducdkb.ipynb`
* `polars_12month_count.csv`
* `polars_12month_daily_averages.csv`
* `polars_12months_fareamount_anomalies.csv`
* `duckdb_nyc_frequent_pickup_dropoff_pairs.csv`

- Submit a final commit message called "final-submission" to your repo. This is critical so that instructional team can evaluate your work. Do not change your GitHub repo after submitting the "final-submission" commit message.
