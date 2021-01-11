### 导入项目
- 检出代码
  ```bash
  git clone https://github.com/git9527/freecloud-viewer
  ```
- 进入项目文件夹并安装依赖
  ```bash
  cd freecloud-viewer
  npm install
  ```
- 打开`HbuilderX`并导入本地项目
  ![image](../../static/image/viewer/setup/import-project.png)
  
### 配置项
- 打开`src`文件夹下`config.json`文件，调整远程Url，默认 `https://23a1b1db-1fd0-4c43-ade4-57acfd9f8b49.bspapp.com/http/netdisk/files`
  ![image](../../static/image/viewer/setup/config-for-remote.png)

### 本地运行
- 左键选中`freecloud-viewer`项目，从`HbuilderX`顶部工具栏选择【运行至浏览器】->【Chrome】(其他浏览器也行)
  ![image](../../static/image/viewer/local-dev/run-to-chrome.png)
  - 控制台输出编译结果
  ![image](../../static/image/viewer/local-dev/compile-success.png)
- 打开的浏览器中会显示如下页面
  ![image](../../static/image/viewer/local-dev/index.png)
  
