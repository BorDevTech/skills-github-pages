---
title: Menu
---
{% assign 1stPost = "./2023-06-30-my-first-post.md" %}
{% assign 1stPostDate = 1stPost | read_yaml | date: "%B %d, %Y %H:%M %p %Z" %}

{% assign 2ndPost = "./2023-06-30-my-second-post.md" %}
{% assign 2ndPostDate = 2ndPost | read_yaml | date: "%B %d, %Y %H:%M %p %Z" %}

{% assign 3rdPost = "./2023-07-01-my-third-post.md" %}
{% assign 3rdPostDate = 3rdPost | read_yaml | date: "%B %d, %Y %H:%M %p %Z" %}

{% assign 4thPost = "./2023-07-01-my-4th-post.md" %}
{% assign 4thPostDate = 4thPost | read_yaml | date: "%B %d, %Y %H:%M %p %Z" %}



Hello World! This is an example site hosted with Github Pages using a theme with Jekyll.
Looking good


|Posts | Date|
|:-        |:-      |
|[My First Post](./2023/06/30/my-first-post.html)|    {{ 1stPostDate }}|
|[My Second Post](./2023/06/30/my-second-post.html)|  {{ 2ndPostDate }}  |
|[My Third Post](./2023/07/01/my-third-post.html)|  {{ 3rdPostDate }}  |
|[My Fourth Post](./2023/07/01/my-fourth-post.html)|  {{ 4thPostDate }}  |
