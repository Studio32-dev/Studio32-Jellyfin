<div align="center">
<h1>JellySkin</h1><h3>Use 67% or 70% zoom in web browser for better experience</h3>
<h4>Note:To take full experience of this CSS on fire fox click <a href="#firefox">here</a></strong>.</h4>
</div>
<br>
This is JellySkin:
To use just copy this :

```css
@import url("https://studio32-dev.github.io/Studio32-Jellyfin/default.css");
```
To use Logos like the images given below use:

```css
@import url("https://studio32-dev.github.io/Studio32-Jellyfin/Logo.css");
```

To use different gradient for your buttons I have added few different gradients you can choose or you can create your own (check the steps given bellow), the default gradient used is jellyfin's default logo gradient,using this alone will only skin the button colors and I know the names for this are very funny:
```css
@import url("https://studio32-dev.github.io/Studio32-Jellyfin/seaGradient.css");
@import url("https://studio32-dev.github.io/Studio32-Jellyfin/sunsetGradient.css");
@import url("https://studio32-dev.github.io/Studio32-Jellyfin/morningGradient.css");
@import url("https://studio32-dev.github.io/Studio32-Jellyfin/nightSkyGradient.css");
```
and past it in custom css text box and click save. To open Custom CSS settings go to Dashboard>General>Custom CSS.
<br>
Using custom own Gradient or color
Create your gradient or solid color and past it in ```--custom``` and gradient in opposite angle in ```--customsel``` :
```css
:root {--custom: your gradient;}
:root {--customsel: your gradient in opposite angle;}
```
Now, to use your own Gradient (to get great button or any gradient go to https://cssgradient.io/gradient-backgrounds or https://cssgradient.io) or solid color:
```css
@import url("https://studio32-dev.github.io/Studio32-Jellyfin/customCol.css");
```  
<h3>Here are some images:</h3>

<h5>Login Page</h5>
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/login.jpg">

<h5>Home screen:</h5>
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Home.jpg">

<h5>Library View</h5>
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Movies.jpg">
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/TV%20Shows.jpg">
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Collections.jpg">

<h5>Title screen:</h5>
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Title%20Page-Movie.jpg">
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Title%20Page-TV.jpg">

<h5>TV Shows Season Episode list:</h5>
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Ep-list.jpg">

<h5>Dialogs</h5>
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Menu.jpg">
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Dialog-1.jpg">
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Dialog-2.jpg">
<img src="https://studio32-dev.github.io/Studio32-Jellyfin/img/Dialog-3.jpg">
<br>
<br>

<div class="conribute" align="center" style="text-align: center;">
<h2> Wanna Contribute? </h2>
<ul>
<li>Fork this Repo</li>
<li>Add your features</li>
<li>Create a Pull Request</li>
<li>Wait for it to be merged.</li>
</ul>
</div>
<br>
<br>

<div class="firefox">
<h4 align="center">Enabling backdrop-filter in firefox</h4>

```
Deaktiviert From version 70: this feature is behind the
layout.css.backdrop-filter.enabled
preference (needs to be set to
  true
  ) and the
  gfx.webrender.all
  preference (needs to be set to
    true
    ).
 To change preferences in Firefox, visit about:config.
```

</div>
