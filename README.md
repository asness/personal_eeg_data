# EEG data

## GitHub notes

### Increase Git's post size

The file size of a zipped hour-long recording from the Music is around 30 MB.
This is too large for remote upload from PyCharm using the Git default settings.
To fix this, run
```{shell}
git config --global http.postBuffer 52428800
```

 