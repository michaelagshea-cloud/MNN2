# How to Upload This Repository to GitHub

## Option A: GitHub web interface

1. Go to GitHub.
2. Create a new repository.
3. Suggested name:
   `MNN5-YJL186W-drylab-validation`
4. Keep it private at first.
5. Upload the contents of this folder.
6. Commit with message:
   `Initial MNN5 dry-lab validation repository`

## Option B: command line

```bash
cd MNN5_GitHub_Repository_READY
git init
git add .
git commit -m "Initial MNN5 dry-lab validation repository"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/MNN5-YJL186W-drylab-validation.git
git push -u origin main
```

## Option C: I can populate an existing repo

Create a blank GitHub repository yourself, then provide the full repo name:

```text
owner/repository-name
```

I can then add core text files to that existing repository through the GitHub connector. Large ZIP/binary uploads may still be better handled manually.
