Student managed website for Department of Computer Science Society, University of Delhi.

Built using [Jekyll](https://jekyllrb.com/) and [Tailwind Css](https://tailwindcss.com/).

# Development

## Requirements

-   Git
-   [Ruby](https://www.ruby-lang.org/en/)
-   [Nodejs](https://nodejs.org/en/)
-   Npm

## Installation

```bash
# clone this repository
git clone https://github.com/csdu/csdu-jekyll-website

# go to working directory
cd csdu-jekyll-website

# install ruby dependencies
gem install bundler
bundle install

# install node dependencies
npm install
```

## Start local dev server

```bash
# to start local dev server on http://localhost:4000
npm run dev

# or

# to start local dev server with live reload (watch for any file changes)
npm run watch
```

## Build for production

```bash
npm run build
```
