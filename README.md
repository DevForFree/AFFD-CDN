# AFFD-CDN
免费，快速，高效的公共CDN项目。

## 加速范围
对各种小众个人github项目文件加速。

## 限制
限制单文件大小<5MB，单文件夹大小<30MB。<br>
国外IP地址将无法使用该公共CDN加速。<br>
禁止加速以下内容:<br>
1.违反中国大陆法律的内容。<br>
2.运行图像托管网站并使用AFFD-CDN作为所有上传图像的存储。<br>
3.大量托管视频、文件备份或其他文件的内容。<br>

## 食用方法
Fork这个仓库，然后在仓库目录下创建任意名称的文件夹，将需加速的内容放入该文件夹中，向本仓库提交`PR`，并等待审核。<br>
随后，你可以使用```https://cdn.affd.ml/{FOLDER_NAME}/{FILE_NAME}```进行调用。<br>

## 公测
本项目于2022年5月3日12:20开启公众测试。

## 原理
对本仓库的raw.githubusercontent.com下的内容进行CDN加速。<br>
使用`Cloudfront`内容分发网络对该仓库下的内容进行加速。

### 速度测试
![IMG_20220503_125204.JPG](https://alpha-q3.sourcegcdn.com/2022/05/03/9yXlgmMI.JPG)
