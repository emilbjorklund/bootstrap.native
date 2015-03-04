# Bootrstrap Vanilla JS
This is a set of scripts formely jQuery Plugins for Bootstap, and now dependency free scripts to be used on performance driven apps and websites.

# Bootrstrap Affix JS
* works with both JS call and via data attributes
* works with pinning to top <b>only</b>
* when target option is used, will automatically calculate that element position
* readjusts on window resize with a small delay (for performance reasons)

<pre>
//call the affix via js call
var sidemenu = new affix(element, options);

//call the affix function via data attributes
&lt;div class="content" data-spy="affix" data-target=".selector">
  //this is when you need to stick to a certain ELEMENT
&lt;/div>

//OR

&lt;div class="content" data-spy="affix" data-offset-top="250">
  //this is when you need to stick to a certain position to top
&lt;/div>


# Bootrstrap Vanilla JS License
The scripts are released under the MIT license.