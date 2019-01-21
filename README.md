<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>CSS specificity</title>
        <style>
            p {
                font-family: sans-serif;
            }
            
            .info-paragraph {
                color: blue;
            }
            
            #main-paragraph {
                font-weight: bold;
            }
        </style>
    </head>
    <body>
    
    <p>This is a snippet from the <a href="http://en.wikipedia.org/wiki/Pacific_Ocean">longer Wikipedia article</a>.</p>
    
    <h1>The Pacific Ocean</h1>

    <p id="main-paragraph" class="info-paragraph important">
    The Pacific Ocean is the largest of the Earth's oceanic divisions. It extends from the Arctic Ocean in the north to the Southern Ocean (or, depending on definition, to Antarctica) in the south and is bounded by Asia and Australia in the west and the Americas in the east.</p>

    <p class="info-paragraph">At 165.25 million square kilometers (63.8 million square miles) in area, this largest division of the World Ocean – and, in turn, the hydrosphere – covers about 46% of the Earth's water surface and about one-third of its total surface area, making it larger than all of the Earth's land area combined.[1] The equator subdivides it into the North Pacific Ocean and South Pacific Ocean, with two exceptions: the Galápagos and Gilbert Islands, while straddling the equator, are deemed wholly within the South Pacific. The Mariana Trench in the western North Pacific is the <strong class="important">deepest point in the world</strong>, reaching a depth of 10,911 metres (35,797 ft).</p>

    <p class="info-paragraph">The eastern Pacific Ocean was first sighted by Europeans in the early 16th century when Spanish explorer Vasco Núñez de Balboa crossed the Isthmus of Panama in 1513 and discovered the great "southern sea" which he named Mar del Sur. The ocean's current name was coined by Portuguese explorer Ferdinand Magellan during the Spanish circumnavigation of the world in 1521, as he encountered favourable winds on reaching the ocean. He therefore called it Mar Pacifico in Portuguese, meaning "peaceful sea".
    </p>
    
    </body>
</html>
