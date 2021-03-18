# MINTBEAN CHALLENGE

## About the challenge

This is a weekly learnathon designed by MintBean for those that are new and/or those that want to improve their web development skills.

This weeks challenge is to create a css framework similar to bootstrap.

https://www.mintbean.io/meets/4b9cd41c-4a27-4c08-a493-3095f9fe2b20?template=meet


## BYOB.css

BYOB.css is an starter CSS framework built for [Mintbean Learnathon #82 - Build Your Own Bootstrap](https://mintbean.io/meets/4b9cd41c-4a27-4c08-a493-3095f9fe2b20).

# Local deployment

This project uses yarn workspaces. You'll need to install `yarn` in order to deploy this locally. Yarn is actually an amazing dev tool and has really neat features like caching, which makes `yarn install` MUCH faster than npm.

(You don't have to install yarn. But you might have to fiddle around with `npm link` if you don't! Be warned.)

Once you've installed yarn, you can do:

```
yarn install
yarn start
```

That's it! Then you should be able to visit the project at [http://localhost:1234](http://localhost:1234).

# How this project is structured

This project uses `yarn workspaces` to stitch two separate JS projects together. They are:

- `packages/byob-css`, a lightweight core CSS framework that can be imported into any SCSS-enabled project. You can start reading this project from `packages/byob-css/src/index.scss`. We're using `parcel-bundler` to bundle things together for this app. If you want to push your framework to NPM, you should probably look into replacing this with [Rollup](https://rollupjs.org/).

- `packages/byob-css-example`, an example kitchen sink. It's VERY raw. You can start reading this project from `packages/byob-css-example/index.html`.

# Sources that I learned from: 

https://geekyants.com/blog/building-your-own-css-framework-373\ 
https://developer.mozilla.org/\
https://www.geeksforgeeks.org/how-to-select-all-child-elements-recursively-using-css/\
https://sass-lang.com/documentation/at-rules/control/if\
https://www.youtube.com/watch?v=Zz6eOVaaelI\
https://www.youtube.com/watch?v=XanhwddQ-PM\
https://www.youtube.com/watch?v=QHRTiU2a3fg&t=304s\
https://onedebos.wordpress.com/2019/08/01/how-to-setup-sass-in-vscode/\
https://css-tricks.com/having-a-little-fun-with-custom-focus-styles/
