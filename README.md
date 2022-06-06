<a href="https://blasphelmy.github.io/flipper-js/" target="_blank"><h1 align="center">Flipper Js</h1></a>

<div align="center" id="top"> 
  <img src="././images/prview.gif" alt="Flipper Js" />

  &#xa0;
</div>

<!-- Status -->

<!-- <h4 align="center"> 
	🚧  Flipper Js 🚀 Under construction...  🚧
</h4> 

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="#author-Author">Author</a> &#xa0; | &#xa0;
</p>

<br>

## :dart: About ##

A quick and easy to use script for creating a masonary layout with contents

## :sparkles: Features ##

:heavy_check_mark: Easy to use
:heavy_check_mark: Clean

## :rocket: Technologies ##

The following tools were used in this project:

- [Masonary](https://masonry.desandro.com) included

## :checkered_flag: Starting ##

```bash
#the html
<div id="cardcontainer" class="res" style="max-width:100%">

    <div id="A_UNIQUE_ID" class="card scale _flipper"> #any cards you want to apply the flipping effect to, add in the defining class. In this case, it's named _flipper
        <div id="A_UNIQUE_ID_content" style="position:relative">
            #front of card goes here
        </div>

        <div class="hide _backPanel" id="A_UNIQUE_ID_backPanel">
            <div class="text">
                #back of card goes here
            </div>
        </div>
    </div>

</div>

# Javascript
window.onload = () => {
    flipper({
        flipperClassName: "_flipper", #name of our flip class. Omit period
        container: "#cardcontainer" #name of card container
    });
}
```

## :memo: License ##

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

## :author: Author ##
Made with :heart: by <a href="https://blasphelmy.github.io" target="_blank">David Nguyen</a>

&#xa0;

<a href="#top">Back to top</a>
