# The Academic Philosophy Webring
This repository serves as a host for files relating to The Academic Philosophy Webring. Submit a Pull Request to be added (or removed!) from the Webring.

<img width="443" height="442" alt="Screenshot 2026-07-07 at 20 32 35" src="https://github.com/user-attachments/assets/4d1a9648-83f5-4e3d-8eff-94d7a2cb19d9" />

## 1. Why a Webring in 2026!?
I have a lot to say about this, and in time I will include some more information here, and on my website also. Until then, it suffices to say that the webring can function as a handy way of linking together our academic websites, and it helps to create a network for folks (like myself) who do not use smart devices and who rarely use 'traditional' forms of social media (i.e., apps like BlueSky or LinkedIn or X) but who are active on their websites.

When I get to writing more about the Webring and my aim for it, it will be available [here](https://megandrury-philosophy.neocities.org) (currently (as of 07/07/26) this redirects to my homepage). 

### Does this mean you have to be a Luddite to join the list?

Absolutely not. I hope that the Webring pulls together academic philosophers who use social media and who don't!

### I work in <insert (sub)field> here, can I join the list?

Absolutely! If it's in philosophy, or philosophy-adjacent, submit a request to add your website to the Webring. This is a *general academic philosophy* webring.

My hope is that eventually this main list might become a large community supplemented by sub webrings, such as 'The Philosophical Ethics Webring' or 'The Feminist Epistemology Webring'. 

## 2. How Do I Join The Webring?

The question of all questions, and I'm glad you asked. 

In this repository you will find 2 html files. One is titled *Webring-HTML.html* and one is titled Webring-Script.html.

First, open Webring-Script.html and copy (cmd-C or ctrl-C) everything between and including the element tags, <script> and </script>. 

Second, paste (cmd-V or ctrl-V) this <script> block into your HTML file (e.g., /index.html) toward the bottom of your file (above </body> is good). 

Third, open Webring-HTML.html and copy (cmd-C or ctrl-C) everything between and including the element tags, <philosophy-webring></philosophy-webring>. 

Fourth, paste (cmd-V or ctrl-V) this <script> block into your HTML file (e.g., /index.html) wherever you would like the Webring 'widget'/'component' to appear. 

Fifth, remember to change 'YOUR URL HERE' to your website, (e.g. *https:// philosophy-of-cats . phil . org*) exactly as you entered it into the Philosophy-Webring-Data.json or nothing will happen!

Sixth, copy and paste the block provided in webring-CSS.css somewhere in your style.css file (or whatever you named your CSS file).

Seventh, enjoy your new home in the Academic Philosophy Webring! (or mess about with the HTML/CSS/JS until it behaves...)


## 3. A Note on the Code
### Credit Where Credit is Due
Though my HTML and CSS have been improving over this year, my JS leaves a lot to be desired. Fortunately for me, and for other philosophers similarly inclined, Chris Coyier at CSS-Tricks developed a [tutorial](https://css-tricks.com/how-you-might-build-a-modern-day-webring/) and helpful code template for a modern Webring! Thanks Chris. 

I would have forked [Chris' repository](https://github.com/CSS-Tricks/css-webring/tree/main) for direct credit, but I'm new to Github and was worried about accidentally pushing changes, so thought it safer to create a separate repo, just in case!

### My Code...
Aspects of my additions to the code are inefficient, but I will be tidying it up in good time. (Likely if this project happens to gain traction). 
