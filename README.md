# GitCloud

Use GitHub for file hosting and indexing

## Usage

### Serving

1. Fork the repo
2. Put files in `files`
3. Create corresponding entries in `_data/gitCloud.yml`
4. Push to a GitHub repo under the branch `gh-pages`

### Clients

Parse all entries within the `<div>` with id = `file-index`

## Example `gitCloud.yml`

This configuration file is an index for the files you wish to serve.

```yml
- href: files/cat.jpg
  name: some cat

- href: files/helloWorld.py
  name: helloWorld
```
