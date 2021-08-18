# Nav Bar
We will be applying methods and grabing values on the Nav Bar. IE (Add Classes, Add Events, Using Elements Location & Dimensions).

## Features
- Adds overflow hidden on HTML/Body Tag.
- Adds all the styling to handle if it's fixed or static.
- Takes an element you want to be the hamburger to attach events like click and resize
- Takes an element you want to as Nav Bar & returns object providing details that will help run conditionals based on the scroll and resize events of the window. Providing you with the ability to add or remove classes based on the location and size of the window. Stuff like close the navbar on window resizes or when a link is clicked.


| NAV BAR | Objects, Values, Events |
| ------ | ------ |
| Nav Bar | elm.obj, elm.x, elm.y, elm.height, elm.width |
| Hamburger | Click Event, Resize Event |
| Window | ScrollTop Property, Scroll Event, Resize Event |



# Full Bleed
A Full Bleed layout that can be a Slider, Image or Video & the Slider and Video have mouse interaction options for buttons.

| Video | Component |
| ------ | ------ |
| Play Button | Takes a play button element |
| Video Poster | Takes a image |
| Video Src | Takes a video ref to display video, url, id depending on plateform |
| Callback | Takes a function to be called when in viewport |

| Image | Component |
| ------ | ------ |
| Image | Takes a Image |
| Callback | Takes a function to be called when in viewport |

| Slider |  Component |
| ------ | ------ |
| Slides | Takes in a html object wtih all information (Image, Headline, Paragraph, buttons, links, Captions)|
| Pagination | Takes in data to display pagination |
| Progress Bar | Takes in elements location you want to add the progress bar. (Progress can come in circle or line form)  Styles scoped in component |
| Arrows | Takes elements you want to add the arrows too |
| Callback | Takes a function to be called when in viewport |


| Mouse | Mouse Interactions  |
| ------ | ------ |
| Follow Cursor | Button follows cursor well in Full Bleed Component |
| Magnetic Button | Button feels  magnetic when cursor because in to proxy |


| Image / Video / Slides | Scroll Interactions  |
| ------ | ------ |
| Offset Scroll Reveal | Added some offsetting to give a image/video reveal on scroll |
| Scale Scroll Reveal | Added either scale up or scale down to give a image/video more reveal on scroll |


# Two Ups
Two Ups 
| Two Ups |  Component |
| ------ | ------ |
| Elements | Takes in a html object wtih all information (Image, Headline, Paragraph, buttons, links, Captions)|
| Columns | Takes Columns to be used on each breakpoint |
| Callback | Takes a function to be called when in viewport |

# Slider
A slide layout - Slides can be Images or Videos and have mouse interaction options for buttons.
| Slider |  Component |
| ------ | ------ |
| Slides | Takes in a html object wtih all information (Image, Headline, Paragraph, buttons, links, Captions)|
| Pagination | Takes in data to display pagination |
| Progress Bar | Takes in elements location you want to add the progress bar. (Progress can come in circle or line form)  Styles scoped in component |
| Arrows | Takes elements you want to add the arrows too |
| Callback | Takes a function to be called when in viewport |


# Modal
Modal- A class will be add to body that will lock the viewport and a element cover the site will have a click none event masking website and a modal will be added on top of that when activeated and will have a close and open button.
| Modal |  Component |
| ------ | ------ |
| Modal Element | Takes element you want the parent modal be |
| Activate Element/s | Elements when clicked opens modal |
| Deactivate Element'/s | Elements when clicked closes modal|
| Click out of Modal close Option | Boolean to decide if you want to close it if clicked outside of modal |

# Grid Layout
| Grid Layout |  Component |
| ------ | ------ |
| Grid Items | Takes an array of elements to display |
| Transitions Items | Takes in Speed, delay, staggering & easing for grid items |

| Mouse | Mouse Interactions  |
| ------ | ------ |
| Hover Item | Button follows cursor well in Full Bleed Component |
| Follow Cursor | Button follows cursor well in Full Bleed Component |
| Magnetic Button | Button feels  magnetic when cursor because in to proxy |



# No Landscape
No Landcape - Covers up Screen when in landscape mode.
| No Landscape |  Component |
| ------ | ------ |
| When to activate No Landscape | Take a string that (Phone, Table, Ipad Pro, Desktop)|
| Headline| Takes in Headline html text |
| Paragarph | Takes in paragarph html text |

# Accordion
| Accordion |  Component |
| ------ | ------ |
| Elements | Takes in a html object wtih all information (Image, Headline, Paragraph, buttons, links, Captions)|
| Toggle Element | Takes class to toggle to close |
| Close Others if already opened | Boolean if you want to close others when you open one. |
| Callback | Takes a function to be called when in viewport |

| Mouse | Mouse Interactions  |
| ------ | ------ |
| Hover Item | Button follows cursor well in Full Bleed Component |
| Magnetic Button | Button feels  magnetic when cursor because in to proxy |



# Age Gate
| Age Gate |  Component |
| ------ | ------ |
| Modal Element | Takes element you want the parent modal to be |
| Age | Takes in age to allow access |
| Yes | Takes element for Yes |
| No | Takes Element for No |


## Features
- Adds overflow hidden on HTML/Body Tag.
- Uses Vue store to keep session cookie
- Takes Age Number to get in.

