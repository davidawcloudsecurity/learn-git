# learn-git
https://medium.com/@jake.page91/the-guide-to-git-i-never-had-a89048d4703a

## How to create MR
https://stackoverflow.com/questions/37410262/how-to-create-a-gitlab-merge-request-via-command-line

https://dev.to/farnabaz/gitlab-create-merge-requests-from-cli-c36
```bash
git push -o merge_request.create -o merge_request.target=your-branch-name
git push --set-upstream origin your-branch-name -o merge_request.create
```
