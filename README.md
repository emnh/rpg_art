# RPG Art

AI Generated RPG Art using Stable Diffusion 1.4 and 1.5.

Source images: Dungeon Crawl Stone Soup public domain 32x32 images.

![Boggart the Gnome](ai_art/char_boggart.png?raw=true "Boggart the Gnome")

# Introduction

I used stable diffusion 1.4 and 1.5 with license at https://huggingface.co/spaces/CompVis/stable-diffusion-license. I used the tool https://github.com/AUTOMATIC1111/stable-diffusion-webui/ and as outlined how to install in https://www.youtube.com/watch?v=6MeJKnbv1ts . I used the techniques described in https://www.youtube.com/watch?v=blXnuyVgA_Y&t=871s .

Out of more than 30,000 generated images I selected the best 1,500 or so for publishing.

As input images to stable diffusion I used 16x hqx upscaled versions of https://opengameart.org/content/dungeon-crawl-32x32-tiles-supplemental . They are under public domain. For 2 of the variants (one battle axe and the purple rage creatures) I used also https://opengameart.org/content/dungeon-crawl-selected-upscale .

All images are 512x512 resolution.

I do not provide the input prompts used to generate the images here but you can run the imagemagick command identify on the image to get the parameters:

```sh
ai_art$ identify -verbose altar.png | fgrep parameters
parameters: Video game art by Shaddy Safadi and Ariel Fain and Calvin Boice of an altar in
the style of world of warcraft and breath of the wild, 8k, intricate, detailed, zoomed out
```
 
# Copyright/Attribution Notice
I release this art under public domain as the originals.

# Monsters Preview
![Monsters Preview](previews/monsters_preview.png?raw=true "Monsters")

# Weapons Preview
![Weapons Preview](previews/weapons_artefact_preview.png?raw=true "Weapons")

# Icons Preview
![Icons Preview](previews/ai_art_preview_224.png?raw=true "Icons")
