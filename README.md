# Material Cards region plugin
APEX plugin to import Google's Material Cards design

## Background
This plugin is based on the Material Cards demo offered by Google here : https://material-components.github.io/material-components-web-catalog/#/component/card

## Install
Import plugin file "region_type_plugin_material_card_plugin.sql" from source directory into your application.

## Plugin Settings
The plugin settings are highly customizable and you can change:
### Region Type
These "region types" are intended to be one-to-one matches for the various examples from the demo page : https://material-components.github.io/material-components-web-catalog/#/component/card
 - Basic
 - Basic w/ Text over Media
 - Basic w/ Header
 - Basic w/ Only Buttons
 - Basic w/ Only Icons
 - Horizontal Image and Text
### Image width
You can override the default image width. Value is in pixels.
### Image height
You can override the default image height. Value is in pixels.
### Include "Add to favorites"
You can toggle the presence of the "heart" symbol, which symbolizes "Add to favorites". No functionality comes with this icon. You can hook your business logic onto the class "plugin-favorite" if you like.
### Include "Share"
You can toggle the presence of the "branching" symbol, which symbolizes "Share". No functionality comes with this icon. You can hook your business logic onto the class "plugin-share" if you like.
### Include "More Options"
You can toggle the presence of the "vertical ellipsis" symbol, which symbolizes "More options". No functionality comes with this icon. You can hook your business logic onto the class "plugin-options" if you like.
### Button1 label
You can specify the label for the 1st button. The link is retrieved from the SQL query.
### Button2 label
You can specify the label for the 2nd button. The link is retrieved from the SQL query.
