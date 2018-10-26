# About
.Net Core image with AzCopy for Linux installed

# Usage

```
#Example: backup Azure Files to Azure Blobs
# docker run --name azcopy dev1l/azcopy-linux azcopy --source https://$SOURCE_STORAGE_ACCOUNT_NAME.file.core.windows.net/$SHARE_NAME --destination https://DESTINATION_STORAGE_ACCOUNT_NAME.blob.core.windows.net/$BLOB_CONTAINER_NAME --source-key SOURCE_STORAGE_ACCOUNT_KEY --dest-key DESTINATION_STORAGE_ACCOUNT_KEY --recursive
```

Details: https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-linux
