----------------------------------------------------------------
 Development page & Debugger
 (work in progress)
----------------------------------------------------------------

 @version: v0.1 (beta) 

 - Gives you a save rapid prototyping environment  
 - Helps you adding the right blueprint classes 

Does only work in browser newer than... 
 + Firefox 1.0
 + Opera 7.0
 + Konquerer 3.4
 + Safari 1.2
...and won't work in IE due to missing support for "outline"


----------------------------------------------------------------
 Credits
----------------------------------------------------------------

 @author: Created by Franz Josef Kaiser [http://say-hello-code.com]


----------------------------------------------------------------
 Usage
----------------------------------------------------------------

 1) Adjust the head of your dev environment page to your needs.
 2) Uncomment the plugins you want to use in your page.
 2.a) -optional- only needed for the mailing list: 
	  describe your goals, trials & errors in the head container.

 3) Add your basic html structure (div, h1-h6, p, span, a).
 4) Add some "lorem ipsum" dummy text and sample imgs to your html. 
 5) Add your blueprint classes to the structure.
 6) Uncomment the css/html debugger plugin in the head.
 7) Open the sample in your browser.

 7.a) -optional- if you see elements outlined, you've forgotten 
	  declarations or added not matching classes.
	  In this case take a look at the head of the debugger 
	  plugin to check color codes & find out what exactly went wrong. 

 8) -done-

----------------------------------------------------------------
 Changelog
----------------------------------------------------------------

v0.1 (alpha) - first version
 + a basic html page structure
 + debugger offers outlining of classical misstakes
 
v0.1 (beta) - debugger now offers help for missing declarations
 + dev page reworked to split between description & content
 