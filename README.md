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
     REPACK_NAME: Name package u need
3. Start commit -> Actions -> Star -> SGSI-Build
```
 
## Output
The output (GSI) are downloaded in [Release](../../releases) 
Files larger than 2G will be automatically uploaded using sub-volume compression
If the upload result is sub-volume compression, download all sub-volumes and merge them with the following command: 
```
cat upload/* > SGSI.zip
```

## Other tools
Android R Tool:[Action-SGSI-build](https://github.com/XayahSuSuSu/Action-SGSI-build)
