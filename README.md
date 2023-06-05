# 教程
## 如何使用Github
如下载，克隆，上传
### 下载
顾名思义，就只是把当前的项目全部下载到本地(打开后是无法进行同步与上传的)<br>
<img src="https://github.com/Fall188/test/assets/117801884/57343178-33f8-48c8-9561-7051c87d2663" width="600px"><br>
### 克隆
#### VSCode
  - 在侧栏中的第三个有个叫`源代码管理`的，里边有个`克隆仓库`<br>
    <img src="https://github.com/Fall188/test/assets/117801884/5bcbfdbd-4e00-4b2a-ab58-f903aea1af0e" width="600px">
    <hr>
  - 当点击`克隆仓库`后，会弹出一些选项(我这就只有一个)，点击`从Github克隆`<br>
    <img src="https://github.com/Fall188/test/assets/117801884/93f91c81-e0f1-4b03-9b69-e6ba998196e3" width="600px">
    <hr>
  - 再从你想克隆的仓库获取链接，像以下图片中点击就复制到链接了<br>
    <img src="https://github.com/Fall188/test/assets/117801884/3e978aee-b002-4f74-ae57-f96c4b723bd2" width="600px">
    <hr>
  - 把链接粘贴就去，在下面就会出现链接仓库的信息<br>
    <img src="https://github.com/Fall188/test/assets/117801884/f60ae029-e1c2-4f60-aed6-0461708dfcbb" width="600px">
    <hr>
  - 点击后它会让你选择存储的路径，选好后在点击右下角的<br>
    <img src="https://github.com/Fall188/test/assets/117801884/19341a62-ab42-46f9-999f-66de1c4ebd4b" width="600px">
    <hr>
  - 然后等待克隆完成...<br>
    <img src="https://github.com/Fall188/test/assets/117801884/1ab5096d-5a35-453d-8aac-de718a7ff9c1" width="600px">
    <hr>
  - 这是克隆完成的样式<br>
    <img src="https://github.com/Fall188/test/assets/117801884/bfdbfc6f-e243-4fa1-a552-49cb32ca895e" width="600px">
    <hr>
  - 打开`源代码管理`长这样就算是克隆完成了
    <img src="https://github.com/Fall188/test/assets/117801884/4f109b0f-c31b-457a-93ba-989b73eb8ec0" width="600px">
    <hr>

#### IDEA(PyCharm\WebStorm同理) *应该*
  - 位于`项目`中的右上角`从VCS获取`<br>
    <img src="#" width="600px">
    <hr>
  - 选择`Github`，粘贴仓库链接，下边就会出现
    ```
    克隆'https://github.com/***/***.git'
    ```
    如图<br>
    <img src="#" width="600px"><br>
    *当然，自行更改一下克隆存储的目录，不然飞哪去了你也不知道*
    <hr>
  - 再点击右下角的`克隆`，等待...<br>
    如图<br>
    <img src="#" width="600px">
    <hr>
  - 最后再选择如何打开就完成了!<br>
    <img src="#" width="600px">
<hr>

### 提交 与 推送
  #### VSCode
  - 当你在某些文件做过修改时，左侧的`源代码管理`就会有一个小点点<br>
  里面的内容如图<br>
  <img src="#" width="600px"><hr>
  - 里边的`提交`就相当于把你修改过的文件确定更改了，但是还并未上传到仓库中<br>
  另外，在`提交`前，得在`消息`中写入些东西，比如你所作的更改，跟查看仓库的人说你做了些什么<br>
  若你在`提交`前忘记写入`消息`了，到后边还是会弹出一个叫*COMMIT_EDITMSG*的文件让你输入`消息`，如图<br>
  <img src="#" width="600px"><hr>
  - 输入完`消息`后，点击位于右上角的勾*接受提交消息*，就会帮你完成一次提交了<br>
  *当你完成所有的更改之后就可以进行最后的同步提交了*