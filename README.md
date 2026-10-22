# Harrison Brown — Portfolio

Buildless static site. The hosted files are in `dist/`.

## Updating content
Edit `dist/content.js`. Add a project object to `projects` using the existing shape. Set `repo` to the exact repository name for a direct source link. Leave it blank to link to your GitHub profile. Update experience in the same file. Project descriptions and metrics should reflect verified work.

The Fresh from GitHub section automatically fetches the three most recently pushed, non-forked, non-archived public repositories from `hbrown88` on page load. GitHub rate limits and network failures fall back to a profile link. Featured projects remain curated so a new repository does not overwrite your strongest work.

Project title links are generated automatically from the projects list. Set `resumeUrl` in `dist/content.js` to a stable HTTPS URL for your latest résumé; all résumé links use this setting. By default it uses the uploaded copy at `dist/resume.pdf`, which you can replace and redeploy. Change presentation in `dist/style.css`; project rendering and interactions live in `dist/app.js`. No dependencies or build required. Redeploy after editing curated content. Do not put GitHub tokens in this public code.
