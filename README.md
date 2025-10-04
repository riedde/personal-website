# personal-website
This is the source code of the personal website of Dennis Ried.

The [former website](https://github.com/riedde/homepageDR) was designed as an application for [eXist-db](https://exist-db.org). The [content](https://github.com/riedde/homepageDRContent) rendered by the application, was encoded in TEI-XML.
This infrastructure was nice, but won't be developed anymore because it is not as easy to handle as a static webpage. In fact, the result was generated dynamically but there wasn't a bigger benefit. So the source coude an the data have been archived and this repository was created.

## Running locally
```
bundle install
bundle exec jekyll serve --livereload
```

The website will be accessible at `http://localhost:4000`

If an error occurres maybe try to reinstall bundler `gem uninstall bundler --all --force && gem install bundler` ([more about](https://stackoverflow.com/questions/78729196/bundle-install-cannot-load-such-file))
