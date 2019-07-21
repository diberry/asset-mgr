# Cognitive asset manager

Manage assets and models built from assets for Cognitive Services

## Goals/Roadmap

1. Manage cognitive models and their underlying assets regardless of Cognitive service
1. Deploy cognitive model within CICD pipeline or other automation
1. Backup cognitive model, providing versioning, search, group collaboration

### Goals for One Week

1. Manage text files by UX 
  * create Azure File container by User
  * delete Azure File container by User
  * add file to Azure Files, track 
      * container
      * user
      * filename
      * language 
  * delete file by 
      * container
      * user
      * filename
      * language
  * list files with
      * container
      * user
      * filename
      * language
      * download URL
1. Get file list for container by API, include: 
   * container 
   * filename 
   * language
   * dateCreated
   * dateLastModified
   * public download URL
1. Transform - translate (and add) text file to Azure Files: track container, filename, language
1. Transform - text (for language A) to speech (for langauge A)

2019 hackathon #82038

* [Backend project](https://github.com/diberry/asset-mgr-back) Node.js backed to Azure Storage
* Frontend project - coming soon - need to clean it up
