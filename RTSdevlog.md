[Back](index.md)

# RTS Devlog
## Idea :bulb:
The idea is to make a multiplayer Real Time Startegy game inspired in my favorite games, like: Age of Empires, Imperium, Sparta, Battle for the Middle Earth, Praetorians, Civilization, Starcraft...

## Log :newspaper:

### First post! - 31/7/2019
I've been working in this project now for two weeks and I'm learning so many things. It's not my first Unity project but it's the first one that I'm very exited with (pretty ambitious though).

Right now I'm focused in the main aspects of the game, like building structures and the movement of the units so everything is made out of cubes and spheres, the cool graphics will come later. 

Here's the **builder** unit, when you click on it all the buildings that it can create will appear at the bottom of the screen. Then, the structure that you select will follow your mouse on the plane and with another click it gets placed down with a small particle effect. Both objects have a health bar on top that follows the camera view.

![](/gifs/construir_cuartel.gif)

You cannot build in the space of another structure. The one that you're trying to create turns red and it's not buildable. Currently the structures cannot rotate during the build process but they will.

![](/images/cannot_build_there.png)

Here's a test with a **laser soldier** unit, when another unit with different team number enters in the attack range of the unit a laser appears dealing some damage per second.

![](/gifs/laser_soldier.gif)

With this basic structure and units I'm now planning to implement two factions. The idea is to have several civilizations from different moments of the history combined. For example, the romans vs some random futuristic civ.

## Comment and get a cookie :cookie:!
Any feedback will be appreciated.

<div id="disqus_thread"></div>
<script>
    (function() {  // REQUIRED CONFIGURATION VARIABLE: EDIT THE SHORTNAME BELOW
        var d = document, s = d.createElement('script');
        
        s.src = 'https://guilleqp.disqus.com/embed.js'; 
        
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>