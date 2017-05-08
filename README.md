# LoungeSquatt Website

This website is made with Wordpress and Git.

The project is base on [markjaquith/WordPress-Skeleton](https://github.com/markjaquith/WordPress-Skeleton)
and then create this tutorial to create wp-core as submodule:
https://davidwinter.me/install-and-manage-wordpress-with-git/


## Files structure

`wp-core/` is added as submodule and is an instance of the Wordpress core.
Each version in a branch and can be easily updated with:

```
cd wp-core
git fetch --tags
git checkout 3.3.2
cd ..
git commit -m "Update WordPress Core to version 3.3.2"

```

Custom files and directories are in `content/`


## Deploy
deploy is automatic done by GitLab
http://kanec.co.uk/2016/06/29/using-gitlab-ci-to-deploy-wordpress/
