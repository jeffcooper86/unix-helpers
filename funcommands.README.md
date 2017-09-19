Remove matching files from a directory

`ls public/assets | grep .js | sed 's/^/public/assets\//' | xargs rm`
