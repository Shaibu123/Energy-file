Feature Pipeline
Install for Development
Create virtual environment:

cd feature-pipeline
poetry shell
poetry install
Usage for Development
To start the ETL pipeline run:

python -m feature_pipeline.pipeline
To create a new feature view run:

python -m feature_pipeline.feature_view