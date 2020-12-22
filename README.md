* 下载并进入项目文件夹

    ```shell
    > cd frontend
    ```

*  安装依赖

    ```shell
    > npm i
    ```
    ps.　若安装失败，先将package-lock.json和node_modules文件夹删除后重新执行安装命令

    或者手动安装
    ```
    npm install --save reactstrap react react-dom
    npm i office-ui-fabric-react
    npm install --save react-modal
    npm install --save react-router-dom
    ```

*  运行

    ```shell
    > npm start
    ```

* 等待编译完成后, 访问```localhost:3000/login```, 看到登录页面表示运行成功。

    ![1](img/1.png)

* 可浏览的网址如下:

    ```shell
    localhost:3000/login    -登录页
    localhost:3000/signup   -注册页
    localhost:3000		      -主页
    ```

     进入主页后, 点击内容会有相应的跳转(查看一条内容的详情, 查看用户资料, 查看用户关注/被关注列表), 不再一一列出。

