---
layout: default
title: Archive
---

# Publications

Here you can find my publications.

-----

## How Do Bot Developers Perceive Bot Development? A Survey

Software bots are becoming more and more popular,  this is due to
the fact that they are a tool that can be used in different contexts.  With this,
software developer has more interest in developing bots, however they may have
to face challenges intrinsic to the development of bot software.  With this, we
seek to understand the profile of bot developers, what motivates them, or what
challenges  they  face  when  dealing  with  bot  development.   To  shed  an  initial
light on this direction,we conducted a survey with 43 Github users who have
been involved (showingtheir interest or actively contributing to) in bot software
projects.

Access it [here](https://sol.sbc.org.br/index.php/washes/article/view/6405).

-----

## Continuous Integration Theater

Background: Continuous Integration (CI) systems are now the bedrock of several software development practices. Several tools such as TravisCI, CircleCI, and Hudson, that implement CI practices, are commonly adopted by software engineers. However, the way that software engineers use these tools could lead to what we call “Continuous Integration Theater”, a situation in which software engineers do not employ these tools effectively, leading to unhealthy CI practices. Aims: The goal of this paper is to make sense of how commonplace are these unhealthy continuous integration practices being employed in practice. Method: By inspecting 1,270 open-source projects that use TravisCI, the most used CI service, we quantitatively studied how common is to use CI (1) with infrequent commits, (2) in a software project with poor test coverage, (3) with builds that stay broken for long periods, and (4) with builds that take too long to run. Results: We observed that 748 (~60%) projects face infrequent commits, which essentially makes the merging process harder. Moreover, we were able to find code coverage information for 51 projects. The average code coverage was 78%, although Ruby projects have a higher code coverage than Java projects (86% and 63%, respectively). However, some projects with very small coverage (~4%) were found. Still, we observed that 85% of the studied projects have at least one broken build that take more than four days to be fixed. Interestingly, very small projects (up to 1,000 lines of code) are the ones that take the longest to fix broken builds. Finally, we noted that, for the majority of the studied projects, the build is executed under the 10 minutes rule of thumb. Conclusions: Our results are important to an increasing community of software engineers that employ CI practices on daily basis but may not be aware of bad practices that are eventually employed.

Access it [here](https://ieeexplore.ieee.org/abstract/document/8870152).



<!--{% assign postsByYearMonth = site.posts | group_by_exp: "post", "post.date | date: '%B %Y'" %}
{% for yearMonth in postsByYearMonth %}
  <h2>{{ yearMonth.name }}</h2>
  <ul>
    {% for post in yearMonth.items %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
-->
