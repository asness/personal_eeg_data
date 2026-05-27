# EEG data

## Description

This is a repository for meditation EEG recordings.

## Equipment

I record the files with a Muse 2 and the Android Mind Monitor app.

## Repository contents

- `muse`: zipped recordings of hour-long Goenka vipassana practice sessions.
- `muse_downsampled`: just the precomputed band power data, sampled once per second. 

## GitHub notes

### Increase Git's post size

The file size of a zipped hour-long recording from the Music is around 30 MB.
This is too large for remote upload from PyCharm using the Git default settings.
To fix this, run
```{shell}
git config --global http.postBuffer 52428800
```

 