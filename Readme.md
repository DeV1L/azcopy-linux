# About
.Net Core image with AzCopy for Linux installed

# Usage

```
# docker run --name azcopy azcopy-linux azcopy /Source:https://myaccount1.file.core.windows.net/myfileshare/ /Dest:https://myaccount2.blob.core.windows.net/mycontainer/ /SourceKey:key1 /DestKey:key2 /S
```

Details: https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-linux
