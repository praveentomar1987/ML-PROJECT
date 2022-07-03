## START ML-PROJECT

### SOFTWARE AND ACCOUNTS REQUIRED
1. [Github AACCOUNT](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com.login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [Git Documentation](https://git-scm.com/docs/gittutorial)


creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
or
```
conda activate venv
```
```
pip install -r requirements.txt
```

To add files to git
```
git add .
```

or
```
git add <file_name>
```
> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
```
git status
```
To check all the versions maintained by git
```
git log
```

To create version/commit all changes by  git (in our sysytem)
```
git commit -m "your_message"
```
To send version/changes to github 
```
git push origin main
```
To check remote url
```
git remote -v
```
To check the branch name
```
git branch
```

To setup CI/CD pipeline in heroku we need 3 informations

1. HEROKU_MAIL = ch.praveentomar@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-project-housepricepredict


BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lower case

To list docker images
```
docker images
```
Run docker image
```
docker run -p 5000:5000 -e PORT=5000 e416778c1c5c
```

To check running containers in docker
```
docker ps
```

To stop docker container 
```
docker stop <container_id>
```

