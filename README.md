# Notes on the website

How to run the website locally: `bundle exec jekyll serve `

## How the site is built

- we can create new page using on of the templates inside `_layouts/`
- we can access directory file with `{{ site.<directory> }}`
    * Ex: for `_posts`, we would have `{{ site.posts }}`
- we can nest pages inside each other by using `{{% include_relative <filename> %}}`
    * Ex: 
- we can add plugins 
    * [Pagination](https://shivabhusal.github.io/jekyll-paginator/)
	+ Edge case with one page. Add it once we have more posts




# ToDos

- [ ] Add next pages to blog post
- [ ] Filter posts by date and tags
- [ ] Finish About Me for each sessions (Autumn 2021)
- [ ] Add pagination with `jekyll-paginate`


## Ressources

- [Gravity Template](https://github.com/hemangsk/Gravity)
- [Pagination in jekyll](https://chrisphillips-cminion.github.io/jekyll/2019/06/26/JekyllPagination.html)
- [Creating tag pages](https://anavarre.net/rebuilding-my-blog-with-jekyll/)

