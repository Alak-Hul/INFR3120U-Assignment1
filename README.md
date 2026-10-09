# INFR3120U-Assignment1

Kurtis Stubbe's Portfolio 

Colours Scheme Used: My Color Theme by Helena Simonová
This color palette has no tags
exported as css:
.My-Color-Theme-1-hex { color: #F2EDD5; }
.My-Color-Theme-2-hex { color: #E7390D; }
.My-Color-Theme-3-hex { color: #F26716; }
.My-Color-Theme-4-hex { color: #084A24; }
.My-Color-Theme-5-hex { color: #04261E; }

Gradients I used:
I used a linear gradients in the header (navigation bar) on the Desktop CSS (Full.css)

header {
  background: linear-gradient(to left, #084A24 0%,#04261E 100%);
  color: #F2EDD5;
  padding: 20px;
  text-align: center;
}

I used radial gradients in the wrapper div on the desktop, tablet, and smartphone css (Full.css,tablet.css,smartphone.css)
radial-gradient(ellipse at center,  #E7390D 40%,#F26716 77%)

#wrapper {
    width: 960px;
    margin-left: auto;
    margin-right: auto;
    background:radial-gradient(ellipse at center,  #E7390D 40%,#F26716 77%);
}

I used linear graidents for the project card on project.html for desktop, tablet, and smartphone css (Full.css,tablet.css,smartphone.css)

.card {
  background: linear-gradient(to bottom, #F26716 0%,#E7390D 100%);
  border: 1px solid #04261E;
  border-radius: 8px;
  padding: 20px;
  flex:1;
  min-width: 200px;
}

Lastly I used a linear gradients for the article (mid section of the pages) for desktop, tablet, and smartphone css (Full.css,tablet.css,smartphone.css)

article {
  background: linear-gradient(to bottom, #084A24 0%,#04261E 100%);
  color: #F2EDD5;
  text-align: center;
}


Viewport sizes:
Desktop - 960px
Tablet - min-width(481px) and max-width(959px)
Smartphone - max-width(480px)

These values where chosen to adhere to the 960px standard, allow develpers to give accessible UI design depending, on the users display. 