# simple-carousel
A really simple carousel that requires jQuery. Also it doesn't come with controls.

### Usage:

    var c = new Carousel('#carousel-1'); // and that's it
    c.auto_next(3000); // make it move on its own every 3 seconds
    c.auto_previous(3000); //  make it go the other way
    c.stop_auto(); // make it stop
    c.next(); // go to the next slide
    c.previous(); // go to the previous slide
    c.move_to(2); // go to a certain slide
