# Install UV runner once
pip install uv
# Enhance project for Agent Engine
uvx agent-starter-pack enhance --adk -d agent_engine
# Connect your GCP project
gcloud auth application-default login
gcloud config set project YOUR_PROJECT_ID
# Provision and deploy
make backend