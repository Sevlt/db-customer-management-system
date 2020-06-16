# 客户管理系统数据库

[客户管理系统](https://)

### 手动创建过程

-   安装依赖
    ```
    npm install -g json-server
    ```
-   创建文件夹
    ```
    mkdir DBdemo
    ```
-   切换到文件夹目录
    ```
    cd DBdemo
    ```
-   安装数据文件
    ```
    touch db.json
    ```
-   初始化项目
    ```
    npm init -y
    ```
-   安装 `json-server` 模块并储存在 package.json
    ```
    npm install json-server --save
    ```
-   把 `package.json` 中 `"test"` 值修改为
    ```
    json-server --watch db.json
    ```
