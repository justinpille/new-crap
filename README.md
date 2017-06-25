# New create-react-app Project

## How I got here

After creating a new project with create-react-app, I...
- added a homepage property to package.json
- added a linter config to package.json
- added a deploy script to package.json
- installed gh-pages
- deleted some junk in src


## Usage

```
  git clone https://github.com/justinpille/new-crap.git <project-name>
  cd <projet-name>
  rm -rf .git
  git init
  git add .
  git commit -m "initial commit"
  git remote add origin https://github.com/justinpille/subsets.git
  git push -u origin master
```
Create a new repo on Github named <project-name>
```
git remote add origin https://github.com/justinpille/<project-name>.git
git push -u origin master
```

Develop:
```
npm start
```

Build:
```
npm run build
```

Deploy:
```
npm run deploy
```
