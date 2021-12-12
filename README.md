### Typora图片上传-基于Github+PicGo-Core+jsdelivr

#### 1、设置图像

打开图像设置`文件->偏好设置->图像`，进行如图设置

![图像设置](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211203255494.png)

#### 2、下载PicGo-Core

点击`下载或更新`，可能下载速度很慢，耐心等待

#### 3、创建Github仓库

前往Github创建仓库

![Github创建仓库](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211203944511.png)

#### 4、生成tokens

![前往生成tokens](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211205011819.png)

![创建新的tokens](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211205238261.png)

![生成tokens](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211205528647.png)

![复制tokens值](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211205656197.png)

#### 5、设置图像配置文件

打开配置文件

![打开配置文件](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211210019141.png)

粘贴一下代码

```json
{
  "picBed": {
    "current": "github",
    "github": {
      "repo": "github仓库地址",
      "branch": "main",
      "token": "上面复制的tokens",
      "path": "",
      "customUrl": "https://cdn.jsdelivr.net/gh/github仓库地址"
    }
  },
  "picgoPlugins": {}
}
```

解释：github仓库地址

![github仓库地址](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211210433740.png)

#### 6、测试

打开图像设置，点击`验证图片上传选项`

显示如图所示，即设置成功

![测试成功](https://cdn.jsdelivr.net/gh/1804784474/images/image-20211211210734509.png)

