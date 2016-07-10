---
title: Get API Version
excerpt: With this API you can see what is the latest version of any Spamty API.
layout: default
permalink: /version/

gh-file: api-version/version.md
---
With this API you can see what is the latest version of any Spamty API.

## URL

The API is located at:

    https://api.spamty.eu/version.php

You have to use [HTTPS](../https/).

## Parameters

You have to pass the following GET parameters to the API:

`api`

The API (eg *shorturlview*, *shorturlcreate*, *decryption*, *encryption*)

`output`

The output type (*json* or *xml* is supported, default is *json*)

### Example URL

    https://api.spamty.eu/version.php?api=decryption&output=xml


## Return Values

The request will return the following parameters in JSON or XML:

`status`

Value 1 for OK and 0 if an error occurred.

`statusDetails`

A description if there were any errors. Otherwise the value is *ok*.

`info`

The URL where you can get some additional information about the API in our documentation.

`version`

The latest version

`url`

The URL of the API

### Example returns

The example URL above would return:

    <spamty>
    	<info>https://dev.spamty.eu/decryption/</info>
    	<url>https://api.spamty.eu/decryption/v4.php</url>
    	<version>4.2</version>
    	<status>1</status>
    	<statusDetails>ok</statusDetails>
    </spamty>


## See Also

Please report any problems or feature requests [via this form](https://spamty.eu/contact-dev.php).
