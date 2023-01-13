# mlops

MLFlow
Manage ML model lifecycle

ML tracking - https://mlflow.org/docs/latest/tracking.html  
mlflow.set_tracking_uri() connects to a tracking URI.
mlflow.get_tracking_uri() returns the current tracking URI.
mlflow.create_experiment() creates a new experiment and returns its ID.
mlflow.set_experiment() sets an experiment as active. If the experiment does not exist, creates a new experiment.
mlflow.start_run(), new runs are launched under this experiment.
mlflow.end_run() ends the currently active run
mlflow.log_param() logs a single key-value param in the currently active run. The key and value are both strings. Use mlflow.log_params() to log multiple params at once.

mlflow.log_metric() logs a single key-value metric. The value must always be a number. MLflow remembers the history of values for each metric. Use mlflow.log_metrics() to log multiple metrics at once.

mlflow.set_tag() sets a single key-value tag in the currently active run. The key and value are both strings. Use mlflow.set_tags() to set multiple tags at once.

mlflow.log_artifact() logs a local file or directory as an artifact, optionally taking an artifact_path to place it in within the run’s artifact URI. Run artifacts can be organized into directories, so you can place the artifact in a directory this way.

mlflow.log_artifacts() logs all the files in a given directory as artifacts, again taking an optional artifact_path.

mlflow.get_artifact_uri() returns the URI that artifacts from the current run should be logged to.



ML projects - 

ML models - 

ML registry- centralized repo, version control
