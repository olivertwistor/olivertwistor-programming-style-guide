# Folder structure for Python projects

| Folder | Contents|
| :-- | :--|
|`/` | Repository files, such as readme, licenses and main `.gitignore`. Also a makefile, `requirements.txt` for dependencies and `setup.py` for initial project setup.|
|`/docs` | Documentation.|
|`/lib` | Libraries that aren't in a Maven repository and thus need to be imported locally into Maven.|
|`/resources` | Resources, such as databases and images.|
|`/{moduleName}` | Source code.|
|`/tests` | Source code and resources for tests.|
|`/venv` | A Python virtual environment for this project.|
