# [dideler.github.com](http://dideler.github.com)

A portfolio of my public work on GitHub.

Based off of [dkuntz2.github.com](http://dkuntz2.github.com/)
which is based off of [twitter.github.com](http://twitter.github.com/).

## FORKING

You may fork this project for your own work. It's **very easy to personalize**.

### Dynamic version

This is the default version (master branch).
Simply search for my GitHub username `dideler` and replace all instances with your own.

### Static version

A [static version](https://github.com/dideler/dideler.github.com/tree/static)
exists. You'll need to modify it more to personalize it, but it does have its
benefits -- such as a faster page load speed.

### Organizations

If you're using it for an organization profile, you also need to search and replace
`users` with `org`.

## GitHub API

GitHub's API v3 is used to grab public information from your profile, which is used to fill in your portfolio page.

[JSON-P Callbacks](http://developer.github.com/v3/#json-p-callbacks) are used to embed your GitHub content in the web page.

To view your public data from the API, use your browser to visit [https://api.github.com/users/your-username](https://api.github.com/users/dideler)
or you can use command-line `curl https://api.github.com/users/your-username?callback`

## LICENSE

[Original](https://github.com/twitter/twitter.github.com) Copyright 2012 Twitter, Inc.

Several modifications made by Don Kuntz and Dennis Ideler.

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
