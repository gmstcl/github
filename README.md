# github

The ability to upload files to the Git repository is limited to 500 MB, but the Git Large File System (LFS) allows the Git repository to perform version management of large files (up to 5 GB per file). Git LFS works by committing only metadata for large files to the repository and storing the actual file contents in a separate remote repository.

```sh
git lfs install
git lfs track "*.exe"
git add .gitattributes
git add .
git commit -m "init"
git push origin main
```
