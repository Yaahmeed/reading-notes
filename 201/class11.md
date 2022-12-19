# Foundations  

## Why these topics matter as it relates to this this module  

Audio, video, and responsive images make our webpages more dynamic and interesting for a user.  

### Video and Audio Content

1. In the early 2000s, video and audio online were made possible by proprietary plugin based technologies, which had security and accessibility issues. Since the early 2000s, native HTML solutions and the availability of JS APIs to control them have come into favor.  
2. `src` is a source attribute that contains the path to the video you want to embed. The `controls` attribute includes the browsers own control interface as a way to start and stop the media.  
3. Fallback content inside of the video tags is important so that we can display something in case the browser accessing the page doesn't support the video element.  
4. Audio and Video need to know where they came from (`src`), they need their `controls` in order to work, and they need to know what to do if they dont work correctly (fallback content). (I apologize for the lack of story, I am currently very ill...)

### Grid  

1. Flexbox was designed for layout in 1 dimension (row or column). Grid is 2 dimensional layout (rows and columns at the same time).  
2. Grid container - This is the parent element of all of the grid items  
Grid item - These are the children of th grid container  
Grid line - These are the dividing lines that make up the structure of the grid (horizontal or vertical)  

### Responsive images  

1. It makes the website more appealing and more accessible across a wide variety of devices.  
2. img attributes `srcset` and `sizes` example: `<img srcset="smallerPic.jpg, largerPic.jpg" sizes="(max-width: 800px) 300px, 800px" src="largerPic.jpg" alt="picture size" />`  
Used to display a different image based on detected screen/resolution size.  
3. srcset defines the set of images we will allow the browser to choose between, and what size each image is.  

## Things I want to know more about  

Embedding video files and creating your own controls
