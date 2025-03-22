---
layout: default
title: Archive
---

# Publications

Here you can see a little bit about what I used to work on.

---

## How Successful Are Open Source Contributions From Countries With Different Levels of Human Development?

In this article we studied whether developers’ locations relate to the outcome of a pull request (PR). Our results suggest that developers from countries with low human development indexes perform a small fraction of the overall PRs and are the ones that face rejection the most.

Access it [here](https://ieeexplore.ieee.org/abstract/document/8870152).

-----

## Continuous Integration Theater

Background: Continuous Integration (CI) systems are now the bedrock of several software development practices. Several tools such as TravisCI, CircleCI, and Hudson, that implement CI practices, are commonly adopted by software engineers. However, the way that software engineers use these tools could lead to what we call “Continuous Integration Theater”, a situation in which software engineers do not employ these tools effectively, leading to unhealthy CI practices. Aims: The goal of this paper is to make sense of how commonplace are these unhealthy continuous integration practices being employed in practice. Method: By inspecting 1,270 open-source projects that use TravisCI, the most used CI service, we quantitatively studied how common is to use CI (1) with infrequent commits, (2) in a software project with poor test coverage, (3) with builds that stay broken for long periods, and (4) with builds that take too long to run.

Access it [here](https://ieeexplore.ieee.org/abstract/document/8870152).

-----

## How Do Bot Developers Perceive Bot Development? A Survey

Software bots are becoming more and more popular,  this is due to the fact that they are a tool that can be used in different contexts.  With this, software developer has more interest in developing bots, however they may have to face challenges intrinsic to the development of bot software.  With this, we seek to understand the profile of bot developers, what motivates them, or what challenges  they  face  when  dealing  with  bot  development.   To  shed  an  initial light on this direction,we conducted a survey with 43 Github users who have been involved (showingtheir interest or actively contributing to) in bot software projects.

Access it [here](https://sol.sbc.org.br/index.php/washes/article/view/6405).

-----

## Expecting the Unexpected: Distilling Bot Development, Challenges, and Motivations

Software bots are becoming an increasingly popular tool in the software development landscape, which is particularly due to their potential of use in several different contexts. More importantly, software developers interested in transitioning to bot development may have to face challenges intrinsic related to bot software development. However, so far, it is still unclear what is the profile of bot developers, what motivate them, or what challenges do they face when dealing with bot development. To shed an initial light on this direction, we conducted a survey with 43 Github users who have been involved (showing their interest or actively contributing to) in bot software projects.

Access it [here](https://ieeexplore.ieee.org/document/8817003).

-----



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
