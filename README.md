# Fast-API 🚀
----------------------------------------

###  **Introduction: Structuring of API**

- `api_template:`  Contains all the API related Code Base.
    - `manage.py:` Only entry point for API. Contains no logic. 
    - `.env:` Most important file for your api and contains global configs. Acoid using application/variable level configs here.
    - `application:`  It contains all your api related codes and test modules. I prefer keeping application folder at global.
    - `logs`: Logs is self-explanatory. FYI it will not contain any configuration information, just raw logs. Feel free to move according to your comfort but not inside the application folder.
    - `models:` As a part of Machine-Learning/ Deep-Learning app you might need to add model files here or if you have huge files on cloud add symlinks if possibles.
    - `resources:` To store any documentation, application related csv/txt/img files etc.
    - `settings:` Logger/DataBase/Model global settings files in yaml/json format.

- `application:` 
    - `main:` priority folder of all your application related code.
        - `🏗 infrastructure:` 
        - `📮 routers:`
        - `📡 services:`
        - `⚒ utility:`
        - `🐍 config.py:`
    - `test:`
    - `initializer.py:`
