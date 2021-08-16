# Some Engineering Website
[https://some.engineering/](https://some.engineering/)

# Local development
Have [Ruby](https://www.ruby-lang.org/) installed.  

Then
```
$ git clone git@github.com:someengineering/website.git
$ cd website
$ git checkout -b your-feature-branch
$ gem install bundler jekyll
$ bundle exec jekyll serve
```

Open [http://127.0.0.1:4000](http://127.0.0.1:4000) and edit the pages.  

When done
```
$ git push origin your-feature-branch
```
and [open a pull request](https://github.com/someengineering/website/compare) between base `main` and `your-feature-branch`.
