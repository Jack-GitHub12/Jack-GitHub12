# Jack-GitHub12

![Profile Views](https://komarev.com/ghpvc/?username=Jack-GitHub12)

Welcome to my GitHub profile! I am a passionate developer with experience

## Recent Repositories

Here are my most recent repositories:

{% for repo in site.github.public_repositories limit:5 %}
- [{{ repo.name }}]({{ repo.html_url }}): {{ repo.description }}
{% endfor %}

## Contributions

I am always looking for ways to contribute to open source projects

