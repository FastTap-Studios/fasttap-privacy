# fasttap-privacy

Static site for FastTap's Privacy Policy (GitHub Pages).

## Quick publish

1. Create a new **public** repo named `fasttap-privacy` on GitHub under your account.
2. Add these files and push:
   ```bash
   git init
   git remote add origin https://github.com/<your-github-username>/fasttap-privacy.git
   git checkout -b main
   git add .
   git commit -m "Add privacy policy"
   git push -u origin main
   ```
3. In the GitHub repo: **Settings → Pages**  
   - Source: *Deploy from a branch*  
   - Branch: *main*  
   - Folder: */docs*  
4. Your policy will be live at:  
   `https://<your-github-username>.github.io/fasttap-privacy/privacy-policy-fasttap.html`

Update that URL in your Godot project at:  
`res://singletons/ConsentManager.gd` → `PRIVACY_POLICY_URL`.
