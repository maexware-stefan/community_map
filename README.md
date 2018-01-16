# OXID Community Map

A map stuffed with peeps being involved in [OXID eShop](https://oxidforge.org) development. The directory is hosted on GitHub and hence allows everyone to add, delete or alter its own entry. ♥ Join us!

__https://oxidprojects.github.io/community_map/__

![Screenshot](https://raw.githubusercontent.com/OXIDprojects/community_map/master/assets/images/communitymap_readme.png)

The screen shot above shows what user entries look like. You’ll even get your own URL for your entry - awesome, isn't it? For example, this is a [link to Chris](https://oxidprojects.github.io/community_map/#code-commerce).

## How to add and manage your entry?

You can add your own marker to the map and manage your data yourself. Learn about it at [3 ways how to manage your entry](https://github.com/OXIDprojects/community_map/tree/master/_directory)!

## Who’s the map for?

The map is for any person to be involved with OXID eShop development: developers, integrators, editors, translators, designers, etc. It’s about visualizing the OXID community. If you use or support OXID, the map is for you!

## How does this map work?

GitHub allows to generate static websites from repositories. They use the ruby based generator [Jekyll](https://jekyllrb.com). Jekyll comes with [Liquid](https://shopify.github.io/liquid/) templates, which helped us injecting all our map entries inside a JSON at the bottom of HTML. JavaScript grabs the data and starts a nice [Leaflet](http://leafletjs.com) map with beautiful tiles provided by [CARTO](https://carto.com/location-data-services/basemaps/). And that’s it. ¯\\\_(ツ)_/¯

## Can we use your map for our community?

Sure, it is open source! However, we don’t provide a release or some setup script. We recommend to download the repository as a zip file and make it run on your local machine first (see [SETUP.md](https://github.com/FriendsOfREDAXO/community/blob/master/SETUP.md) for instructions). Then, you probably want to replace the `REDAXO` content with your community content, empty the `_directory/data` folder and start over with your own _virgin_ map.

In case you struggle, we’d love to help!
Also, if your map is live, we'll be glad to receive a quick note to _friendsof [at] redaxo.org_. Thanks!

## How to run the map on my local machine?

See [SETUP.md](https://github.com/FriendsOfREDAXO/community/blob/master/SETUP.md) for instructions.

## What else?

You should join our Slack chat. It’s full of nice REDAXO people! ✌️  
Provide your email to receive an invitation: https://redaxo.org/slack/