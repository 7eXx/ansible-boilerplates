# Boilerplates
This repo holds some useful recurrent tasks for maintenance about servers.

## Credits
This repo is freely inspired by [boilerplates by ChristianLempa](https://github.com/ChristianLempa/boilerplates)

## Usage
To perform a disk cleanup:
```sh
$ ansible-playbook maintenance/disk-cleanup.yml
```
Cleanup all dangling docker stuffs:
```sh
$ ansible-playbook  maintenance/docker-cleanup.yml
```
Performs system update:
```sh
$ ansible-playbook maintenance/update.yml
```
Check disk space:
```sh
$ ansible-playbook maintenance/disk-space.yml
```


