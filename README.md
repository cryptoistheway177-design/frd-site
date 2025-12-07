# 1. Ga naar je lokale FRD projectmap
cd /pad/naar/frd-site-vercel

# 2. Initialiseer Git (als nog niet gedaan)
git init

# 3. Voeg de remote repository toe / update de URL
git remote add origin https://github.com/cryptoistheway177-design/frd-site.git
# Als remote al bestaat:
# git remote set-url origin https://github.com/JOUW_GITHUB_USERNAME/frd-site.git

# 4. Voeg alle bestanden toe
git add .

# 5. Maak een commit
git commit -m "Reset FRD website"

# 6. Force push naar GitHub en overschrijf oude bestanden
git branch -M main
git push -u origin main --force


