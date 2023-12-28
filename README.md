# To Test Locally:

## Root Page

`hugo --config ./config/root/hugo.yaml -w server`

## For Blog
`hugo --configDir ./config/blog -w server`

## To test as it would be if being displayed on Cloudflare

- Run: `hugo --config ./config/root/hugo.yaml && hugo --configDir ./config/blog && hugo server -c ./public -w `
