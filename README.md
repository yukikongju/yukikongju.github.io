# Notes on the website

How to run the website locally: `bundle exec jekyll serve `

## How the site is built

Read [this](https://jekyllrb.com/docs/structure/)

- we can create new page using on of the templates inside `_layouts/`
- we can access directory file with `{{ site.<directory> }}`
    * Ex: for `_posts`, we would have `{{ site.posts }}`
- we can nest pages inside each other by using `{{% include_relative <filename> %}}`
    * Ex: 
- we can add plugins 
    * [Pagination](https://shivabhusal.github.io/jekyll-paginator/)
	+ Edge case with one page. Add it once we have more posts
	+ Note: `jekyll-paginate-v2` supports pagination outside `index.html` 
	  file but is not supported by github pages

- to add more projects to the `projects.md` page, go to `_data/projects.yml`



# ToDos

- [ ] Add pagination with `jekyll-paginate`
- [ ] Filter posts by date
- [ ] filter posts by tags using `jekyll-tagging`
- [X] Finish About Me for each sessions (Autumn 2021)
- [X] render projects from `_data/projects` instead of manually


## Ressources

- [Gravity Template](https://github.com/hemangsk/Gravity)
- [Pagination in jekyll](https://chrisphillips-cminion.github.io/jekyll/2019/06/26/JekyllPagination.html)
- [Creating tag pages](https://anavarre.net/rebuilding-my-blog-with-jekyll/)
- [Creating menu and subsections](https://www.freecodecamp.org/news/hugo-vs-jekyll-battle-of-static-site-generator-themes/)
- [datafiles and subfolders](https://jekyllrb.com/docs/datafiles/)
- [Collections](https://ben.balter.com/2015/02/20/jekyll-collections/)

