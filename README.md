# Pressmatic template for WP-Palvelu.fi

By ZeelandFamily, based on the WordPress project layout used at Seravo's wp-palvelu.fi. The contents of the app/ directory is essentially a stripped-down and slightly modified version of https://github.com/Seravo/wordpress

A WordPress project layout for use with Git, Composer and Nginx.

This same project layout is used by default on all [WP-palvelu.fi](https://wp-palvelu.fi) instances for easy deployment workflow. Contents of the app/ repository equals to what you would have on the server in the directory /data/wordpress/.

The reason this repository exists is to make starting a project in Pressmatic easier, when hosting is in wp-palvelu.fi, or any environment where a similar directory structure is used.

## How to use this template

[Download the latest release release ZIP](https://github.com/ZeelandFamily/pressmatic-wp-palvelu-template/releases/latest) and drop it in `~/Library/Application Support/Pressmatic/site-templates`. You should then be able to create a new site in Pressmatic using this template (New Site > Template).

## Documentation

Please see production environment documentation at https://docs.wp-palvelu.fi for more info.

## WordPress plugins

The composer.json contains some plugins and themes that are likely to be useful for pretty much every installation.

## Credits

WP-palvelu (https://github.com/Seravo/wordpress)
Directory layout heavily inspired by [roots/bedrock](https://github.com/roots/bedrock)


