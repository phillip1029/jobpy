<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
![Version](https://badge.fury.io/gh/rodrez%2FJobs-and-Skills.svg)
![Issues](https://img.shields.io/github/issues/rodrez/jobpy)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Python Version](https://img.shields.io/pypi/pyversions/jobpy)



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/rodrez/jopby">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Jobpy</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/rodrez/jobpy/issues">Report Bug</a>
    ·
    <a href="https://github.com/rodrez/jobpy/issues">Request Feature</a>
  </p>
</p>





Jobpy
========

What is Jobpy?
--------------

Jobpy is a library built with Python to pull job posting from all over the internet.
The idea behind is was to analyze the different characteristics of the job posting, like
skills required, experience, etc. It can also be used to apply to the search jobs although
the fetaure has not been released yet.


Look how easy it is to use:

```
   [In]: from jobpy.search import cb_job_search as cb
   [In]: jobs_in_la = cb.start_search('software developer', 'Los Angeles')
   [In]: print(jobs_la)
   
   [Out]: 'software_developer_job_los_angeles.csv'
```
>>>>

Table of Contents
-----------------

- [Features](#Features)
- [Installation](#Installation)
- [FAQS](#FAQS)
- [Contributing](#Contributing)
- [Support](#Support)
- [License](#License)

Features
--------

- Easy Job Search
- Great Performance
- Export to CSV or MD Table
- Organized data
- File converter support
- Apply to jobs easily

>>>>

Installation
------------

At the command line::

    pip install jobpy

>>>>

FAQS
----

1. How do we performed the search.

   - I used Scrapy, Beutiful Soup to perform the search.

2. How often does jopby gets updated?

   - I am currently releasing weekly updates.
   - NOTE: I'm currently a full time employee and part time student so I spend the rest ofvmy free time coding to expand my knowledge. Help is always appreciated.

3. Will this become something more?

   - I would like this to become an Open Source website that could help developers like me find their dream job.

>>>>

Contributing
------------

   To get started...

- Issue Tracker: ![https://img.shields.io/github/issues/rodrez/jobpy](github.com/rodrez/jobpy/issues)
- Source Code: !()[github.com/rodrez/jobpy]

**Step 1**

- **Option 1**
    - 🍴 Fork this repo!
- **Option 2**
    - 👯 Clone this repo to your local machine using ![https://github.com/rodrez/jobpy.git](https://github.com/rodrez/jobpy.git)

**Step 2**

- **HACK AWAY!** 🔨🔨🔨

**Step 3**

- 🔃 Create a new pull request using ![https://github.com/rodrez/jobpy/compare/](https://github.com/rodrez/jobpy/compare/).

>>>>

Support
-------

If you are having issues, please let us know.
We have a mailing list located at: fabian.rodrez@gmail.com

It's easier to reach me on Twitter @Rodrez_

License
-------

The project is licensed under the MIT license.
