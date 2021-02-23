# Benjamin Galyen's Website

Built using [Eleventy](https://www.11ty.io).

## Managing the Website

Here are all the recipes for making updates

### Opening project in Visual Studio Code

1. Open command prompt
1. `cd Desktop`
1. `cd projects`
1. `cd benweb`
1. `code .`

### Build and Run Website Locally

```sh
npm run build
npm run dev
```

> Note: Press CTRL+C to stop the local webserver

### Folders

|Folder or File|Description|
|:---|:---|
|`src/site`|This is where the markdown files go. `index.md` is the home page.|
|`src/site/images`|This is where images go.|
|`src/site/_data/site.json`|Configuration of the website including name, description, navigation, and others.|

### Creating a Newsletter Post

```sh
npm run post create "Title of Super-Awesome Newsletter"
```

### Publishing a change

|Command|Description|
|:---|:---|
|`git pull`|Get the latest changes|
|`git add .`|Stage all changes to be committed.|
|`git commit -m "description of update"`|Commit all changes locally.|
|`git push`|Push commits to GitHub.|

## Copyright & License

Copyright (c) 2021 Benjamin Galyen - Released under the [MIT license](LICENSE).

## Based on ReverentGeek's Blog

This site is inspired by [ReverentGeek's Blog](https://reverentgeek.com)
