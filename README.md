# MF Photos - MS2

I decided to continue trying to develop my photography website but with a different approach. I opted to use a Bootstrap template from W3newbie.com. My reasoning was that going forward, I would specialise in Bootstrap, but will probably use 
templates in future professionally, as my background has been with WordPress thus far. It would also allow me to dissect and study a pre-made website, so I can learn how it all operates, hands-on while working on something productive for MS2. 
Using a template, I figured, would allow me to focus on JavaScript so, I would not need to worry about developing a a full HTML/CSS website and work out JavaScript too. Being a creative, I'm still very much not where I need to be when it comes to 
technical competence with all languages. I'm a visual thinker and very creative and I struggle coding. Despite what I thought was good reasoning, I ran into major issues but I'm optimistic and got some positive learning outcomes.  

Some of these issues, I will raise in the appropriate following sections. But mostly, I failed to reach the targets of the brief. One of the goals I want to achieve was to assign Google Maps API to the Contact section of the website. 
I was unable to do so. I also attempted to change tact last minute and use a Twitter feed API. 

The positive learning outcomes were that I learned about new things like using PHP Mailer as well as positioning JS engines like Popper. I learned how to get Google API keys and the basics of how to implement them and the logic JS
uses to run the API. Unfortunately, I was unsuccessful in my practical implementation of this but has inspired me to start again but from scratch. It has inspired me to question the ethics of using templates. Is it acceptable? What do is the 
consensus among developers? How practical is using templates and can I easily jump in and add JS to the existing template if there are all ready JS plugins being used?
 
## UX

Overview

Using a Bootstrap template, kind of removed some of the UX process. Because I opted to develop for a photography website, I already had certain cornerstones of UX principles in mind. My goal is to 
have users to be able to view my photography work quickly and to for them to contact me through the website or access contact details. I loved the idea of a single scrolling parallax website. It's the opposite of 
my thinking before. I still believe simple design is beautiful design. It's uncluttered. The visual art must speak for itself. However, a parallax site has the power to impress the user if done correctly. 

Humans and animals frequently move within their environments. Many behaviours that are essential for survival (e.g. foraging, fighting and fleeing), as well as behaviours for social interaction and entertainment (e.g. shaking hands or playing tennis), involve interacting with objects in three-dimensional space while we are moving in the world. Accurate perception of depth during self-motion is critical for success in many such tasks: for example, a lion will decide whether to chase a deer based on the distance between them, and a tennis player will stop running if the ball is not likely to be within reach.
The brain makes use of a variety of cues to estimate depth. These include pictorial depth cues that are present in a single static image of a scene, such as occlusion, relative size, perspective, shading, texture gradients and blur. Although such pictorial cues are valuable in interpreting three-dimensional scene structure, they generally do not provide precise quantitative information about depth. Additional powerful depth cues arise when a scene is viewed from multiple vantage points. Binocular disparity cues arise because the two eyes are separated horizontally and provide information about depth. Additionally, when an observer translates through the environment, motion parallax cues also provide a powerful source of depth information.[1]

I think the structure and effects of using a parallax design is immediately familiar to the user. It does not just provide an aesthetically pleasing result, but something more connecting on an evolutionary and biological level. Marrying this with the idea that when selling photography services, this 
parallax effect can help give a positive impression when presenting photographic work.

UX Considerations

Choosing the correct template is a kind of a process of elimination. There are plenty of templates that would be fit for other goals but perhaps not my own and more importantly the user in how they may want to interact with the website to achieve their goals. Having chosen a template, much of the “UX process” is trying to discern and I identify positive UX values within the selection of templates available online. It is all well and good, finding a template but I must think of the user in mind. So, I started with navigation. How easy is it for me to use? How many steps does it take me to get from the landing page to Contact? Are there calls to action? Use-case scenarios for a portfolio photography website are quite basic. And I appreciate my judgement of the template is subjective, and it’s anecdotal reasoning. So, I got an elder family member 
to test out the site. I gave the user 3 objectives. Find the gallery, find my number, and find out where I’m based. It’s not scientific but given their level of technical knowledge, which I would consider average for a person 60+ years of age, I thought it to be a reasonable indicator that the site
performed well when it comes to UX design. The 3 objectives were reached in a manner of seconds. 

Choosing the correct template is a kind of a process of elimination. There are plenty of templates that would be fit for other goals but perhaps not my own and more importantly the user in how they may want to interact with the website to achieve their goals.

## Features

**Contact form:** 
This is implemented using PHP Mailer. It came as a part of the template and I’ve been figuring out how to programme it to work using Gmail method as well as domain email method. However, I’ve yet to be successful with it. I am not sure if it’s because it’s not been hosted yet or if it should work in 
It's current state. 

**Google Maps API**
I struggled with this. I left myself with little time to fix it. I left the code in and it will show as a blank space at the end of the page. I did learn how to get Google API keys which was useful but essentially, I’ll need to practice on implanting that again. Perhaps on my own website from scratch, just to get it working.
 
### Features Left to Implement
What I really need is a client login page and login form so clients can view private galleries. 

## Technologies Used

**Bootstrap 4 template** –  For the website template <a href="https://w3newbie.com/product/photography-template/">Photography Website Template</a></br>
**Google Maps API** – For Google Maps display  - <a href="https://cloud.google.com/">Google Cloud Platform </a></br>
**PHP Mailer** – For contact form functionality - <a href="https://github.com/PHPMailer/">PHP Mailer – Git Hub</a> </br>
**HTML/CSS/Javascript** - For Google API </br>
**Photoshop/Lightroom** - For photo-resizing and manipulation - <a href="https://www.adobe.com/">Adobe</a>
**GitHub Pages** - For hosting - <a href="https://pages.github.com/">GitHub Pages</a>

## Testing

**Feature testing**

At first, Google Maps API was giving me specific error codes during the initial tests. Then it changed to more generic 404 error making it more difficult for me to figure out what it is. 

I'm unable to discern if PHPMailer is working as I have yet to test it online or even know if it should work while not hosted. 

As I opted to use a template, may fixes were applied, particularly display fixes when running on various browser. This is included in the coding notes. 

## Deployment

Deployed on hosting platform GitHub Pages. It's the same version of development version. I wanted to show it in the development state. 


## Credits

Drew Ryan of w3newbie.com

Unlimited Use Theme License:
Your use of the theme may extend to multiple websites or domain names.
You may use the theme for unlimited websites for your own purposes or for your clients.
You must not incorporate the theme in a work which is created for redistribution or resale by you or your clients.
The theme may not be redistributed or resold.
(https://w3newbie.com/licenses).

### Content
[1]The neural basis of depth perception from motion parallax, HyunGoo R. Kim Dora E. Angelaki, Gregory C. DeAngelis https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4901450/

### Media
- The photos used in this site were produced by mysself. 

### Acknowledgements

- I received inspiration for this project from Drew Ryan of w3newbie.com, also http://www.firewatchgame.com/

