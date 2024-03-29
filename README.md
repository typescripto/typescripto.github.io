# typescripto.github.io

A template repository for publicly available documentations.

#### Setup

- Create a new repository from typescripto.github.io.
  - https://github.com/typescripto/typescripto.github.io/generate
- Configure your GitHub Actions permissions.
  - https://github.com/typescripto/typescripto.github.io/settings/actions
  - Under "Workflow permissions", select "Read and write permissions", then save.
- Configure your GitHub Pages source.
  - https://github.com/typescripto/typescripto.github.io/settings/pages
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