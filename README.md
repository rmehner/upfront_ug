# up.front.ug

up.front is a monthly meetup
for webdesigners & frontend developers in Berlin

* **Website**: http://up.front.ug
* **Twitter**: http://twitter.com/upfront_ug

---

 - Please push to gh-pages branch for website updates
 - If you would like to give a talk at one of our next meetups, please get in touch or fill out our call for proposals.

---

# Contributing

If you would like to contribute to our site, please fork the project and then submit a pull request. We appreciate your help and will try to get back to you as soon as possible.

# Run jekyll

`$ jekyll serve watch`

If you want to open the site from an external device on your local network, run jekyll with:

`$ jekyll serve --host 0.0.0.0`

If Ruby complains about a `Gem::LoadError`, try putting `bundle exec` in front of the command you’re trying to run: `$ bundle exec jekyll serve watch`, for example.

# Page build failure

If you receive a generic page build failure, try rebuilding by pushing an empty commit:

`$ git commit -m 'rebuild pages' --allow-empty`

`$ git push`
