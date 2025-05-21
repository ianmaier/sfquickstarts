author: Ian Maier
id: build_an_offsite_commerce_media_network_on_snowflake
summary: Build a commerce media platform for audience curation, offsite activation, and closed-loop measurement.
<!--- Categories below should be hyphenated, i.e., Getting-Started. Do not leave blank. Visit site for available categories. -->
categories: Marketing
environments: dais <!--- What is the correct environment for the DAIS hands-on lab? -->
status: Draft
feedback link: https://github.com/Snowflake-Labs/sfguides/issues
tags: Marketing, Partners, Media, Hightouch, Retail, Commerce

# Build an Offsite Commerce Media Network on Snowflake with Hightouch & The Trade Desk
<!-- ------------------------ -->
## Overview 
Duration: 1

In this guide you will learn how to transform your existing Snowflake investment into a user-friendly platform that a non-technical commerce media team can use to curate custom audiences, activate and share them with their advertising partners, and provide closed-loop attribution.

### Business Scenario
We are building a Travel Media Network for a global luxury hospitality conglomerate called Altuva, which owns multiple hotel brands with millions of  visitors annually. We are partnering with a high-end Consumer Packaged Goods company called Omnira, which sells luxury snacks, beverages, and health & wellness amenities within most of Altuva's hotels. Omnira has approached us with a specific campaign idea: they want to promote their chocolate truffles to your hotel visitors in the 30 days before their arrival to influence more in-hotel consumption.

Our task is to build a platform that our non-techincal media team can use to create a highly customized audience, share the audience with Omnira, and provide them with the data & reporting to attribute the ads they run to in-hotel purchases.

### Prerequisites
- N/A

### What You’ll Learn 
- How to enrich Snowflake with UID2s using the Native App for privacy-safe activation and measurement.
- How to build a visual audience builder on top of Snowflake using Hightouch.
- How to activate audiences on The Trade Desk using Hightouch, for both managed service and self-service campaign execution.
- How to send offline conversion events from Snowflake to The Trade Desk using Hightouch.
- How to execute The Trade Desk campaigns using shared audiences and conversion events.
- How to build SKU-level attribution reporting on Snowflake using The Trade Desk's Raw Event Data Stream (REDS). 

### What You’ll Need 
- A Snowflake account login with a role that has the permissions to create a new database, schema, and warehouse to be used by Hightouch.
- A Hightouch account with Customer Studio access. You can [sign up for a free Hightouch account here](https://app.hightouch.com/signup). Please [contact our team](https://hightouch.com/demo) to inquire about Customer Studio access.

### What You’ll Build 
- A Snowflake-native visual audience builder that is customized to your luxury hospitality brand's unique data & offering
- An activation platform for syndicating audiences and conversion events
- Closed-loop attribution reporting with SKU-level breakdowns

<!-- ------------------------ -->
## Import the mock datasets
Duration: 1

<!-- ------------------------ -->
## Enrich Snowflake with UID2
Duration: 1

<!-- ------------------------ -->
## Connect Hightouch to Snowflake
Duration: 1

<!-- ------------------------ -->
## Connect Hightouch to The Trade Desk
Duration: 1

<!-- ------------------------ -->
## Build the audience schema
Duration: 1

<!-- ------------------------ -->
## Create a custom audience for monetization
Duration: 1

<!-- ------------------------ -->
## Sync the audience to The Trade Desk
Duration: 1

<!-- ------------------------ -->
## Share the audience with the advertising partner
Duration: 1

<!-- ------------------------ -->
## Create a brand-specific conversion model
Duration: 1

<!-- ------------------------ -->
## Create an Offline Conversion Sync to The Trade Desk
Duration: 1

<!-- ------------------------ -->
## Share the conversion data with the advertiser
Duration: 1

<!-- ------------------------ -->
## Advertiser: Run a self-service campaign
Duration: 1

<!-- ------------------------ -->
## Set up REDS data sync
Duration: 1

<!-- ------------------------ -->
## Create attribution report
Duration: 1

<!-- ------------------------ -->
## Conclusion
Duration: 0





<!-- ------------------------ -->
## Code Snippets, Info Boxes, and Tables
Duration: 2

Look at the [markdown source for this sfguide](https://raw.githubusercontent.com/Snowflake-Labs/sfguides/master/site/sfguides/sample.md) to see how to use markdown to generate code snippets, info boxes, and download buttons. 

### JavaScript
```javascript
{ 
  key1: "string", 
  key2: integer,
  key3: "string"
}
```

### Java
```java
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```

### Info Boxes
> aside positive
> 
>  This will appear in a positive info box.


> aside negative
> 
>  This will appear in a negative info box.

### Buttons
<button>

  [This is a download button](link.com)
</button>

### Tables
<table>
    <thead>
        <tr>
            <th colspan="2"> **The table header** </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>The table body</td>
            <td>with two columns</td>
        </tr>
    </tbody>
</table>

### Hyperlinking
[Youtube - Halsey Playlists](https://www.youtube.com/user/iamhalsey/playlists)

<!-- ------------------------ -->
## Images, Videos, and Surveys, and iFrames
Duration: 2

Look at the [markdown source for this guide](https://raw.githubusercontent.com/Snowflake-Labs/sfguides/master/site/sfguides/sample.md) to see how to use markdown to generate these elements. 

### Images
![Puppy](assets/SAMPLE.jpg)

### Videos
Videos from youtube can be directly embedded:
<video id="KmeiFXrZucE"></video>

### Inline Surveys
<form>
  <name>How do you rate yourself as a user of Snowflake?</name>
  <input type="radio" value="Beginner">
  <input type="radio" value="Intermediate">
  <input type="radio" value="Advanced">
</form>

### Embed an iframe
![https://codepen.io/MarioD/embed/Prgeja](https://en.wikipedia.org/wiki/File:Example.jpg "Try Me Publisher")

<!-- ------------------------ -->
## Conclusion
Duration: 1

At the end of your Snowflake Guide, always have a clear call to action (CTA). This CTA could be a link to the docs pages, links to videos on youtube, a GitHub repo link, etc. 

If you want to learn more about Snowflake Guide formatting, checkout the official documentation here: [Formatting Guide](https://github.com/googlecodelabs/tools/blob/master/FORMAT-GUIDE.md)

### What we've covered
- creating steps and setting duration
- adding code snippets
- embedding images, videos, and surveys
- importing other markdown files
