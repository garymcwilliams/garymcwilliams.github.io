Gary's jekyll github pages
==========================

## Background

Source for the website

## Installation on centos (e.g. Virtualbox):
    gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
    \curl -sSL https://get.rvm.io | bash -s stable
    . ~/.bash_profile
    rvm install ruby-2.4
    gem install jekyll bundle
    bundle update
    cp /vagrant/temp/*gmail* ~/.ssh
    cp /vagrant/temp/config ~/.ssh
    chmod 600 ~/.ssh
    cd ~
    mkdir gary
    cd gary
    git clone git@ssh.github.com:garymcwilliams/garymcwilliams.github.io.git

