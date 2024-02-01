# mdbook-template

A template repository for publicly available documentations.

#### Setup

- Create a new repository from mdbook-template.
  - https://github.com/typescripto/mdbook-template/generate
- Configure your GitHub Pages source.
  - https://github.com/typescripto/mdbook-template/settings/pages
  - Use the branch `gh-pages`
  - Use the folder `/ (root)`
- Configure your `book.toml` file.
  - Set the authors, title, description, updated repository urls, cname.

#### Usage

```sh
# navigate to book folder
cd ./book/

# mdbook install
bash ./mdbook-install.sh

# mdbook development
./mdbook serve

# mdbook production
./mdbook build
```

#### References

- https://rust-lang.github.io/mdBook/
- https://rust-lang.github.io/mdBook/format/summary.html

#### License

MIT