# pins

Photos for the `/pins` wall (`pins.html`).

Drop images here named `01.jpg`, `02.jpg`, … `12.jpg`. Each card on
`pins.html` loads the matching number; a card whose image is missing simply
hides itself, so you can add photos incrementally.

The frame crops to a fixed aspect ratio (`object-fit: cover`), so any image
dimensions work. To add more than 12, add another `<figure class="pin">`
block in `pins.html` and a matching `NN.jpg` here.
