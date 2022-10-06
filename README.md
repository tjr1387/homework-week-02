# Week 2 Homework Challenge -- A Sample Portfolio

## Description

The intention of this repo is to build a sample portfolio page with the use of several images: One serving as a sub-header of sorts, one large image serving as a link to the 'primary' project, and a few smaller, 'secondary' ones serving as links to smaller projects. It will have a header 'nav' which sends the user down to each respective section ('About Me', 'Work' & 'Contact'), as well as a sample 'resume' HTML page. It is designed to be responsive to various/changing screen widths, which has been executed okay in some spots, and not so much in others.

## Installation

N/A

## Usage

It is very important to note that I have no real work to show. All the links, while they function properly, do NOT go to any of my work, as it does not currently exist. Instead, they just go to various websites (and a non-existent resume) -- most of the time not even related the pictures (the one exception is the 'GitHub' link, which _does_ go to my GitHub). I felt this was okay because the point of the exercise was implementing responsive styling and functional HTML structure/links. It should also be noted that the minimum width I accounted for was 500px (browser constraint), which isn't ideal because I believe small phones go into the low 300s.

Screenshot: You can find it inside the 'assets' folder, titled 'my-mockup'.

Link to live site: 

## Flaws

I wasn't able to make everything perfectly. The page is not well colored (I am _not_ a graphic design guy; not even close) -- I basically just tried to mimic the sample mock-up we were given. I went with 'grid' layout (primarily because it made the section headings easy to put in a clean column on the left), and that lead to some sloppy styling, specifically in the 'secondary photo-links' area. There are two main things I could not get to be very responsive: the aforementioned secondary photo-links (for some reason I couldn't shrink/grow them -- I think it has something to do with the photos being enormous and the styling I used to constrain their size) and the labels that are laid-over the photos (couldn't get them to scale with the images that were shrinking/growing). I ended up just using media queries to make sure it didn't look too terrible with the overlapping, but the better way is definitely the correct use of flexbox!

## Credits

N/A

## License

MIT License (as referred to in the repo)