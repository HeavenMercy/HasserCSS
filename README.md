# Hasser-CSS
A lite and flexible CSS framework (Inspired by Skeleton CSS)

Hasser is primarily made to define the style of the contained tag on the container one.
```html
<!-- says "I have a button with the 'success' style inside" -->
<span class="has-button-success">
    <span>Fake...</span> <!-- this tag will be styled by the parent class -->
</span>
```
It was difficult to apply a style on a Symfony form without having to create a bundle/module. I wasn't familiar with the framework, so I decided to create this and wrap parts of form to style them.

**Particularities**
+ Has a flexible 6 column grid designed on/for desktop and automatically adapted for the the other screens. For rigid/static/"not flexible" column, append '-noresp' to the column class.
+ Has a hero style, a &lt;div/&gt; that will take all the page width and height

*To see all the available class, consult the file 'hasser_repert.txt'* <br/>
*To see the framework in action, open the file 'documentation.html'*

Don't hesitate to notify me of any issue, so that I can fix it quickly. <br/>
And you can send me any request or suggestion. <br/>

Good luck !

PS: If you like that framework, please spread the word ! I am not yet popular :lol:.
