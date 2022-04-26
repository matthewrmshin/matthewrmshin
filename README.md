# About Matt

I have over 20 years of software development/engineering experience in a variety
of programming languages including Python, Perl, Java, Fortran, C, C++, Bash,
JavaScript, SQL, etc. I am currently most comfortable working with Python in a
Linux environment, but I am always looking out for challenges and
opportunities to learn something new.

I have led software development activities and developed software solutions
in different teams for a variety of users, from Met Office scientists to
international partners. These software systems have helped keep large computing
resources busy such as the HPC and the Linux clusters, and contributed to the
smooth operation of workflow systems that generate the 24/7 forecasts and other
products over the years. They have helped scientists to develop, build, configure,
and automate complex and resource intensive model applications. I am particular
keen on complexity reduction, always look out for opportunities to streamline
logic and processes.

## Professional Experience

I joined the Met Office in 2002 and has worked there since then.

### 2021/now

*Expert Scientific Software Engineer, Weather Science Research To Operation.*

I am currently working on improving the user experience in managing
and working with large workflow suites for the next generation modelling
systems for research to operational use. Some example recent activities:

- I adviced developers and users on how to modularise large model application
  configuration files, using a YAML processor application I have quickly put
  together.
  See [JCSDA-internal/yamlprocessor](https://github.com/JCSDA-internal/yamlprocessor/).
- I have contributed to C++ model applications to allow them to generate
  configuration schema files at build time.
- I am investigating how to effectively manage releases of large C++ model applications
  that are built from many active projects that are under development by a
  number of partner organisations.
- I am providing advice to scientists on how to manage and organise
  application configurations in workflow suites.
- I am looking at how to manage versioning of run time configurations in a
  rapid development environment.
- I am looking at how to create useful form-based UI for application
  configuration files with schemas with our workflow engine's UI environment.
- I have developed a user experience vision for working with meteorological
  workflow suites and a roadmap to implement the vision. The vision helps to
  drive the conversation with management and stakeholders on how to resourcing
  and prioritisation in the future.

### 2019/2021

*Expert Scientific Software Engineer, Business Group Post Processing Applications.*

In my previous role, I worked on modernising some of our Post
Processing applications.

I led the development of a workflow suite to allow scientists to trial
different new post-processing applications and techniques with many years of
data. The success of this work allowed our scientists to study new ways to
deliver new science capabilities to our customers.

I proposed and demonstrated how to migrate an existing post processing
workflow from running on-premise to running in a serverless architecture on
AWS, to reduce cost and increase flexibility. I developed a prototype that would
automate building, infrastructure creation, and launching the workflow on the fly.

I removed bottlenecks in various application logic to enable an on-demand API
that triggered post processing applications in the backend, reducing the
overall runtime from tens of minutes to a few seconds.

I adviced our scientists on best practice for scientific software development
flow, and helped them solve everyday's software development problems.

### 2002/2019

*Expert Scientific Software Engineer,*  
*Senior Scientific Software Engineer,*  
*NWP Applications Developer, Weather Science IT.*

I worked on many different software projects before that.
Here are some examples.

[metomi/rose](https://github.com/metomi/rose/):
A system to manage configuration for model application runtime, which provided
our scientists with a common environment and a common set of toolkits to work
on and manage their model configurations for robust reproducibility. This
system has been in use operationally for many years. I led the
original design, development and deployment of this system since the
beginning.

[cylc/cylc-flow](https://github.com/cylc/cylc-flow/):
A workflow scheduling system, which provided our scientists, engineers and
system analysts a common environment to run workflow suites to submit jobs on
the HPC and other computing resources, from simple workflows to complex
cycling workflows and from research to operation. This workflow scheduling
system is used by all of Met Office core forecasting workflow suites for
many years. I led and coordinated its development, release and
on-premises deployment from the beginning.

[metomi/fcm](https://github.com/metomi/fcm/):
A wrapper to Subversion and a fully featured build system for modern Fortran
applications. The latter provided   our scientists with a very efficient
environment to compile their code (compared to a traditional `Makefile`
environment) and to reproduce build configurations. Its introduction has
reduced build time of some of our largest science applications from hours
to a few minutes. I wrote this system over a decade ago and it is still in
use today for building our largest science model applications due to its
efficiency and effectiveness.

MOOSE:
The software layer of our massive archive system, providing our users with
a common interface to access our massive archive system. I was a highly
productive member of the original team. I contributed to the design of
the client-server interaction, and implemented the client logic.
The software is still in use after 15 years.

I have also ported applications across several generations of HPC and Linux
clusters, some of which have very different architectures and operating systems.
I have written applications to convert the format of binary data files,
handling fragments of incoming data files on often chaotic schedules,
and handling complex platform specific issues.

## Education

I studied Material Science at Trinity College, University of Oxford.
I gained an MEng (1st Class Honour) in 1998 and a DPhil (aka PhD) in 2002.

[Me @ LinkedIn](https://www.linkedin.com/in/matthewrmshin/)

<!--
**matthewrmshin/matthewrmshin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
