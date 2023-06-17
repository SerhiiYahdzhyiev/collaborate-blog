# The Collaboration Blog

An exercise for Computer Science Lab students to practice the collaboration on GitHub.

## Instructions for collaborators

### 1. Fork the repository

If you dont know how to fork repos check out the following resources:

[https://www.howtogeek.com/759384/how-to-fork-a-github-repository/](https://www.howtogeek.com/759384/how-to-fork-a-github-repository/)

[https://www.youtube.com/watch?v=XTolZqmZq6s](https://www.youtube.com/watch?v=XTolZqmZq6s)

[https://docs.github.com/en/get-started/quickstart/fork-a-repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

Some of these links also cover a topic of managing a fork and syncing it with original repository.

### 2. Create new branch for your article

### 3. Create an article

As the content is not important for this exercise you can copy existing article or generate one with Chat GPT or whatever.
Than take an `article.html` file from the `templates` folder and copy it to the `articles` folder.
Change it name to any name of your choice. Than replace the parts of the template html file with your content. Most places to replace are surrounded by curly braces like `{Your Name}`.
All content of your article has to go inside `<div class="article-body"></div>`. Pragraphs should be wrapped with `<p></p>` and headings with `<h3></h3>` or `<h4></h4>`.
Don't worry about the styles, the will be applied automatically.

### 4. Create an article thumbnail inside `index.html`

Just copy this block and insert it inside the div with class `articles-list` (don't forget to replace required values with your own)

```
          <div class="article-thumbnail">
            <h3 class="article-thumbnail_title">Article Title</h3>
            <p class="article-thumbnail_author">by Your Name</p>
            <a href="/articles/your_file_name.html">Read</a>
          </div>
```

### 4. Commit and push your changes to your fork.

### 5. Create a pull request to the main branch of an original repository

But don't merge it, I will do it myself after giving a feedback to your pull requests.
