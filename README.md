# CIT Codelabs

## Source Files
These codelabs are developed from source files stored in the robiupui account.

## Hosting
Final output of these codelabs is hosted on a storage bucket in the cit-codelabs project.

### Updating Remote Files

```
gcloud config set project cit-codelabs
gsutil rsync -r {codelab-folder} gs://elliott-cit-codelabs/{codelab-folder}
```