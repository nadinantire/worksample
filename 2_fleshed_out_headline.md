# 1 Guide Assumptions
This guide is designed for beginners who want to get started with a Rails application from scratch. It does not assume that you have any prior experience with Rails.

Rails is a web application framework running on the Ruby programming language. If you have no prior experience with Ruby, you will find a very steep learning curve diving straight into Rails. There are several curated lists of online resources for learning Ruby:

    Official Ruby Programming Language website
    List of Free Programming Books

Be aware that some resources, while still excellent, cover versions of Ruby as old as 1.6, and commonly 1.8, and will not include some syntax that you will see in day-to-day development with Rails.

# 2 Introduction to rails

Ruby on Rails. . .by now most people have heard the hype about it. It promises more effective code, total object orientation, and true MVC architecture to say the least. As far as my own personal experience, it has been all that and more. The code is beautiful, easy to maintain, and edit. In a recent project I was working on, it took me less than 10 hours to do the application, as compared to at least double that if I was writing in PHP.

I've heard a lot of web developers that know other languages, usually ASP or PHP, that want to learn Ruby on Rails, but just don't know where to get started. From personal experience, I know it is very different from PHP. Personally, I learned Ruby on Rails less than a year ago, and have had few to no problems with it so far. If you haven't already, I highly recommend hopping on board with the up and coming web framework, Ruby on Rails!

What is HTML?
 HTML is the language in which most websites are written. HTML is used to create pages and make them functional.
 HTML was first created by Tim Berners-Lee, Robert Cailliau, and others starting in 1989. It stands for Hyper Text Markup Language.
 Hypertext means that the document contains links that allow the reader to jump to other places in the document or to another document altogether. The latest version is known as HTML5.A Markup Language is a way that computers speak to each other to control how text is processed and presented. To do this HTML uses two things: tags and attributes.
 Ref:Author:Frank Moraes
     https://html.com/#ixzz6dx9OVQnt

# 2.1 rails definition
Rails is a web application development framework written in the Ruby programming language. It is designed to make programming web applications easier by making assumptions about what every developer needs to get started. It allows you to write less code while accomplishing more than many other languages and frameworks. Experienced Rails developers also report that it makes web application development more fun.

Rails is opinionated software. It makes the assumption that there is a "best" way to do things, and it's designed to encourage that way - and in some cases to discourage alternatives. If you learn "The Rails Way" you'll probably discover a tremendous increase in productivity. If you persist in bringing old habits from other languages to your Rails development, and trying to use patterns you learned elsewhere, you may have a less happy experience.

The Rails philosophy includes two major guiding principles:

    Don't Repeat Yourself: DRY is a principle of software development which states that "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system." By not writing the same information over and over again, our code is more maintainable, more extensible, and less buggy.
    Convention Over Configuration: Rails has opinions about the best way to do many things in a web application, and defaults to this set of conventions, rather than require that you specify minutiae through endless configuration files.

