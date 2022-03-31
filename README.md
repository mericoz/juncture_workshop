# DSGF Workshops Spring'22: Juncture
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Composing a Visual Essay"
       author="Meriç"
       banner="https://upload.wikimedia.org/wikipedia/commons/7/7d/Princes_of_the_House_of_Timur.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

## This is Heading n.2

You can format this just as you would format a paragraph in an essay, with the added benefit of including [interactive links](https://lab.plant-humanities.org/heliconia/). The link here is an example of a visual essay from The Plant Humanities lab, which was a project developed in collaboration between JStor and Dumbarton Oaks Institute. 
<param ve-image 
       manifest="https://cudl.lib.cam.ac.uk//iiif/PH-CAVENDISH-P-00006">

# Basic usage

## Image

_Notice how, in the markdown text, the information for a visual element precedes your body paragraph._ 
Click on the info button on the upper left of the image on this section, and discover how the parameters below are reflected in your visual essay. Do the same with this footnote here: [^1]
<param ve-image
       label="Image of Anastasis from Armenian Manuscript" 
       description="Bodleian Library MS Arm. c. 1" 
       license="© Bodleian Libraries, University of Oxford" 
       url="https://iiif.bodleian.ox.ac.uk/iiif/manifest/ed00e41d-83e4-410a-943b-d4cfa28ea2ba.json">

## Let's see if another image will work

In this session, we will keep it simple and try to use the IIIF framework to add images. Try visiting [their website](https://iiif.io/guides/finding_resources/) for a guideline about finding Mirador-compatible images.
<param ve-image
       manifest="https://iiif.harvardartmuseums.org/manifests/object/217072"
       label="Dragon in Foliage"
       license="Harvard Art Museums/Arthur M. Sackler Museum, Gift of Stuart Cary Welch, Jr."
       description="Ottoman Watercolor from the Harvard Art Museums, Obj. N. 1999.288"
       url="https://hvrd.art/o/217072"
       
## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Well done! You have found a reference. Enjoy this video on Indian Ragamala paintings](https://www.youtube.com/watch?v=BaXQtx3nMqQ)
