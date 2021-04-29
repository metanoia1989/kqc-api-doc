# kqc-api-doc
孔雀巢API文档 使用OpenAPI构建。     

公司本来的API文档用的是ShowDoc，在线编辑和查看都非常方便，缺点是无法导入postman，前端必须自动手动来建，不太方便。   
用OpenAPI的规范来编写文档，这样方便导入。而且是非侵入式的，之前一个公司用的 [APIDoc](https://apidocjs.com/) 是写在代码注释中的，侵入了代码了。   
本来想把文档文件放在项目里，但是很多个项目，文档分散了也不好编辑，后续处理还要一个个文件夹查看太麻烦了，所以单独建一个仓库。    

使用方式，先安装依赖，然后发布文件，再将 public 设置为网站根目录
```sh
$ yarn install
$ yarn run copyredoc
```