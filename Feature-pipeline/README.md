Create virtual environment:

cd feature-pipeline
poetry shell
poetry install

To start the ETL pipeline run:

python -m feature_pipeline.pipeline
To create a new feature view run:

python -m feature_pipeline.feature_view
