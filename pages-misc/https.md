---
title: SSL encryption for API requests
excerpt: You have to use use HTTPS for all your Spamty API requests.

layout: default
permalink: /https/

gh-file: pages-misc/https.md

---
You have to use use HTTPS for your API requests. For api.spamty.eu all HTTP requests are redirected to HTTPS but api-raw.spamty.eu does only work with HTTPS (there is no redirection).
The domain api.spamty.eu has a SSL-certificate from *CloudFlare*. api-raw.spamty.eu has a SSL-certificate from *Let's Encrypt*.

## Fix

If you have any problems with the certificate you can ignore any errors when using our API in case our certificate is considered as invalid.

### PHP with cURL

If you are using PHP with cURL you can add this line to ignore the invalid certificate:

    curl_setopt($ch, CURLOPT_SSL_VERIFYPEER, false); 

### cURL

Add `-k` or `--insecure`.

    curl -k https://api.spamty.eu/version.php
