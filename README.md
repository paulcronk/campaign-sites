# campaign-sites
Google Tag Manager (GTM) container for GOV.UK campaign platform

Full instructions are published on the campaign site https://analytics.campaign.gov.uk/.

## Using this container
If you are using Google Tag Manager for your campaign you can use this container to shorten the process of setting it up. You would need to:
1. download the json file from Github
2. within GTM, import it into the new or existing container that you're planning to use on the site

Because the campaign sites are structured in the same way, in should work across all of them. But there is one crucial change you need to make. The user-defined variable 'GA property settings - EDIT THIS' needs to be edited to include your GA tracking ID. (In the format UA-********-\*.)

The container should be tested in GTM's preview mode before being published.

## What the container records
The container is set up to record pageviews and a range of events. These events include:
* external links
* clicks on any hidden help sections
* clicks on buttons
* use of any embedded video - this includes play, pause, and progress through the video

## Further customisation
You may need to customise the container further. For example, to add Floodlight tracking, or Twitter cards, Facebook Pixel tracking etc.
