---
layout: pub
urltitle: "Aragnation"
title: "An AI Generative Art Project by Devi Parikh & Abhishek Das"
categories: Aragnation, Generative Art, AI Art, Devi Parikh, Abhishek Das
favicon: static/img/aragnation.png
permalink: /
---

# Aragnation

Aragnation is a long-form generative art project by by [Devi Parikh][devi] and [Abhishek Das][das] on [ArtBlocks][artblocks].  

<img class="inline-pic" src="static/img/aragnation_collage.png">

## The Concept

Aragnation questions preconceived notions of what AI art can be. Does AI art have to be powered by giant neural networks? Do the aesthetics have to be that of photos or paintings or collages of pieces thereof?

Aragnation uses tiny AI models and constructs abstract imagery in the vocabulary of abstract blobs and organic textures rather than pixels. It is playful with colors. It has a hint of a watercolor and art paper aesthetic. 

The training data includes photographs taken by one of the artists, Abhishek.  The generated pieces thus capture, in broad strokes, [Abhishek’s photography][das-photos] – nature, landscapes and urban settings.

In a refreshing contrast to the gravity of the role AI technology is playing in content creation and creative expression, Aragnation brings a light and joyful touch to generative AI art. 

No GPUs were harmed in the making of Aragnation. All AI models are entirely different architectures than those commonly used, and have been designed and trained from scratch by the artists.

## The Features

Aragnation has six features.

1. Paper: The background paper is one of four styles -- graph, rods and cones, marble, and fabric
2. Colors: The colors are either sampled using an AI model or randomly for a more playful aesthetic
3. Palette: One of fourteen palettes partially curated by the AI model
4. Subject: An AI model assigns the generated piece to one of four categories -- flower, bird, urban and landscape
5. Texture: The texture of a piece is either plain or has a gradient generated using an AI model
6. Reflection: Some of the pieces have added depth to them via a horizontal reflection 

## The Artists

Devi and Abhishek have collaborated on dozens of projects since 2015. Many in AI, some in art, and some unrelated to either AI or art. Abhishek first introduced Devi to generative art in 2018!

### Abhishek Das

In his day job, Abhishek Das is an artificial intelligence researcher, i.e., he builds algorithms to mimic intelligence or the biological brain. Much like that, his art explores algorithms to mimic textures from the physical world – paper, ink, cloth, sand, paintings.

### Devi Parikh

Devi Parikh is an AI researcher and a generative artist. She also makes [Macrame][macrame], [Origami][origami], and maintains a physical sketchbook with kawaii doodles, zentangles, mandalas, paper cutting and sketches. 

While evolving, her generative art so far has tended to have vibrant colors, geometric patterns, symmetries, and crisp textures co-existing with organic shapes. She gets inspiration from a variety of sources -- some mundane, some exotic; some traditional, some unexpected; some specific, some diffused -- colors in rare stones, textures in snake skins, graffiti, wall art, digital illustrations, acrylic pouring, mandalas, ethnic fabrics, looking out the window during a long taxi ride, Indian culture, or feedback from a trusted friend. She maintains an ever growing list of ideas -- ranging from small tweaks to an existing project to entirely new projects or styles. Her process involves starting with an idea, prototyping the core of it to see if it feels right, and then iterating, iterating, iterating. The joy and mystery is in seeing where the iterations lead!

She gets energy out of creative expression. Some of it through her art -- both digital and analog. Some of it through her research in AI. In fact, the two intersect -- part of her work is on developing AI that can enhance human creativity -- give people new tools for creative expression.

She was born in Tulsa, Oklahoma, USA. But you wouldn't guess from her name, how she looks, or how she sounds. She has lived in Riyadh, Saudi Arabia. She grew up in Ahmedabad, India. She currently lives in San Francisco, USA. She has an abysmal sense of space and orientation. She has an excellent sense of time. She hates small talk. She loves deep connections with people. She appeared in Forbes' list of 20 "Incredible Women Advancing A.I. Research". 

She has dabbled in sketching, painting, origami, dancing, music all her life -- she was decent at some of this, not so much at the rest :) She was first introduced to AI in 2003 in junior year of college and has worked in AI since. She was first introduced to generative art by a friend in 2018, when her day-job presented fewer opportunities to be hands-on with code. Generative art scratched the itch to code as well as explore AI for creativity.

Find out more about Devi's art at [http://stateoftheheart.ai/][soth]. You can also find her on [Twitter][tw], [Instagram][insta], [Foundation][fnd] and [fxhash][fxhash]. 

## The Visuals

Below are several Aragnations.

<div class = 'art'>
  {% for person in site.data.aragnation_1 %}
  <div class = 'aragnationpiece'>
    <a href = '{{ person.link }}'><img src = '{{person.link}}' alt = 'Aragnation'></a>
  </div>
  {% endfor %}
</div>

<div class = 'fullartpiece'>
<a href = './static/img/aragnation_11.jpg'><img src = './static/img/aragnation_11.jpg' alt = 'Aragnation'></a>
</div>

<div class = 'art'>
  {% for person in site.data.aragnation_2 %}
  <div class = 'aragnationpiece'>
    <a href = '{{ person.link }}'><img src = '{{person.link}}' alt = 'Aragnation'></a>
  </div>
  {% endfor %}
</div>

<div class = 'fullartpiece'>
<a href = './static/img/aragnation_22.jpg'><img src = './static/img/aragnation_22.jpg' alt = 'Aragnation'></a>
</div>

<div class = 'art'>
  {% for person in site.data.aragnation_3 %}
  <div class = 'aragnationpiece'>
    <a href = '{{ person.link }}'><img src = '{{person.link}}' alt = 'Aragnation'></a>
  </div>
  {% endfor %}
</div>

<div class = 'fullartpiece'>
<a href = './static/img/aragnation_33.jpg'><img src = './static/img/aragnation_33.jpg' alt = 'Aragnation'></a>
</div>

<div class = 'art'>
  {% for person in site.data.aragnation_4 %}
  <div class = 'aragnationpiece'>
    <a href = '{{ person.link }}'><img src = '{{person.link}}' alt = 'Aragnation'></a>
  </div>
  {% endfor %}
</div>


[artblocks]: https://www.artblocks.io/
[das]: https://abhishekdas.com/art/
[devi]: http://stateoftheheart.ai/
[das-photos]: https://www.instagram.com/abhshkdz/
[aragnation]: https://deviparikh.github.io/aragnation/
[sketchbook]: https://www.cc.gatech.edu/~parikh/sketchbook.html
[macrame]: https://www.cc.gatech.edu/~parikh/macrame.html
[origami]: https://www.cc.gatech.edu/~parikh/origami.html
[soth]: http://stateoftheheart.ai/ 
[devi]: https://www.cc.gatech.edu/~parikh/
[tw]: https://twitter.com/deviparikh
[insta]: https://www.instagram.com/deviparikh/
[fnd]: https://foundation.app/@deviparikh
[fxhash]:  https://www.fxhash.xyz/u/Devi%20Parikh