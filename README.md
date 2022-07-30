## Start Machine Learning project.

### Software and account Requirement.



Aim of the project
The aim is to build a predictive model to find out the sales of each product at a particular store so that it would help the decision makers at BigMart to find out the properties of any product or store, which play a key role in increasing the overall sales.

Predict sales of each item on particular store


Data Description
Variable - Description
Item_Identifier - Unique product ID
Item_Weight - Weight of product
Item_Fat_Content - Whether the product is low fat or not
Item_Visibility - The % of total display area of all products in a store allocated to the particular product
Item_Type - The category to which the product belongs
Item_MRP - Maximum Retail Price (list price) of the product
Outlet_Identifier - Unique store ID
Outlet_Establishment_Year - The year in which store was established
Outlet_Size - The size of the store in terms of ground area covered
Outlet_Location_Type - The type of city in which the store is located
Outlet_Type - Whether the outlet is just a grocery store or some sort of supermarket
Item_Outlet_Sales - Sales of the product in the particular store. This is the outcome variable to be predicted.



[SS High_Level_Design.docx](https://github.com/codeofelango/ineuronproject_storesales/files/9224804/SS.High_Level_Design.docx)
[SS Low_Level_Design.docx](https://github.com/codeofelango/ineuronproject_storesales/files/9224806/SS.Low_Level_Design.docx)

![homepage](https://user-images.githubusercontent.com/85941190/181875169-46c17560-ae8d-4578-8ea9-f1f21eeaf936.PNG)

![log](https://user-images.githubusercontent.com/85941190/181876044-23219c4a-4fe6-4fc2-a96c-9fee1f9e0c0d.PNG)

![predictionj](https://user-images.githubusercontent.com/85941190/181875243-4d5cccd7-fc45-4a38-84d3-5001d572b7b6.PNG)


1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)


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

To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL = elango.yuva27@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-storesales

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


git remote add origin https://github.com/codeofelango/ineuronproject_storesales.git

git branch -M main 

git add .

git commit -m "File added"
