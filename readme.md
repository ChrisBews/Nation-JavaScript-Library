What is this?
==============
Put simply, this is a collection of classes that will help you build stuff. These aren't plugins, so coding knowledge is required to put all the pieces together.

How do I use it?
==============
* Decide which classes you want to use
* Check if they have any dependancies (most need Nation.Utils)
* Copy/paste them into your project and include them in your page
* Prepare your HTML and CSS however you want it
* If the class you're using requires certain CSS classes or styles to exist, these docs will tell you what you need to add
* Code your JavaScript however you want, making use of the Nation library where needed

Core concepts
==============
This library was born out of a need to simplify common tasks, without being restrictive in the way that plugins often are. Each class will only add the minimum amount of styles required to achieve the desired functionality. This often means that the developer has to have a general understanding of how each feature is intended to work, as they will sometimes need to ensure that compatible styles are in place in their build for the application to function correctly. For example, the Slideshow class relies on animation of the 'left' property by default, so the slides in the developer's HTML need to have either position: relative, or position:absolute in their styles, or else there will be no visible result.

These docs try to point out instances where specific styles are required, but in general it is a good idea to understand the basics of how the required feature(s) in this library work, in order to get a working result. The benefit of this approach is that this library will not overwrite your own HTML or CSS, so you are always fully in control of how things look, and how your HTML is structured.

What this isn't
==============
* A jQuery replacement
* An Angular/React/Backbone/etc replacement

Something is broken!
==============
It's early days, this is definitely going to happen. Please report the bug to Library HQ - [chris@wearenation.co.uk](mailto:chris@wearenation.co.uk)