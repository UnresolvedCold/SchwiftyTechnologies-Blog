# Schwifty Technologies Blog

## Blog writing Guide

The blog supports markdown as well as in-build html formatting techniques.
 To learn more about markdown, [refer here](https://guides.github.com/features/mastering-markdown/). Markdown can help you to write faster and HTML is very useful in desigining the page.

## Examples and hints on adding link and images in blog
 
1. Adding an image
   * HTML way
   > `<img src="Public URL of image" />`
   * Markdown way 
   > `![Alt Text](Public URL of image)`
1. Adding links
    * HTML way
    > `<a href='link reference with http or https'>Text to display</a>`
    * Markdown way
    > `[Text to display](full link with http or https)`
1. For new line use double new line characters

## Cloning Guide

1. Get the code using `git clone https://github.com/UnresolvedCold/SchwiftyTechnologies-Blog.git`
1. `yarn install` to add necessary repositories
1. `yarn devStart` to start App in dev mode (entry point- server.js)
1. `yarn start` in production mode.

## Folder Structure

1. HTML views are stored at `./views`
1. MomgoDB Schema are defined in `./models`
1. Routes are defined in `./routes`