# dart-debian

Debian meta files for DART PPA

## Update `changlog` files using a script

Set following environment variables that are used in the changelog files:

```shell
$ export DEBEMAIL=<your_email>        # e.g., export DEBEMAIL=jslee02@gmail.com
$ export DEBFULLNAME=<your_fullname>  # e.g., export DEBEMAIL=Jeongseok Lee
```

To update changelogs and push a commit for the changes, run:

```shell
$ cd <dart_version_to_update>          # e.g., cd 6.12
$ ../changelog_spawn.sh <new_version>  # e.g., ../changelog_spawn.sh 1.0.0-0
```
