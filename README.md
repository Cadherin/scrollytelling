# Franny's scrollytelling templates

## Background
I recently worked on a [project](https://www.ischool.berkeley.edu/projects/2022/cost-putting-food-table-across-world-and-over-years) that investigated food prices around the world. It resulted in a website that showcased various data visualizations that explored publicly available food indices from different aspects. Beyond the context of food prices, the project made me think deeply about the workflow and ways to share data visualizations with on the web quickly with the minimial setup. Because of this, I traced back the steps that I took to compile the data story and especially, the construction of the one-page website. This led me to generalize the the building blocks of the website and the code blocks used so that it could be reused and built upon in the future. The generalization turned into the creation of templates. I selfishly created this for myself to start, but my belief has been that sharing is a big part of how we all learn, so I'm making this public for those who may find it useful.  

## What do these templates do?
Franny's scrollytelling templates are ready-to-deploy website templates geared towards the sharing of data visualizations in a minimalistic format with a journalistic flair.

## What do I get in a template?
At the time that this repo is published, there is one set of template. It comprises of the following:
- A HTML file
- A CSS stylesheet
- A sample cover page image

More to be added in templates to be published in the future

## How do I use these templates?
Each template is contained in a folder in this repo, simply download the repo and extract the content in the template of choice. Refer to the comments in the HTML and CSS files to customize the code to suit your needs. Put the files into a folder of your website host location and it would be ready to go.

## Available templates
### Minimalista

"Minimalista" features a single-page website that showcases:
- 1 cover page
- 2 sections for key messages
- 2 sections for data visualization
- 1 closing section
- Fade-in effect is built whereby the page listens to where the user is during the scrolling and turns the opacity of the next section from 0 to 1 within a default duration of 3

To customize, simply copy & paste the respective sections to create more key messages or data visualizations. Styling such as font, height of each section, etc. could be adjusted using the CSS stylesheet. 
