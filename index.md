# Project Website: Community Monitors Mapping project

> tracing associations

## Quick Links
* [current version of the community-monitors map](Map_Index.html "Index Map")
* [view and comment the community monitors database here](https://docs.google.com/spreadsheets/d/1KQE_r0g6fgniXlygYdSrsEwZin0JXl1YzNrDSsG8pS8/edit?usp=sharing)
* [Edit this page](https://github.com/christofvanwyk/commnuity-monitors/edit/gh-pages/index.md "Markdown Editor")

## Introduction

Commnuity Monitors are a [Bench Marks Foundation](https://www.bench-marks.org.za/) affiliated activists living and reporting about life and problems in mining affected areas. This project will aim to create a searchable map that includes the ~2440+ reports since 2016: [link](communitymonitors.net/). With a better overview of the work already done, it becomes easier to follow up on issues, as well as perhaps seeing the reports at a different scale and in relation to the mining operations. With basic training and some automation in place, Bench Marks Foundation will potentially have a powerful tool to communicate their work. 

There are already solutions out there, that enable people to make maps like:
* [Ushahidi](https://www.ushahidi.com/). This is a is mostly used for humanitarian & crisis response (31%), election monitoring & civic engagement (25%), human rights advocacy (19%) [*source*](https://www.ushahidi.com/uploads/case-studies/ImpactReport_2018.pdf "Report"). This platform, although very user friendly and excellent at receiving large amounts of pre-formatted surveys quickly (online surveys, also sms, twitter, csv import etc.), it lacks some freedom in how to display and manipulate the data in order to get better insights.
* [Google Earth](https://earth.google.com/web/). This is a widely adopted and user friendly platform that makes it easy to create maps with your own points and shapes etc. However the .xml data capabilities are missing. The exported .kml file is interoperable with many applications, which makes it excellent if one needs a quick and dirty map.
* [QGIS](https://www.qgis.org/en/site/) . A free, open source and powerful GIS program with many powerful plugins. 
* [Mapbox](https://www.mapbox.com/) is an online mapping platform that's used by many [big companies](https://www.mapbox.com/showcase). It's free if you have less than 10,000 visits to your map in a month and it supports OpenStreetMap development. It's really flexible and I've used it to create the map sofar.
* [OpenStreetMap](https://www.openstreetmap.org). This is the community created, open source backbone of geodata. Basically, if you don't exist either on Google Maps or OSM, you don't exist. There are many mining communities are "off the map". Anyone can edit and I am already busy adding in communities that didn't exist before. My account is [here](https://www.openstreetmap.org/user/sweetmap) and I can really recommend mapping as a relaxing evening activity. You can even import GPS data (see [section III](https://github.com/christofvanwyk/commnuity-monitors/blob/gh-pages/index.md#iii-content-creation))

**there is no perfect application. What is important is that all these applications can be used in conjunction with the monitors'**

## I: Enhance existing reports with Metadata

> archaeology

### Tasks

- [x] scrape communitymonitors.net using [octoparse](https://www.octoparse.com/)
- [x] download all images from blog
- [x] format titles (2020)
- [x] format authors (2020)
- [x] format dates (2020)
- [ ] geocode locations using [smartmonkey geocode](https://workspace.google.com/marketplace/app/geocoding_by_smartmonkey/1033231575312)
- [ ] figure out how to format and store all media (photos, sounds, videos) in a structured way. 
- [ ] In the cloud but link and backup-able (dropbox/drive)!?
- [ ] link media to reports
- [ ] extract geolocation from 
- [x] extract keywords automatically (rough)
- [ ] extract keywords manually (final)

## II: Status Quo - Capacity

>you either create the software or you are the software

Survey community monitors capacity (time available, access to technology, transport etc.), capability (level of education, interests, skills, social connections etc.). Define and describe other issues that might hinder monitors’ work so that 

### Tasks

- [x] write survey [link](https://forms.gle/wAKFhBpPyGKcN5Aq6) (done Nov 2020)
- [ ] feedback end editing
- [ ] do we have profile pics of everyone?
- [ ] maybe the monitors need their own fb group
- [ ] format dates (2020)
- [ ] geocode locations using [smartmonkey geocode](https://workspace.google.com/marketplace/app/geocoding_by_smartmonkey/1033231575312)
- [ ] read 
- [ ] this is an incomplete item

## III: Content Creation

>liberate a thought into indeterminacy

Enrich the data content from collection, storage and sending. 

### Tasks

- [ ] let's try using our GPSs (map points in space)
- [ ] let's try using [Signal](https://signal.org/en/) to send files (WhatsApp wipes metadata like geolocation 😿).
- [ ] panoramas?
- [ ] create a meme (imgur)?
- [ ] crowdmapping?
- [ ] editing a database together (google sheets)
- [ ] in-App OpenStreetMap editor [street complete augmented reality app](https://play.google.com/store/apps/details?id=de.westnordost.streetcomplete&hl=en&gl=US), or [OSMand](https://osmand.net/)

## IV: Dissemination

>The Medium is the Message

### Tasks

- [ ] Automate Facebook posts with [Zapier](https://zapier.com/) 🤖
- [ ] embed some maps in emails
- [ ] share pictures, memes
- [ ] strategize on how to reach different NGOs
- [ ] strategize on how to reach politicians
- [ ] strategize on how to reach mining companies
- [ ] strategize on how to reach ...

### Support or Contact

This project is currently in proposal stage.
Contact me on christof.vanwyk[at]gmail.com
I am also available in stream 
