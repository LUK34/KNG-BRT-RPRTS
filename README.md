

- Initialize Git
- Track large files (like .rar) using Git LFS (do this BEFORE adding files)
- Add LFS tracking file
- Add your files to Git
- Commit with a message
- Set branch to main
- Add remote repository
- Push to GitHub

### First push of large files
```
git init
git lfs install
git lfs track "*.rar"
git add .gitattributes
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/LUK34/KNG-BRT-RPRTS.git
git push -u origin main
```

### Update large files in repo after first Initialize
```
git lfs track
git add .
git commit -m " "
git push origin main
```

