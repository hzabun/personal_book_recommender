# Personal book recommender

A single book can drastically change your life.

But finding the next book to read can be very challenging. There are just too many to choose which can lead to option paralysis. At the same time, giving every single book a chance can be quick wasteful in terms of time.

That's why this project aims to create a personal book recommender based on several different algorithms and an LLM built on top of it for more customized recommendations.

The tracking and logging for each algorithm is done via [MLflow](https://github.com/mlflow/mlflow).

## Roadmap

- [x] Finish quick EDA (file: *notebooks/quick_EDA.ipynb*)
- [x] Query ISBNs of missing books (file: *notebooks/query_isbn.ipynb*)
- [x] Process raw files (file: *src/data_processing/process_raw_data.py*)
- [ ] Implement and log first algorithm in MLflow
- [ ] Implement and log remaining algorithms
- [ ] Implement LLM to use algorithms as basis for even more personalized recommendations
- [ ] Set up GUI to chat with LLM
