= Create the visual structure for a project

Utilizing the zipped psd file in this repository

1) 


The objective is to create the Schedule an Appointment page from the included pst file.

The output should include the following structure:

schedule_appointment.css
index.html

<b>many</b> different albums. The widget will look something like this:

http://s3.amazonaws.com/ember/F65U5o7orp42zOLoTpGlUYbiUAN5EWIp_o.png

The carousel bar in the left is what you see in the ui at first.
Each image in the carousel represents the main album image,
each album has an X amount of images.
When you click on an image of the carousel bar
an overlay similar to the one on the right pops up.

The overlay displays the same carousel in the bottom and the first
image from the album that was clicked in the top. When another 
image from the carousel in the bottom is clicked, the top part
loads the first image from the album that was clicked.

The top left/right arrows navigate through the pictures of a particular
album. The bottom left/rignt arrows navigate through the album collection

== The input

The input will be an array of hashes like such:

    [
      {
        name: 'My Grand Mothers Bday',
        album_image: 'path_to_image/image.png'
        images: ['path_to_image/image.png', ...]
      }, ...
    ]

== The nitty gritty

You can hard code the array of hashes in your code or you can load
it from the dom for extra points.

Also for extra points you can add fancy styles and effects!

Finally if you want even more extra points you can provide your
widget with an api to be used as a plugin.

== The deliverable

Please fork the complete repo and create a folder named 'solution'
in the same folder where you find this READEME.rdoc file.

The folder must contain this structure

    solution/
      index.html
      carousel.js
      javascripts/
        your_favorite_library.js
      css/
        carousel.css
      images/
        any_images_you_might_need.png

Commit as often as you can and push your solution when its finished.
At least push once when you start the solution and once you end it,
we would like to see the time it took to reach your solution also.

== Notes and Caveats

* Please only use a single library or framework. 
* Don't use any plugin
* We preffer you only use JQuery.
Vimium has been updated to 1.30.x
