[![Build Status](https://travis-ci.org/labs-js/turbo-git-commit.svg?)](https://travis-ci.org/labs-js/turbo-git-commit)
[![codecov](https://codecov.io/gh/labs-js/turbo-git-commit/branch/develop/graph/badge.svg)](https://codecov.io/gh/labs-js/turbo-git-commit)
[![npm](https://img.shields.io/npm/v/turbo-git-commit.svg?style=flat)](https://www.npmjs.com/package/turbo-git-commit)
[![Turbo Commit](https://img.shields.io/badge/Turbo_Commit-on-3DD1F2.svg)](https://github.com/labs-js/turbo-git/blob/master/CONVENTION.md)
[![bitHound](https://www.bithound.io/github/labs-js/turbo-git-commit/badges/score.svg)](https://www.bithound.io/github/labs-js/turbo-git-commit)
[![Code Climate](https://codeclimate.com/github/labs-js/turbo-git-commit/badges/gpa.svg)](https://codeclimate.com/github/labs-js/turbo-git-commit)

# turbo-git-commit

**Turbo git commit** -> Help command for implement easily a commit convention. 

#### This lib is part of the [Turbo Git](https://github.com/labs-js/turbo-git) -> Making your git even more awesome 😎🙌

## how to use it:

```
npm install --save turbo-git-commit
```

And then from the code when you need use it:

```javascript
require('turbo-git-commit')()
```

This will print out the command output guiding you on how to commit, following the obtained commit convention. 
> Note: The commit convention will be obtained by the `.turbogit` config file on the git repo. If this file is not on your repo this will use the default convention got by the package [turbo-git-config](https://github.com/labs-js/turbo-git-config/)
