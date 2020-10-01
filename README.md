**About Dashbuilder**

Dashbuilder is a full featured web application which allows non-technical users to visually create business dashboards.
Dashboard data can be extracted from heterogeneous sources of information such as JDBC databases or regular text files.

dashbuilder-website
===================

Sources for the website http://www.dashbuilder.org

# How to build with Dashbuilder's Awestruct:

Follow the instructions of Awestruct's [getting started guide](http://awestruct.org/getting_started/).

First set up your environment correctly using the following code:

    $ curl -L https://get.rvm.io | bash -s stable --ruby=1.9.3
    $ gem install awestruct bundler
    $ rake setup

Then build your website (before and after your changes):

    $ rake clean build
    $ firefox _site/index.html

And publish your changes:

    $ rake publish

And that's it!
Happy coding😄