# 2.2 Concepts of Ruby on Rails 
Ruby on Rails follows several principles to help keep it's code sleek and clean. You should try to live by these principles while you're working with RoR to get the most of it. For one, it follows the Agile programming term of DRY (Don't repeat yourself). Obviously, this means that you only write your code once in a certain consistent place. For example, if you need the code to do a certain thing, then you'll put it in a certain place every time.

The second concept that RoR follows is CoC (Conventions over Configuration).This pretty much means that ruby assumes a lot, and explains most of the automatic defaults you'll see ruby generate for us. Instead of you always having to configure everything, in every single project, ruby does it for you automatically.Then, if you want to do something that's unconventional, you simply override the sensible defaults that RoR already has in place.This generally leads to less code having to be written.

Advantages of Learning Ruby on Rails:

    It is pretty easy to learn compared to other languages
    Completely Object Orientated
    MVC Architecture
    You don't have to write as much code
    Very extendible
    Open Source
    The community is extremely helpful in answering questions
    Despite being a relatively new framework, it is pretty fully featured, and has very few bugs.

# 3 How the Framework Works
## 3.1 MVC Architecture
MVC Architecture

Rails runs off of MVC Architecture. Basically that means we break up our code into three sections; the model, the view, and the controller. If you'd like to learn more about MVC Architecture be sure to visit the Nettuts MVC introduction tutorial.

## 3.2 Creating a New Rails Project
The best way to read this guide is to follow it step by step. All steps are essential to run this example application and no additional code or steps are needed.

By following along with this guide, you'll create a Rails project called blog, a (very) simple weblog. Before you can start building the application, you need to make sure that you have Rails itself installed.

The examples below use $ to represent your terminal prompt in a UNIX-like OS, though it may have been customized to appear differently. If you are using Windows, your prompt will look something like c:\source_code>

## 3.3 Installing Rails

Before you install Rails, you should check to make sure that your system has the proper prerequisites installed. These include:

    Ruby
    SQLite3
    Node.js
    Yarn

3.1.1 Installing Ruby

Open up a command line prompt. On macOS open Terminal.app, on Windows choose "Run" from your Start menu and type 'cmd.exe'. Any commands prefaced with a dollar sign $ should be run in the command line. Verify that you have a current version of Ruby installed:

$ ruby -v
ruby 2.5.0
Rails requires Ruby version 2.5.0 or later. If the version number returned is less than that number, you'll need to install a fresh copy of Ruby.

To quickly install Ruby and Ruby on Rails on your system in Windows, you can use Rails Installer. For more installation methods for most Operating Systems take a look at ruby-lang.org

If you are working on Windows, you should also install the Ruby Installer Development Kit.

### 3.3.2 Installing SQLite3
You will also need an installation of the SQLite3 database. Many popular UNIX-like OSes ship with an acceptable version of SQLite3. On Windows, if you installed Rails through Rails Installer, you already have SQLite installed. Others can find installation instructions at the SQLite3 website. Verify that it is correctly installed and in your PATH:

$ sqlite3 --version
The program should report its version.
### 3.3.3 Installing Node.js and Yarn
Finally, you'll need Node.js and Yarn installed to manage your application's JavaScript.

Find the installation instructions at the Node.js website and verify it's installed correctly with the following command:

$ node --version
The version of your Node.js runtime should be printed out. Make sure it's greater than 8.16.0.

To install Yarn, follow the installation instructions at the Yarn website.

Running this command should print out Yarn version:
yarn -v
If it says something like "1.22.0", Yarn has been installed correctly.

### 3.3.4 Installing Rails
To install Rails, use the gem install command provided by RubyGems:
gem install rails

To verify that you have everything installed correctly, you should be able to run the following:
$ rails --version
If it says something like "Rails 6.0.0", you are ready to continue.

### 3.4 Creating the Blog Application

Rails comes with a number of scripts called generators that are designed to make your development life easier by creating everything that's necessary to start working on a particular task. One of these is the new application generator, which will provide you with the foundation of a fresh Rails application so that you don't have to write it yourself.

To use this generator, open a terminal, navigate to a directory where you have rights to create files, and type:

$ rails new blog

This will create a Rails application called Blog in a blog directory and install the gem dependencies that are already mentioned in Gemfile using bundle install.

If you're using Windows Subsystem for Linux then there are currently some limitations on file system notifications that mean you should disable the spring and listen gems which you can do by running rails new blog --skip-spring --skip-listen.

You can see all of the command line options that the Rails application builder accepts by running rails new -h.

After you create the blog application, switch to its folder:
cd blog

The blog directory has a number of auto-generated files and folders that make up the structure of a Rails application.

# 4 Rails

To begin with, let's get some text up on screen quickly. To do this, you need to get your Rails application server running.

## 4.1 Starting up the Web Server
You actually have a functional Rails application already. To see it, you need to start a web server on your development machine. You can do this by running the following in the blog directory:

$ rails server
If you are using Windows, you have to pass the scripts under the bin folder directly to the Ruby interpreter e.g. ruby bin\rails server.

JavaScript asset compression requires you have a JavaScript runtime available on your system, in the absence of a runtime you will see an execjs error during asset compilation. Usually macOS and Windows come with a JavaScript runtime installed. therubyrhino is the recommended runtime for JRuby users and is added by default to the Gemfile in apps generated under JRuby. You can investigate all the supported runtimes at ExecJS.

This will fire up Puma, a web server distributed with Rails by default. To see your application in action, open a browser window and navigate to http://localhost:3000. You should see the Rails default information page: