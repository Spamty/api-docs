# Spamty API Docs

This is our API documentation which can be viewed here: http://dev.spamty.eu/

## Build

Use local Jekyll server for testing
	
    jekyll serve --detach

Build the jekyll site (in folder *_site*)
	
    jekyll build --watch

Publish the website by uploading the contents of *_site* folder on FTP. 
~~Or upload the complete Jekyll install on GitHub Pages.~~

## .htaccess

To use custom .htaccess files with Jekyll create a file named *htaccess* (without dot) and set permalink to *.htaccess* (with dot).
Same for htpasswd file.

See also: http://newbieonruby.com/jekyll-include-htaccess/

### Example .htaccess file

    ---
    permalink: /apikeys/generator/.htaccess
    ---
    AuthName "INTERNAL DOC" 
    AuthType Basic 
    AuthUserFile /home/dpgfnbmi/public_html/developer/.htpasswd 
    require valid-user

## Notes

Built with 
 * [Jekyll](http://jekyllrb.com/)
 * ~~[GitHub Pages](https://pages.github.com/)~~
 * [Twitter Bootstrap](https://getbootstrap.com/)
 * [Prettify](https://github.com/google/code-prettify/)
