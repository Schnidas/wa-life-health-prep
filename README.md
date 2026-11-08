# Washington Life & Health Exam Prep

A single-page study platform for the Washington Life and Disability Producer exam. It has all 14 chapters in course order (notes, study guide, summary, quiz), cross-chapter review pages, a mixed question bank of 1,118 chapter questions, a 150-question practice exam weighted like the state exam, and four fixed practice exams.

Everything lives in `index.html`. The content is encrypted (AES-256-GCM, key derived from the passcode with PBKDF2), so the page shows nothing until the right passcode is entered. Without the passcode, the file is unreadable, even to someone who views the source.

## Publish with GitHub Pages
1. Put `index.html` (and this README) in the root of a GitHub repository.
2. On GitHub, open the repo's **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to "Deploy from a branch", choose the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two, the site is live at `https://<your-username>.github.io/<repo-name>/`.

Free GitHub accounts can only publish Pages from **public** repositories. That's okay here: the content is encrypted, so the public file shows only the passcode screen.

## Changing the passcode
The passcode is baked into the encryption. To change it, rebuild the page with the new passcode and replace `index.html`. Anyone who chose "Keep me signed in" will be asked for the new one.

## Notes
- Quiz scores are saved only in each person's own browser.
- For study use only. Not affiliated with PSI, ExamFX, or the Washington Office of the Insurance Commissioner. Confirm rules with official sources.
