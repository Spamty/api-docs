# .htaccess

To use custom .htaccess files with Jekyll create a file named *htaccess* (without dot) and set permalink to *.htaccess* (with dot).
Same for htpasswd file.

See also: http://newbieonruby.com/jekyll-include-htaccess/

## Example .htaccess file

    ---
    permalink: /apikeys/generator/.htaccess
    ---
    AuthName "INTERNAL DOC" 
    AuthType Basic 
    AuthUserFile /home/dpgfnbmi/public_html/developer/.htpasswd 
    require valid-user
