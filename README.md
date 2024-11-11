## PySpark Data Processing - week10_PySpark_zihan
[![CI](https://github.com/zihanxiao23/week10_PySpark_zihan/actions/workflows/cicd.yml/badge.svg)](https://github.com/zihanxiao23/week10_PySpark_zihan/actions/workflows/cicd.yml)  
This project utilizes PySpark for data processing on a large dataset, with a focus on applying Spark SQL queries and performing data transformations. The dataset is sourced from fivethirtyeight and contains information about the guests of *The Daily Show*.

### Setup:

1. Open Codespaces environment.
2. Wait for the environment to finish installing.
3. Run the command: `python main.py`
4. View the results in the [PySpark Output Data/Summary File](pyspark_output.md)

### Code Formatting & Checks:

1. Format the code: `make format`
2. Lint the code: `make lint`
3. Run tests: `make test`

### Data Processing Workflow:

1. First, I extract the dataset using the `extract` function.
2. Then, I start a Spark session with `start_spark`.
3. I load the dataset using `load_data`.
4. Next, I compute and display descriptive statistics via the `describe` function.
5. I execute a query on the dataset using `query`.
6. I apply further transformations on the sample dataset using `example_transform`.
7. Finally, I end the Spark session with `end_spark`.

## Data Source
2. https://github.com/fivethirtyeight/data/tree/master/daily-show-guests
