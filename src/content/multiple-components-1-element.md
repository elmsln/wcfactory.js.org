---
title: Multiple components in one repo
---
<p>Let's say you've made an element and now you want to add another one.</p>
<p>If the element is related or integral to the success of the first element, you might want to consider grouping it in the same "element" for publishing. The ELMSLN team does this all the time via the "lib" convention</p>
<media-image source="files/scale-50/foldertree.jpg" caption="Folder tree, lib directory shown with an additional .js file" size="wide" card resource="#63c36fe5-0fbe-b0b7-d1f7" prefix="oer:http://oerschema.org/ schema:http://schema.org/ dc:http://purl.org/dc/terms/ foaf:http://xmlns.com/foaf/0.1/ cc:http://creativecommons.org/ns# bib:http://bib.schema.org " style="width: 75%;"></media-image>
<p>By placing these sub-elements in the lib directory you lose out on the separation of concerns / tooling capabilities of the yarn start command but you gain simplicity of managing many related elements.</p>
<p>We recommend making the lib directory if you generate an abstraction from the element as your working on it via the tooling. The tooling is there to help ease you into the workflow and keep things abstracted into MVC, but it doesn't mean you need to be constrained by it!</p>
