# Resources needed to build pod-ui 

This is a repository for resource needed to build `pod-ui` on
non-GTK-native platforms, i.e. Windows and MacOS. On Linux
you typically already have a GTK theme set up and you don't
care about these.

This repo is needed for `mk-win64-dist.sh` and `mk-osx-dist.sh`
scripts and is imported into the `pod-ui` repository as a
sub-module due to its relatively large size and infrequent use.

For now the themes are:

 * Arc GTK theme: https://github.com/lbrfabio/Arc-theme @
   [89e5335](https://github.com/lbrfabio/Arc-theme/tree/89e53355eef70b495ea0974b17d187151c589241)
 * Paper icon theme: https://github.com/snwh/paper-icon-theme @
   [aa3e8af](https://github.com/snwh/paper-icon-theme/tree/aa3e8af7a1f0831a51fd7e638a4acb077a1e5188)
