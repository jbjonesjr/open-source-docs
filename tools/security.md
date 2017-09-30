## Security, Inspectors, and Pre-receive hook stuff

#### Truffle Hog find security keys:
http://windowsitpro.com/security/truffle-hog-finds-security-keys-hidden-github-code

#### GitMagic
Enforces contributing guidelines via status checks and protected branches
https://gitmagic.io/
example: https://github.com/benbalter/gman/pull/133#issuecomment-213111334

## Commit and repo inspectors

#### Project-Migration

https://github.com/krues8dr/project-migration

#### GitHub-Watchdog
https://github.com/jfredrickson5/github-watchdog

#### Poirot
https://github.com/emanuelfeld/poirot

#### Git-Seekret
https://github.com/apuigsech/git-seekret
> git-seekret is a cross-platform, open source, Golang application through a pre-commit git hook, that can inspect the files that are staged for the commit and if there is anything found in either the files or the commit message that matches any of the enabled rules it will prevent that commit from making its way into your repository. It also can scan existing commits and notify you of any sensitive information that has already made its way into your repository. [from 18F blog [announcement post](https://18f.gsa.gov/2017/09/26/automated-scanning-for-sensitive-information/)]


#### Clouseau
Search your repository's git history for undesirable text patterns such as passwords, ssh keys and othe personal identifiable information
https://github.com/cfpb/clouseau


#### Git Secrets for AWS
Prevents you from committing secrets and credentials into git repositories
https://github.com/awslabs/git-secrets

#### Safe Commit Hook
pre-commit hook for Git that checks for suspicious files.
https://github.com/jandre/safe-commit-hook

#### GitRob
Reconnaissance tool for GitHub organizations
Details: http://michenriksen.com/blog/gitrob-putting-the-open-source-in-osint/
https://github.com/michenriksen/gitrob
