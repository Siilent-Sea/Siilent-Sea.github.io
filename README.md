# ZJP Software Development & IT Services

Static GitHub Pages website for an individual freelance software development
service profile.

## Local preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8080
```

Then visit:

```text
http://localhost:8080
```

## Publishing to GitHub Pages

This site is designed for a GitHub user site repository named:

```text
Siilent-Sea.github.io
```

If this directory is not initialized as a Git repository yet:

```bash
git init
git add .
git commit -m "Create freelance software development service page"
git branch -M main
```

After the repository exists on GitHub:

```bash
git remote add origin git@github.com:Siilent-Sea/Siilent-Sea.github.io.git
git push -u origin main
```

If GitHub Pages is not enabled automatically, open the repository settings:

```text
Settings -> Pages -> Build and deployment -> Source -> Deploy from a branch
Branch: main
Folder: / root
```

The public website URL will be:

```text
https://Siilent-Sea.github.io/
```

## Public information used

- Public service name: `ZJP Software Development & IT Services`
- Contact email: `momomonkfish@gmail.com`
- GitHub profile: `https://github.com/Siilent-Sea`
- Profile name: `Zhou Jianping`

Do not add private employer, client, phone, home address, credentials, or
internal project details to this public website.
