# Keith Taylor Authoring Website Source

[.github/`add new screenshot`]

All about Keith's:

- Sites owned
- Sites contributed to
- Social networks
- Public Profile Pages
- Archived content
- Any other Internet content
- Writing tools I use or have used
- Authoring tools I use or have used

I include tags. Especially `Contact` so you can easily see details of different ways to contact me. Including a summary page of the main ways to make contact.

This project is mostly edited with [Gitpod](https://www.gitpod.io/) and deployed to [Cloudflare Pages](https://pages.cloudflare.com).

My website is largely inspired by Google's abandoned 'Plus' service. In a nutshell, they claimed that they have enough information to identify valid authors. However, I want to continue with my own version because:
- It's my only acceptable form of communication from people not already on my Contacts List (once on there, I accept email, text, phone, or anything you want).
- It's nice to provide information about me to interested parties that don't have Google's resources.
- I like to see everything I've contributed to on the Internet in one place.
- I'd like to develop this as a template for other Internet contributors.

## How to contact Keith Taylor

- Just start a [New Issue](./issues/new/choose)

## How to collaborate on content

- Just start a [New Issue](./issues/new/choose)

## Develop

- I anticipate website users will contribute by commenting on, or adding new issues.
- I hope Jamstack and GitHub developers will guide me however they can. Because I have lots to learn about most aspects of using this model as I transmigrate from WordPress.

## Credits

I could not have got this far without the wonderful gift of [Site In A Box (SIAB) from Shane Robinson](https://github.com/11ta/11ta-template).

## ToDo

- Move technical development to a duplicated template repo and refocus this on improving content for Keith Taylor
- resolve dependency issues. Note 220329, started trying to address some errors using Gitpod Terminal. Specifically `npx browserslist@latest` --update-db and `npm audit fix --force`
- Documentation note: I think dependencies problems might be due to several issues. I've just retried updating via Gitpod. Only to have the succesful build fail when deployed to Cloudflare Pages. After searching for "Cloudflare Pages" plus the error message, I found https://www.brycewray.com/posts/2021/10/gems-in-rough-10/. Eventually, I noticed from the update notes in date sequence that the solution was to change NODE_VERSION in Cloudflare Pages Environment Variables. ~~But retrying deployment does not reflect the changed settings.~~ So hopefully, this edit will force a new build correctly using node v16.13.2.
Correction: There are separate Cloudflare Pages Environment Variables for Production and Development, which I didn't scroll down to see. So the general solution to `Error [ERR_UNSUPPORTED_ESM_URL_SCHEME]: Only file and data URLs are supported by the default ESM loader` is to check the version of node.js befoer anything else.
