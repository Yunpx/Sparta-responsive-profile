# CSS Media Queries Lab

## Timings

45 - 60 minutes

## Summary

Starting from an unresponsive CSS layout of Steve's profile (or your own version if you prefer) use CSS media queries to make the website aesthetically pleasing at all screen widths and devices. Ensure the page has at least two noticeably different layouts at different screen widths.

Here are some helpful hints to get you started:

 - Remember that CSS is read downwards and overwrites as it goes down
 - Start mobile first - how does this dictate what kind of media query you will use?
 - The panels on the projects page are perfect for making responsive - how could you position them to make better use of the space you have?
 - Have a look at common websites and how they handle responsiveness - how complex is a usual mobile page compared to a full width desktop page?

## Bonus Tasks

 1. Have two breakpoints, giving a mobile, tablet and desktop view
 2. Simplify your CSS as much as possible - prizes for the least lines of CSS code!

------------------------------------------------------------------

# My Work

## Index page

For the index page, __Desktop__ and __iPad__ viewport, I have changed the list of years in Education, from blocks to inline blocks, each taking 32% of the screen width, so that they can appear in a single line. In the __mobile__ viewport, I have changed them back to display in lists, each block takes 100% of the screen width, since the screen size is smaller. I have also moved the ```#headshot``` (profile picture) to the centre to fit the screen, and to look better.
```CSS
.years{
  display: inline-block;
  width: 32%;
```
The profile also shrinks in proportion to the mobile device's screen width, so that the user is still able to see the full profile picture.

## Project page
For the projects' page, I have adjusted the __profile picture__ the same way as the index page, for both phone and iPad viewports.

I have also changed the layout of the completed projects section. From inline block each taking a third of the width, to each taking 100% of the width. And when the viewport is at the size of an __iPad__, the pictures adjusts to 100% width of the device, enable the user to have a clear view of the picture. I have set the descriptions for the projects to be aligned to the left.

```CSS
img.screenshot{
  width:100%;
  height: auto;
}
```

The same is applied to the __phone__, as I see the layout fits the phone as well.

### Issues
> There is a strange gap on the right of the Additional skills in mobile view, hope to update it in the future.
