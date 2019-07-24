# Cognitive asset manager

Manage assets and models built from assets for Cognitive Services

## Goals/Roadmap

1. Manage cognitive models and their underlying assets regardless of Cognitive service
1. Deploy cognitive model within CICD pipeline or other automation
1. Backup cognitive model, providing versioning, search, group collaboration

### Goals for One Week


#### 1. Manage text files

|Task|UX Status|Backend Status|API|
|--|--|--|--|
|create Azure File container by User|-|Complete|-|
|delete Azure File container by User|-|Complete|-|
|add file to Azure Files|-|Complete|-|
|delete file by filename|-|Complete|-|
|list files|-|partial|-|
||||

#### 2. Translate

|Task|UX Status|Backend Status|API|
|--|--|--|--|
|translate (and add) text file to Azure Files|-|Complete|-|
||||


#### 3. Text to Speech

|Task|UX Status|Backend Status|API|
|--|--|--|--|
|translate (and add) text file to Azure Files|-|Complete - English only|-|
||||

2019 hackathon #82038

* [Backend project](https://github.com/diberry/asset-mgr-back) Node.js backed to Azure Storage
* Frontend project - coming soon - need to clean it up
