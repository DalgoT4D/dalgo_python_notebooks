### About

- Each root level folder is an experiment and should contain its own dependencies `requirements.txt`

- Create new notebooks if you want to share your work, since figuring out diffs in notebook on git is  not possible

- Do not push any secrets in the notebook

### Setup

1. `cd <experiment_name>`

2. `python -m venv venv`

3. `pip install -r requirements`

4. Open the notebook in vscode. Make sure the kernel is pointing to the env you created above

5. Create `.env` in that folder and update it based on what ever the notebook is using