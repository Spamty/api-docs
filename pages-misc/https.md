---
title: SSL encryption for API requests
excerpt: You have to use use HTTPS for all your Spamty API requests.
layout: default
permalink: /https/
---
You have to use use HTTPS for your API requests.

The domain api.spamty.eu has a SSL-certificate from *Let's Encrypt* but you should ignore any errors when using our API in case our certificate is considered as invalid.

## Fix

### PHP with cURL

If you are using PHP with cURL you can add this line to ignore the invalid certificate:

    // ignore the invalid SSL certificate
    curl_setopt($ch, CURLOPT_SSL_VERIFYPEER, false); 

### cURL

Add `-k` or `--insecure`.

    curl -k https://api.spamty.eu/version.php
