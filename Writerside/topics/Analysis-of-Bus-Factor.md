# Analysis of Bus Factor

Bus factor is a metric that denotes the resilience of the project to sudden engineer turnover. Bus factor is the minimal number of engineers that have to be "hit by a bus", or leave the project, for it to stall.

By analyzing the history of code contributions, we can identify the files and subsystems at risk of stalling in the event of developer turnover. We believe that bus factor analysis is a good starting point to work on enabling the collaboration tools to use version control history data to assist with organization of teamwork.

The goal of this project at this stage is to evaluate the viability of bus factor analysis as a user-facing feature in one of JetBrains projects.

## Artifacts

<tabs>
<tab title="bus-factor-deploy">

[Repository](https://github.com/JetBrains-Research/bus-factor-explorer) 🚀[Demo](https://bus-factor.labs.jb.gg/)

This demo service is meant to enable everyone at JetBrains to see the results of bus factor analysis for every repository hosted on Space.

How it works:
1. You choose a repository from Space.
2. Our service loads the repository and calculates and stores the bus factor report.
3. The report is available to view.

</tab>
<tab title="bus-factor-explorer">

<a href="https://github.com/JetBrains-Research/bus-factor-explorer"><img src="gh.png" alt="GitHub logo" width="20"/> Repository</a>

<chapter title="About">
<p>
  A web app for exploring Bus Factor of GitHub projects by analyzing the commit history.
</p>
<p>
<b>bus-factor-explorer</b> provides an interface and an API to compute, export, and explore the Bus Factor metric via treemap visualization, turnover simulation mode, and interactive charts. It supports repositories hosted on GitHub and enables functionality to search repositories and process multiple repositories at the same time.
</p>
<p>
  Our tool enables the users to identify the files and subsystems at risk of stalling in the event of developer turnover by analyzing the commit history.
</p>
<p>
  Demo is available on <a href="https://www.youtube.com/watch?v=uIoV79N14z8">YouTube</a>.
</p>
</chapter>

</tab>
<tab title="ASE ‘23: Bus Factor Explorer">
<p><a href="https://www.overleaf.com/project/6464f27ee924874909b258cc">Overleaf</a></p>
<p>ASE'23 Tool Demo Track (ASE'23 Demo)</p>
<chapter title="Abstract">
<p>
  Bus factor (BF) is a metric that tracks knowledge distribution in a project. It is the minimal number of engineers that have to leave for a project to stall. Despite the fact that there are several algorithms for calculating the bus factor, only a few tools allow easy calculation of bus factor and convenient analysis of results for projects hosted on Git-based providers.
</p>
<p>
  We introduce Bus Factor Explorer, a web application that provides an interface and an API to compute, export, and explore the Bus Factor metric via treemap visualization, simulation mode, and chart editor. It supports repositories hosted on GitHub and enables functionality to search repositories in the interface and process many repositories at the same time. Our tool allows users to identify the files and subsystems at risk of stalling in the event of developer turnover by analyzing the VCS history.
</p>
<p>
  The application and its source code are publicly available on GitHub at https://github.com/JetBrains-Research/bus-factor-explorer. The demonstration video can be found on YouTube: https://youtu.be/uIoV79N14z8
</p>
</chapter>
</tab>
<tab title="ICSE-SEIP '22: Bus Factor In Practice">
<p>Test.</p>
</tab>
</tabs>

## Changelog

- **Bus Factor Explorer accepted at ASE ’23**

  Comment on the change
- **New release of bus-factor-deploy is available**

  See: https://aaaa/
- **Bla bla bla bla!**

  Wow such bla bla bla