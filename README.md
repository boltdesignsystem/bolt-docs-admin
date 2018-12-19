# Bolt Docs Admin

Update [Bolt Site](https://bolt-design-system.com) by using this admin UI: <https://bolt-docs-admin.netlify.com> and sign in with GitHub account. If you have access to repo, you have access to admin.

Edits saved as drafts will create Pull Requests on the [Bolt repo](https://github.com/bolt-design-system/bolt) and then deploy an example site you can preview. Upon moving a draft to published, it will merge the PR into `master` and then deploy to live site. Using GitHub UI is not necessary, but can be helpful for feedback.

This uses [Netlify CMS](https://www.netlifycms.org/docs/intro) and any alterations to `./admin/config.yml` will adjust site; just `git push` and wait ~60 seconds. 

The Netlify site is hosted by Basalt and is [configured here](https://app.netlify.com/sites/bolt-docs-admin/), but to be honest, there's next to no configuring there needed. It basically provides static hosting and a git gateway to this [Bolt GitHub app](https://github.com/organizations/bolt-design-system/settings/applications/954531).
