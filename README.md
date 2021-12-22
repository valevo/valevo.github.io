# valevo.github.io



### TODOs

 - [GitHub pages intro](https://docs.github.com/en/pages)
 - [how to configure custom domains](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
 - [GitHub pages with jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)


 - font: sans-serif?
 
 - content:
   - education
   - projects & work experience
   - misc: 
     - presentations, talks, workshops, etc.?
     - B.Sc. supervision
     - publications
   - personal info
   
   - programming languages, real languages
   
   
 - structure:
 
   - header section: name, (navigation)
   - 

 
 
### Ideas

 - blur on:hover -> see ark.amsterdam
 - catalogue-like design? also see ark.amsterdam
 
 - talk about fixed-contract work experience like projects:  
   e.g. SABIO (at KNAW), ConversationKG (at INDELab)
   
 - integrate PDF reader? (is that possible? maybe Javascript?)  
   -> for thesis, papers, supervised theses
 
 
 - make page as a whole (i.e. body) NOT overflow, i.e. exactly size of viewport;  
   let left and right container overflow: scroll on their own if necessary
 
 
 - add Komoot routes to personal page 
 
 
 ## `v2`

left-panel:  

    items (projects, education, ...); title + year 
    
    centered in panel, large margins, individual scroll
    
    each item has ;solid right border -> delete onlick
    
right-panel:

    item details: images, description
    
    default: profile pic with general info about myself, onlick for name & default on load
    
    individual scroll
    
    put all sections in HTML, set visibility=0, onlick item in left panel: set corresponding detail section to visibility=1, put default at the top with always visibility=1 (creates fallback)
    
    


### Stolen Stuff

from Folgert's site:

    text-rendering: optimizeLegibility;
    font-family: 'Fira Code', monospace;



