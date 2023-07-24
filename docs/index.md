# Backstage documentation

## Summary

![image](https://github.com/micc83/wr-backstage-docs/assets/1750404/c7a804e6-d4f3-48c7-8768-85be10760e10)

## Todo

- [ ] Authentication and permissions
- [ ] Select to easily switch between envs -> will change the host but keep the path of the current url
- [ ] Create new project from backstage is doable (devops)?
- [x] Tech Documentation to migrate from clickup -> Ability to export to md files
- [x] For techdocs might be cumbersome to have all documents inside `/docs` folder when readme.md, changelog.md, contributing.md are usually in the root. -> We can create symbolic links

## Links
- https://blog.apihero.run/how-to-programmatically-create-a-commit-on-github#heading-3-create-a-commit

## How to integrate backstage with your project

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur ut ex tempor nibh accumsan vulputate. Vivamus ac placerat neque, in pellentesque ex. Aenean in dui at eros tincidunt viverra. Morbi mi ligula, interdum sed rutrum vitae, placerat eu risus. Proin elementum libero id rhoncus feugiat. Nunc sodales, massa nec convallis commodo, ligula lectus feugiat orci, a rutrum arcu elit et nisl. Sed ornare lobortis tortor, id placerat ex blandit ac. Curabitur sit amet sapien sed est elementum fringilla. Phasellus convallis arcu risus, et finibus tortor vulputate quis. Nam ullamcorper augue vitae consequat suscipit.

## Hot to expose root .md files in techdocs

From the docs folder:
```
ln -s ../README.md ./index.md
```

