# Non-blocking services with Mojolicious

## About this Course

The course will introduce and prepare the student to implement, troubleshoot, and debug non-blocking clients and web-services quickly and succinctly, giving apps unprecedented scalability, handling 100s and even 1000s of effectively simultaneous actions per process.

You'll learn why non-blocking apps are important, how to implement them, and learn the potential pitfalls you'll run into and how to avoid them.

As a bonus, you will also learn how to use the latest Mojolicious sister project, **Mojo::Pg**! Understand usage and some common pitfalls that you would otherwise run into.

## Audience Profile

This course is designed for developers who have a knowledge of web development technologies, and fall into any of the following categories:

* Never made use of non-blocking web apps
* Made some usage of non-blocking, but are a little unclear how it all works
* Ever asked yourself, what is that Delay thingy?

## At Course Completion

Upon completion of the course, you will be able to:

* Write non-blocking client scripts
* Write non-blocking server app
* Explain how to design a maintainable non-blocking app
* Begin converting blocking apps to non-blocking
* Understand how to use Postgres from Perl in a non-blocking fashion

## Prerequisites

### Equipment

This course is designed for Bring Your Own Device (BYOD).  You must
   have a mobile workstation capable of wireless networking.

### Experience/Skill

Students are expected to have a basic familiarity with Perl and web development. For those that need to brush up, http://qntm.org/files/perl/perl.html is an accessible, free resource. Skimming over the tutorial at http://mojolicio.us/perldoc/Mojolicious/Lite and the first four guides listed on http://mojolicio.us/perldoc/ will do.

We also recommend that you have some experience with SQL. It's not strictly required, but you will get more out of the course if you do.

### Software

Students are recommended to bring laptops running OSX or Linux. Windows will work for much of the lab assignments, though you'll have to account for any platform-specific differences.

Please arrive with the following items installed and ready to go:

1. Running Perl v5.20+
4. Installation of PostgreSQL database
2. Latest version of Mojolicious
3. Latest version of App::cpanminus
4. Latest version of Mojo::Pg

For those using versions of Perl below 5.20, http://perlbrew.pl is recommended. Please contact us if you have questions or need help arriving prepared.

You can install Mojolicious and App::cpanminus using the following command:

	curl -L cpanmin.us | perl - Mojolicious Modern::Perl App::cpanminus

### PostgreSQL

If running OSX, the easiest way to get up and running is to use [Postgres App](http://postgresapp.com/).

For other platforms, take a look at [http://www.postgresql.org/download/]()

### Determining minimum skill level
If the student can answer these questions easily, they are ready for the course. If not, the student can get up to speed using their favorite search engine. The student needs to have created at least one simple client script using Mojo::UserAgent and one simple daemon using Mojolicious or Mojolicious::Lite.

* What is a URL?
* What is a URL parameter? How is it specified within a GET request?
* What is the difference between a POST and a GET request
* What is an API?
* What's the difference between a web page and a web application?
* What would a database be used for?
* How do you select a row from a database?
* How do you update a row in a database?
* How is a Perl script executed from a terminal?
* How do you create and call a Perl subroutine?
* How do you instantiate an object?


## Course Outline

Course will be split up into lecture and lab sessions. Some labs, the students will work together. The instructor will be available for questions during the course of all labs. If the instructor is asked questions during the lecture, he will answer based on the fanciness of the respective student's outfit. Glitter definitely helps.

### Morning Lecture (1.5 hours)

#### Non-blocking theory

* Why it's important
* High level explanation how Mojolicious does it
* Goals of non-blocking behavior - performance vs scalability

#### Implementation examples and walk-through

* Sleeping without blocking
* Web scraping with Mojo::UserAgent
* Demonstration of difference between blocking and non-blocking web scraping
* Using callbacks and their drawbacks
* More advanced and maintainable alternative to callbacks
* Serial execution: alternative to callbacks

### Break

### Morning Lab (1.5 hours)

* Implementing non-blocking sleep
* Web scraping with callbacks
* Embedded callbacks
* Non-blocking without callbacks

### Lunch

### Afternoon Lecture (1.5 hours)

#### Implementation examples and walk-through

* Using non-blocking on the server side
* Server being an abstraction for remote non-blocking APIs
* Concurrent and serialized non-blocking calls
* Authentication: using blocking bridges vs using non-blocking bridges
* Converting blocking applications to non-blocking: techniques and gotchas
* Troubleshooting non-blocking, how it differs from blocking
* Mojo::Pg usage, how it differs from DBI
* Common pitfalls in Mojo::Pg

### Break

### Afternoon Lab (1.5 hours)

* Implementing a non-blocking server API that consumes remote APIs
* Implementing non-blocking authentication
* Implementing concurrent and serial flows, and mixes of the two
* Implementing database queries with Mojo::Pg

#### Troubleshooting practice

* Troubleshooting provided non-blocking problems
* Practicing troubleshooting techniques

## Written Material

Student will receive written material covering the topics of the class.

## Coverage

Coverage of material may change depending on the pace of the students. Some topics may be skipped, but will be included in written material provided to the student.