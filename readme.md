--- After initial clone, run

py -3 -m venv .venv
.venv\scripts\activate
pip install -r requirements.txt

--- To start local virtual environment

flask run


--- To commit changes

git status (check status)
git add . (all files)
git commit -m "COMMENT HERE" (provide relevant comment for commit)
git push

--- To deploy web app to Azure

1. Make sure that the config file within the .azure folder has the correct information
2. Run the command az webapp up
