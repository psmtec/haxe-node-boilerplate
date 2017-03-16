# haxe-npm-boilerplate

## used packages
- [lix.pm](https://github.com/lix-pm/lix.client) - haxelib without the suck
- [switchx](https://github.com/lix-pm/switchx) - versioned haxe compiler
- [haxeshim](https://github.com/lix-pm/haxeshim)
- [nodemon](https://nodemon.io) - file change watcher
- [cross-env](https://www.npmjs.com/package/cross-env) - cross platform environment variables
- [shx](https://www.npmjs.com/package/shx) - cross platform shell commands

## available scripts
- install a haxe library from github (for other uses see the [lix.pm](https://github.com/lix-pm/lix.client) documentation)
  - ```npm run lix install gh:USERNAME/REPOSITORY```

- watch sources and rebuild in debug mode
  - ```npm run build:dev```

- watch compiled code and restart app in debug mode
  - ```npm run start:dev```

- watch sources and rebuild in release mode
  - ```npm run build:prod```

- watch compiled code and restart app in release mode
  - ```npm run start:prod```
