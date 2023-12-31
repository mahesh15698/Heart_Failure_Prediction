# Heart_Failure_Prediction
1. [Review more technical details in EDA.ipynb file?](https://github.com/mahesh15698/Heart_Failure_Prediction/blob/main/EDA.ipynb)
2. [Find Detailed Presentation](https://github.com/mahesh15698/Heart_Failure_Prediction/tree/main/PPT)

 
![Heart Failure](https://github.com/mahesh15698/Heart_Failure_Prediction/blob/main/Heart_Failure/Slide1.JPG)


![Problem Statement](https://github.com/mahesh15698/Heart_Failure_Prediction/blob/main/Heart_Failure/Slide3.JPG)

![Data Description](https://github.com/mahesh15698/Heart_Failure_Prediction/blob/main/Heart_Failure/Slide4.JPG)
## Appendix:

1. [What is Data Scaling?](https://towardsdatascience.com/all-about-feature-scaling-bcc0ad75cb35)
2. [What is Feature Engineering and Feature Selection?](https://scikit-learn.org/stable/modules/feature_selection.html)
3. [What is Random Forest?](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)















### Software and account Requirement.

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/download)
3. [GIT cli](https://git-scm.com/downloads)
4. [GIT Documentation](https://git-scm.com/docs/gittutorial)


Creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
OR 
```
conda activate venv
```

```
pip install -r requirements.txt
```

To Add files to git
```
git add .
```

OR
```
git add <file_name>
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status 
```
git status
```
To check all version maintained by git
```
git log
```

To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url 
```
git remote -v
```



BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase


To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

To check running container in docker
```
docker ps
```

Tos stop docker conatiner
```
docker stop <container_id>
```



```
python setup.py install
```


Install ipykernel

```
pip install ipykernel
```


