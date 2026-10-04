# Ōtautahi Transgender Collective

Heya! This is the website for the Ōtautahi Trans Collective. You are likely
looking for our website at [otc.org.nz]. This is the source code for the
website. If you want to contribute, check out the next section.

## Contributing

This assumes knowledge of only HTML and CSS. We go barebones here as it's
simpler when hosting and contributing, and the scope doesn't warrant a
framework. This assumes some knowledge of git, although if you need any more
guidance than in this little guide you may ask another maintainer.

### Setup

Ensure you have [git](https://git-scm.com/install/) and [Node](https://nodejs.org/en/download)
downloaded, and that you've [forked the
repository](https://github.com/OtautahiTransgenderCollective/OTC-Website/fork).
Then clone it into a folder. Once downloaded, run the following commands in a terminal

```sh
# Ensures all git hooks are synced between all people
# Right now this is only checking that code maintains our standard
git config --local core.hooksPath .githooks/
npm install
```

### Developing

Make your changes in your code. Ensure they're centralised and don't span
multiple changes. If you need to, you can use [branches](https://www.geeksforgeeks.org/git/how-to-create-a-new-branch-in-git/).

Before pushing your code up, run `npm run prettier` in a terminal. This
will let you know of any formatting issues in your code. If you want, you can
also run `npm run prettier:format` to automatically fix them for you.

Once you've finished, create a pull request from your fork into the main repo
and someone will look at it.
