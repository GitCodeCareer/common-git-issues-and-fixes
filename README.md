# common-git-issues-and-fixes

## private repo push fail - not found

```
git remote rm origin
sudo git push --set-upstream HTTPS_REPO_URL BRANCH_NAME
```

https://stackoverflow.com/questions/10116373/git-push-error-repository-not-found
