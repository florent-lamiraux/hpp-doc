# Website for the [Humanoid Path Planner](http://humanoid-path-planner.github.io/hpp-doc/index.html) software

## Updating the website
The website can be locally built by installing `jekyll`:
```bash
sudo apt-get install gem ruby ruby-dev
bundler install
```

and serving the website:
```bash
bundle exec jekyll serve --incremental --safe
```

The locally-built website is the available at [http://localhost:4000/hpp-doc/](http://localhost:4000/hpp-doc/)
