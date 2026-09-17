# rimtoln GitHub profile README

Special repo: **`rimtoln/rimtoln`** (must match the username exactly, public).

## Push (from this folder)

```powershell
cd "D:\script cursor\github-profile-rimtoln"
git init -b main
git add .
git commit -m "profile README: cryptopsihoz desk layout"
gh auth login   # use the rimtoln account if current is mistikoz
gh repo create rimtoln/rimtoln --public --source=. --remote=origin --push
```

Or create empty `rimtoln/rimtoln` on github.com → then:

```powershell
git remote add origin https://github.com/rimtoln/rimtoln.git
git push -u origin main
```

After push, open https://github.com/rimtoln — the README renders as the profile.

## Edit

- `README.md` — copy / badges / layout  
- `assets/banner.png` — top collage  
- `assets/desk.png` — right illustration  
