1. Load the Cluster Modules (Prerequisites)

module load python/3.10 scipy-stack opencv

2. Create and Activate your Environment

python -m venv ~/yolo_env
source ~/yolo_env/bin/activate

3. Install the specific requirements

pip install --no-index --upgrade pip
pip install --no-index -r requirements.txt