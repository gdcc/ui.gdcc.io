# ui.gdcc.io

The source for https://ui.gdcc.io, the website for the Frontend Development Interest Group.

## Contributing

Before committing changes to the website, build it locally to make sure everything looks fine with:

```
bundle install
```

Then run the server with:

```
bundle exec jekyll serve
```

You should be able to see the site at <http://localhost:4000>

If you prefer running the site in Docker, you can try this:

```
./run.sh
```

To run with docker and allow incremental updates to the site, use:

```
./run-incremental.sh
```
