---
title: Menu
---
{% assign 1stPost = "./2023-06-30-my-first-post.md" %}
{% assign date = 1stPost | read_yaml | date %}

{% assign 2ndPost = "./2023-06-30-my-second-post.md" %}
{% assign date = 2ndPost | read_yaml | date %}

{% assign 3rdPost = "./2023-07-01-my-third-post.md" %}
{% assign date = 3rdPost | read_yaml | date %}

{% assign 4thPost = "./2023-07-01-my-4th-post.md" %}
{% assign date = 4thPost | read_yaml | date %}



Hello World! This is an example site hosted with Github Pages using a theme with Jekyll.
Looking good


|Posts | Date|
|:-        |:-      |
|[My First Post](./2023-06-30-my-first-post.html)|    {{ 1stPost.date }}|
|[My Second Post](./2023-06-30-my-second-post.html)|  {{ 2ndPost.date }}  |
|[My Third Post](./2023-06-30-my-third-post.html)|  {{ 3rdPost.date }}  |
|[My Fourth Post](./2023-06-30-my-4th-post.html)|  {{ 4thPost.date }}  |
