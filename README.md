# Resume Template

[![](https://badgen.now.sh/badge/published/now/purple)](https://zeit.co/about)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

Generate resume based on only **markdown syntax** with **emoji**.
And publish generated resume with [now](https://github.com/zeit/now-cli) on the web.

## Examples

- [jbee-resume](https://jbee-resume.now.sh/) - _my resume_

## If you...

If you want to create your own resume with using this repository, follow the steps below.

```bash
# Setup
$ git clone https://github.com/JaeYeopHan/resume my-resume
$ cd my-resume
$ npm install

# For publishing,
$ npm install -g now

# Change data in `templates.resume.mdx` with markdown syntax.
$ code .
# Writing resume in resume.mdx file on your favorite editor.

# Prepare to publish.
# In package.json, change the alias to your name.
$ npm run now-publish
```

> It's done!

## Development

- This repository is consist of
  - [mdx](https://github.com/mdx-js/mdx)
  - [remark-emoji](https://github.com/rhysd/remark-emoji)
- You can customize template in `components` directory.

## LICENSE

[MIT](https://github.com/JaeYeopHan/resume/blob/master/LICENSE)
