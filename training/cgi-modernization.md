# Modernizing CGI.pm Apps with Mojolicious

## About this Course

Whether you've already decided on Mojolicious as your next generation
web framework, or you're still considering your options, this course
is for you.  In this course, we will take you through all of the
Mojolicious basics, give you the tools and techniques for making sure
you don't miss anything when you modernize, and completely spell out
your deployment options.

The morning session is dedicated to getting you aware of the
Mojolicious web framework environment and what it takes to be
successful in modernizing your web app.  The early afternoon session
takes you into having that fast and responsive web application
experience, and how Mojolicious accelerates you on that path.
Finally, in the last session, we will talk about deployment options
and how to be successful in each of those.

This course is packed with hands-on labs and takeaways that will
catapult your modernization efforts to the next level!

## Audience Profile

This course is designed for developers and system administrators who
are currently maintaining CGI.pm based web applications.  The ideal
learner has at least six (6) months Perl programming experience with
CGI.pm.  Basic understanding of Mojolicious is nice to have but not
required.

## At Course Completion

At course completion, you will be able to:

* Decide where CGI.pm code belongs in a Mojolicious app.
* Understand how to asynchronously 
* Create unit tests using Test::Mojo
* Translate CGI.pm functional code to the Mojolicious framework.
* Translate CGI.pm presentation code to the Mojolicious framework.
* Understand Mojolicious deployment options
* Deploy Mojolicious Apps using Apache and plack
* Deploy Mojolicious Apps using Nginx and plack

## Prerequisites

This course is designed for Bring Your Own Device (BYOD).  You must
have a mobile workstation capable of:

1. Running Perl v5.20+ and the latest version of Mojolicious.
2. Running Apache WWW and Nginx.
3. Wireless networking.

## Course Outline

Each module composes a lecture and lab experience. 

### Module 1: Mojolicious Basics

Mojolicious' architecture isn't new, but the design and implementation
certainly is.  In this module, we will discover all the key parts to
developing web applications with Mojolicious and draw important
relationships to CGI.pm. Through each of these topics, you will become
more familiar with the implementation options that are available to
you.

1. Mojolicious MVC architecture and design.
2. Execution architecture: comparing Mojolicious to CGI.pm.
3. Mojolicious routing and controller basics.
4. Mojolicious rendering basics.
5. Managing static files, images, and client-side scripts.
6. Development environment.

### Module 2: Creating Tests and Refactoring

What's the strategy for migrating to Mojolicious?  If you have an
application that's been in use for quite some time, one of the worst
things you can do is rip functionality out from under your users.  In
this module, we discover how we can discover all your code paths,
replicate behaviors, and the options for transforming your application
over time.

1. Incremental vs. Big Bang Conversion
2. Approaching CGI.pm testing.
3. Converting CGI.pm tests to Test::Mojo
4. Understanding test coverage
5. Refactoring to Mojolicious

### Module 3: The UI and User Experience

CGI applications are notorious for making your browser wait for long
durations.  In this module, you will learn how to leverage Mojolicious
features to make your application be more responsive than ever.

1. Layouts and Templates
2. Aligning controllers with Templates
3. Implementing routes to make javascript asynchronous calls
4. Implementing validation and customizing error pages
5. Increasing throughput with AssetPack

### Module 4: Deploying Mojolicious Apps

Regardless your app is private or public, you need to know your
options for keeping your application humming along.  Just like
anything Perl, you have a wide variety of deployment options available
to you.  In this module, we will enable you to make practical and
situationally-based decisions for your application's infrastructure.

1. Choosing between deployment architectures
2. Apache CGI 
3. Heroku deployment
4. Continuous deployment


Copyright (C) 2015 brian d foy, All Rights Reserved.

