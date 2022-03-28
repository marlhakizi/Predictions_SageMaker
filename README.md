# Predictions_SageMaker

This jupyter notebook is uses AWS SageMaker Linear models algorithms for breast cancer prediction using UCI'S breast cancer diagnostic data set. The jupyter notebook goes through the following steps:

- Basic setup for using SageMaker.
- Converting datasets to protobuf format used by the Amazon SageMaker algorithms and uploading to S3.
- Training SageMaker's linear learner on the data set.
- Hosting the trained model.
- Scoring using the trained model.
