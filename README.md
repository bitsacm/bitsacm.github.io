# BITS-ACM Tech Blog:
* Made with Jekyll and Markdown    
* Link: https://bitsacm.github.io  

#### Local Development
 
 1. Pre-requisites - Ruby (version 2.5 or above) and RubyGems  
    ```
    sudo apt-get install ruby ruby-dev build-essential
    echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
    echo 'export GEM_HOME=$HOME/gems' >> ~/.bashrc
    echo 'export PATH=$HOME/gems/bin:$PATH' >> ~/.bashrc
    source ~/.bashrc
    ```
 2. Install Jekyll
    ```
    gem install jekyll bundler
    ```
 3.  Build and Run on local server to test changes
     ```
     bundle exec jekyll serve
     ```
 Further Links
  - [Jekyll Quick Start Guide](https://jekyllrb.com/docs/quickstart/)
  - Complete guide for [Ubuntu](https://jekyllrb.com/docs/installation/#ubuntu) and [macOS](https://jekyllrb.com/docs/installation/#macOS)
  - How to setup on [Windows](https://jekyllrb.com/docs/windows/)
