# SGSI-build-action
**Don't build directly in this warehouse, please fork this warehouse first, and then go to your own warehouse to build!**

## How to use:
```
1. Fork this repo
2. Edit SGSI_Build.yml:
     ROM_URL: Rom download link (direct link)
     ZIP_NAME: Archive Name (GSI name)
     OS_TYPE: Rom Type  
     BUILD_TYPE: Choose ab or a-only to build
     REPACK_NAME: 为你需要打包的包名
3. Start commit -> Actions -> Star -> SGSI-Build
```
 
## Output
结果在[Release](../../releases)下载  
大于2G的文件将自动采用分卷压缩上传  
如果上传结果为分卷压缩，下载所有分区卷，并使用以下命令进行合并:
```
cat upload/* > SGSI.zip
```

## 友情链接
Android R版:[Action-SGSI-build](https://github.com/XayahSuSuSu/Action-SGSI-build)
