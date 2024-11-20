npm create @keystatic@latest
- Astro
- ./testtest2

npm i

git init

manually create .gitignore

git push … create github repo (private by accident)

modify keystatic.config.ts

git push …

npm run dev

open http://127.0.0.1:4321/keystatic/

On the UI that starts the github flow
- leave both fields blank

Continue => Redirecting back to `http://127.0.0.1:4321/api/keystatic/github/created-app?code=123`
==> Which leads to a `404 Not Found`

---

Manually open http://127.0.0.1:4321/keystatic/ to start the process again
- Redirects to https://github.com/login/oauth/authorize?client_id…

Auth again with github

Now I see http://127.0.0.1:4321/keystatic/repo-not-found with "Repo not found"

Now running through the repo access screens

---

Now editing works as expeced.

Repo is now public as well at https://github.com/tordans/astro-keystatic-test/
