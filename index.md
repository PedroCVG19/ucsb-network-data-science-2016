---
layout: default
---

# UCSB Network Data Science Boot Camp - Directory

## Adding yourself

Students, introduce yourself via a `GITHUB_USERNAME.json` file under the [`_data/{{ site.current_term }}/`](https://github.com/{{ site.git_owner }}/{{ site.git_repo }}/tree/gh-pages/_data/{{ site.current_term }}) directory, and submit via pull request. Here's an example:

```javascript
// _data/{{ site.current_term }}/afeld.json
{
 "emoji": "dancer",
 "introduction": "Developer at 18F by day, dancer by night."
}
```

Using the format above, replace with your own `emoji` (choose from [this list](http://www.emoji-cheat-sheet.com/)) and `introduction`.
## Students

{% include students.html %}
