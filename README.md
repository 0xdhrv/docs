# Mintlify Starter Kit

<p>
  <a href="https://github.com/0xdhrv/docs/stargazers">
    <img alt="GitHub stars" src="https://shieldcn.dev/github/stars/0xdhrv/docs.svg?variant=secondary" />
  </a>
  <a href="https://github.com/0xdhrv/docs/commits">
    <img alt="Last commit" src="https://shieldcn.dev/github/commits/0xdhrv/docs.svg?variant=secondary" />
  </a>
</p>

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to autopropagate changes from youre repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
