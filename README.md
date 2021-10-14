This repo reproduces the following yarn issue https://github.com/yarnpkg/berry/issues/3434

There are two (surprising) ways of avoiding the stack overflow being thrown.

1. Copy pack1's peer dependencies into the dev depencies list

or

2. Remove the apps workspace
