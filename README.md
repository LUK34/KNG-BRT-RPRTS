

- 1. Initialize Git
- 2. Track large files (like .rar) using Git LFS (do this BEFORE adding files)
- 3. Add LFS tracking file
- 4. Add your files to Git
- 5. Commit with a message
- 6. Set branch to main
- 7. Add remote repository
- 8. Push to GitHub

### First push of large files
git init
git lfs install
git lfs track "*.rar"
git add .gitattributes
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/LUK34/KNG-BRT-RPRTS.git
git push -u origin main
