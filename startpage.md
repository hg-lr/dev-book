[Home](readme.md)

# Startpage

The startpage is a targeted page for 

* the brand of the webproperty
* one competitive phrase

The startpage is a *value hub*, and 

 * links to the most important targed pages of the webproperty 
 * to a random selection of targeted pages
 * the newest / latest updated targeted pages

The startpage must be in the root of the domain. I.e.: https://www.example.org/

The startpage does not redirect away from the root. I.e. 

 * no redirect from https://www.example.org/ to https://www.example.org/en/
 * no redirect from https://www.example.org/ to https://www.example.org/welcome.html
 * or similar 

The canonical of the startpage points to itself. I.e:: https://www.example.org/ has the canonical <link rel="canonical" href="https://www.example.com/" />. If any alternate URLs for the startpage exist, they also point the canonical to the root of the domain. I.e.: https://www.example.org/ has the canonical <link rel="canonical" href="https://www.example.com/" /> 

