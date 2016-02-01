# Build Jekyll

Use local Jekyll server for testing
	
    jekyll serve --detach

Build the jekyll site (in folder *_site*)
	
    jekyll build --watch

# Publish on server

When everything is ok: `add` and `commit` changes. Then push to Git repository. 
The site will be build on the server with Jekyll and this script: <https://git.pr.cx/spamty/build-sites>