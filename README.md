The idea of the setup is to never have to worry about depencencies because grunt takes care of this. The only external package are node and jekyll. 

# INSTALL
Ensure that npm is installed and ruby is >= 2.1.

Install grunt global:
sudo npm install -g grunt-cli
sudo gem install jekyll-seo-tag
sudo gem install jekyll

Install all depedencies locally (you may need install packages like gcc-c++ first):
npm install --save-dev

# TESTING
jekyll serve

# ISSUES
I: When 'jekyll serve is ran, the pile-driver-operator.css is removed from the \_site directory.
S:
