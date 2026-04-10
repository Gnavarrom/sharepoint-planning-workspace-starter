# GitHub Upload Checklist

This checklist is for publishing the public-safe starter pack to a new GitHub repository.

## What to upload

Upload the contents of `public-demo/` only.

That means this GitHub repo should include:

- `README.md`
- `LINKEDIN_POST.md`
- `STORY_SCRIPT.md`
- `CODEX_STARTER_GUIDE.md`
- `DISTRIBUTION_PLAN.md`
- `LIST_TEMPLATE.md`
- `sample-team.csv`
- `sample-tasks.csv`
- `PUBLIC_REPO_CHECKLIST.md`
- `video/`
- `images/`
- `.gitignore`

## What not to upload

Do not upload the original project root.

Do not upload:

- `src/`
- `config/`
- `sharepoint/`
- `lib/`
- `dist/`
- `release/`
- `node_modules/`
- any internal files that still contain real naming or workplace context

## Recommended repository name

Pick one of these:

- `sharepoint-planning-workspace-starter`
- `sharepoint-to-planning-workspace-demo`
- `codex-sharepoint-starter-pack`

## Recommended repository description

Public-safe starter pack showing how a SharePoint list workflow can evolve into a lightweight planning workspace using VS Code and Codex.

## Recommended repo visibility

`Public`

## Easiest upload method

### Option 1: GitHub web upload

1. Create a new empty repository on GitHub.
2. Open the `public-demo/` folder on your machine.
3. Select everything inside `public-demo/`.
4. Drag those files into the new GitHub repository upload screen.
5. Commit with a message like:
   `Initial public starter pack`

Important:
Upload the contents of `public-demo/`, not the `public-demo` folder itself, so the repo opens directly with `README.md` at the root.

### Option 2: Git locally

From inside `public-demo/`:

```bash
git init
git add .
git commit -m "Initial public starter pack"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

## Best structure for sharing on LinkedIn

Use GitHub as the permanent home of the free resource.

Then in LinkedIn:

1. publish the post
2. ask people to comment `starter pack`
3. pin a comment with the GitHub link
4. optionally also add the link to your profile featured section

## Optional extra step

Create a ZIP from the repo contents for people who prefer download over GitHub browsing.

## Final check before publishing

1. Open the GitHub repo homepage.
2. Confirm `README.md` is visible immediately.
3. Confirm the images load.
4. Confirm `video/index.html` is present.
5. Confirm no internal names or workplace references remain.
