# luckym1.github.io

luckym1 github pages site

## Workflow

Work on the dev branch and locally with jekyll. When ready to publish, merge dev into master and push to github. Github will build the site and publish it.

### Install dependencies

Ubuntu:

```bash
sudo apt-get install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler
```

### Jekyll commands for local development

Need to change directory to the `/docs` directory of the repo since that is where github will build from.

```bash
cd docs
```

Build and serve locally with:

```bash
bundle exec jekyll build 
bundle exec jekyll serve
```
