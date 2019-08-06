# Taipei Toastmasters Club's Bulletins

This is a place to host bulletins from Taipei Toastmasters Club.

## How to Use

WARNING: `ONLY TAIPEI TOASTMASTERS CLUB's OFFICERS HAVE THE PERMISSION TO UPLOAD FILES`

If you want to upload a new bulletin file, just enter `files` folder, click the `upload` button then upload your file with date format (`YYYYMMDD`)

After uploading the file, the index page would show the lattest file on the list automatically.

Note that the name of the file **cannot have special characters** like `!`, `@`, `#`, `(`, `)`.


## Customizing

### Configuration variables

Merlot will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

