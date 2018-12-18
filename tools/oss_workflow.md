# Repository Sync Utilities


## Options for cloning or transforming repositories

- HubSync: [github.com/jonatanpedersen/hubsync](https://github.com/jonatanpedersen/hubsync)
	- Clones an organization or person’s repositories. Node.js
- Repository-sync: [github.com/gjtorikian/repository-sync](https://github.com/gjtorikian/repository-sync)
	- repository-sync is a tool designed to keep two repositories—one private, one public—entirely in sync. Private commits are [squashed](http://jamescooke.info/git-to-squash-or-not-to-squash.html) into a single commit to avoid leaking information. Similarly, every public commit is brought over to the private repository, so that none of the history is lost.
- Google Copybara: [github.com/google/copybara](https://github.com/google/copybara)
	- Copybara is a tool used internally at Google. It transforms and moves code between repositories.
- OSS Fork: [github.com/larsxschneider/scotty/blob/master/admin/oss-fork.sh](https://github.com/larsxschneider/scotty/blob/master/admin/oss-fork.sh)
	- Fork Public OSS to your own private instance 


## Others 

- Git-sync: [github.com/kubernetes/git-sync](https://github.com/kubernetes/git-sync)
	- git-sync is a simple command that pulls a git repository into a local directory. It is a perfect "sidecar" container in Kubernetes - it can periodically pull files down from a repository so that an application can consume them. Written in Go.
- Issue Shadower: [github.com/benbalter/issue-shadower](https://github.com/benbalter/issue-shadower)
	- Issue Shadower. A webhook receiver to mirror [GitHub.com](http://GitHub.com) issues to private GitHub Enterprise forks. Ruby.
- HookHand: [github.com/mikemcquaid/HookHand](https://github.com/mikemcquaid/HookHand) 
	- A small web application which runs scripts from webhooks. Ruby.


