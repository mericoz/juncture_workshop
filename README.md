# DSGF Workshops Spring'22: Juncture
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Composing a Visual Essay"
       author="Meriç"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
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
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Notice how, in the markdown text, the information for a visual element precedes your body paragraph._ 
Click on the info button on the upper left of the image on this section, and discover how the parameters below are reflected in your visual essay. Do the same with this footnote here:[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Well done! You have found a reference. Enjoy this video on Indian Ragas](https://www.youtube.com/watch?v=BaXQtx3nMqQ)
