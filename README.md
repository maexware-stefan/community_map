# OXID Community Map

A map stuffed with peeps being involved in [OXID eShop](https://oxidforge.org) development. The directory is hosted on GitHub and hence allows everyone to add, delete or alter its own entry. ♥ Join us!

__https://oxidprojects.github.io/community_map/__

![Screenshot] (https://raw.githubusercontent.com/OXIDprojects/community_map/assets/images/communitymap_readme.png)

The screenshot above shows what user entries look like. You’ll even get your own URL for your entry, which is awesome! Look, this is a [link to Markus](https://friendsofredaxo.github.io/community/#staabm).

## How to add and manage your entry?

You can add your marker to the map and manage your data by yourself. Learn about [3 ways how to manage your entry](https://github.com/FriendsOfREDAXO/community/tree/master/_directory)! 🚀

## Who’s the map for?

The map is for any person being involved in REDAXO: developers, users, editors, writers, designers, friends and family et al. It’s about visualizing the REDAXO community. If you use or support REDAXO, the map is for you!

## How does this map work?

No big deal: GitHub allows to generate static websites out of repositories. They make use of [Jekyll](https://jekyllrb.com), a ruby based generator. Jekyll comes with [Liquid](https://shopify.github.io/liquid/) templates, which helped us to inject all our map entries within a JSON at the bottom of the HTML. JavaScript grabs the data and starts a nice [Leaflet](http://leafletjs.com) map with beautiful tiles provided by [CARTO](https://carto.com/location-data-services/basemaps/).  
—Well, that’s it. ¯\\\_(ツ)_/¯

## Can we use your map for our community?

Sure, it’s open source! However, we don’t provide a release or some setup script. We’d recommend you to download the repo as zip file instead and make it run on your local machine first (see [SETUP.md](https://github.com/FriendsOfREDAXO/community/blob/master/SETUP.md) for instructions). Afterwards you’ll need to replace some `REDAXO` content with your community content, empty the `_directory/data` folder and start over with a shiny fresh map.

In case you struggle, we’d love to help! 🙋‍♂️  
Also if your map is live we’d be grateful to receive a quick note from you: _friendsof [at] redaxo.org_. Thanks!

## How to run the map on my local machine?

See [SETUP.md](https://github.com/FriendsOfREDAXO/community/blob/master/SETUP.md) for instructions.

## What else?

You should join our Slack chat. It’s full of nice REDAXO people! ✌️  
Provide your email to receive an invitation: https://redaxo.org/slack/
