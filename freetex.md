# Installing (La)TeX 

<br/><br/>

## Start Here (if you're starting from scratch) 
 
	                 
	                       
	                    
### The Bottom Line 
  &#128176;  Download and install <a href="#MT">MikTeX</a>.

  * MikTeX is available for most operating systems.  Also  <a href="https://www.tug.org/texlive/" target="_blank"> Tex Live</a> is an alternative. If you like apples, you may be interested in  the  <A HREF="https://www.tug.org/mactex/">MacTeX</A> page. 

&#128176;&#128176; [OPTIONAL] Download and install an editor. The MikTeX distribution includes a simple editor and previewer. I listed some additional full featured <a href="#editors">editors</a> below. There are many free editors and you should try a few before you settle on one. 	 


&#128176;&#128176;&#128176; [OPTIONAL] Download and install <a href="#GS"> Ghostscript </a> (and Ghostview if you want it). You don't need this  if you just use pdflatex, but you might want to  get it to keep your options open.   

<br/>
&#128175; For details on these steps and more, just keep scrolling down. 

---
---

 <br/>



<a name="MT"></a>   
## MikTeX
		
Get MikTeX and install it. MikTeX is simple to install - just go to the <A HREF="https://miktex.org" target="_blank">MikTeX Homepage</A> and download a (basic system or complete system)  setup wizard. The basic system is a quick set-up that automatically pulls packages off the internet as you need them.  This should be fine for most users.


Is there an alternative to MikTeX?  Yes- it's called  <a href="https://www.tug.org/texlive/" target="_blank"> Tex Live</a>
 

NOTE: The MiKTeX installation now includes <a href="https://www.tug.org/texworks/" arget="_blank">TeXworks</a>, which is an editor and a pdf reader/previewer.  So basically, all you need to start pdflaTeXing is MiKTeX.   If you're just starting out, then this should be fine ...  for awhile However, my suggestion is to get one of the TexMakers and SumatraPDF-TeX instead of using TeXworks. 

<br/>              
 
## Editors
		
There are many different editors and  a nice list and discussion of editors can be found at <a href="https://tex.stackexchange.com/questions/339/latex-editors-ides" target="_blank">  stackexchange</a> ... it seems to be updated peridoically.  I'll just list a few below. 
		
	
<a name="TM"></a>
 - Lots of people (and juggalos) like <a href="http://www.xm1math.net/texmaker/" target="_blank"> TexMaker</a>.  It comes with an integrated pdf viewer and all the bells and whistles that a modern 
editor should have... and, it's actively maintained.  The creator of TeXMaker is also the creator of Kile (a great Unix based editor). It is also possible to use <a href=" https://www.latex-community.org/forum/viewtopic.php?f=20&t=8212" target="_blank"> Kile </a> on WinDoze.  


 - Another option is <a href="https://texstudio.sourceforge.net/" target="_blank">TexStudio</a>. Basically, it started as a TexMaker ripoff, but it has  many more  configuration  options ...  it used to be called _TexMakerX_. 


- As previously indicated, the MikTeX distribution now includes an editor</em> called <a href="https://www.tug.org/texworks/" target="_blank">TeXworks</a>. It's a bit too simple for my tastes, but if you're a first time user  it might be best to use _TeXworks_ until you need something more versatile.
 
<br/>

> TexMaker and TexStudio (and others) come with a built-in previewer that is pretty good, but it doesn't render graphics very well. A better option is to get <a href="https://www.sumatrapdfreader.org/download-free-pdf-viewer.html" target="_blank">SumatraPDF</a>. It is small and you can use it as general pdf reader instead of acrobat. You can easily configure many editors to use it; see this page for <a href="https://william.famille-blum.org/blog/static.php?page=static081010-000413" target="_blank"> Configuring editors with SumatraPDF</a>.  Some editors allow inverse search, but it is specific to the editor... an internet search on "inverse search [name of my editor]" will do the trick.

<br/> 

 <a name="fonts"></a>

> A NOTE ON FONTS: Most of these editors use fixed width or monospace fonts,  and while the monospace fonts are better than they used to be, I still use  <a href="https://www.dafont.com/bitstream-vera-mono.font" target="_blank"> Bitstream Vera Sans Mono</a> in all my editors.  It is very good in that it is easy on the eyes and it's easy to distinguish between similar looking characters such as "l" , "1" , "i" and "o" , "0" , "O".

>  If you came down here looking for additional LaTeX fonts, you can find information about them at <a HREF="https://www.tug.dk/FontCatalogue/" target=new>The LaTeX Font Catalogue</a>. 


<br/>
	  
<a name="GS"></a>   
## Ghostscript
		
I  recommend  getting <a HREF="https://www.ghostscript.com/download/" target=new>Ghostscript</a>. It's not necessary if you use pdflatex, but other programs depend on it.  It's small, so storage shouldn't be a problem.  

<br/>

<a name="SC"></a>     

## Spell check 

This is an old topic... most 21st century editors check spelling.   <a href="http://aspell.net"  target="_blank">Gnu Aspell</a> is still around (but old), and if you need additional dictionaries, you can use the ones from Open Office:


 
>  Some editors use the spelling engine of  <a href="https://www.openoffice.org/" target="_blank">OpenOffice</a>   and you can download   <a href="https://www.openoffice.org/lingucomponent/download_dictionary.html" target="_blank"> dictionaries</a> for it, if necessary.  The dictionary files are archives with an .oxt extension.  If you have something like  <a href="https://www.7-zip.org/" target="_blank"> 7-zip (free)</a>, you can expand it.  If not, just change .oxt to .zip and use your native extracter.  You'll need 2 files, the .dic AND the .aff file. Put them in a convenient location and then configure the editor so it knows where those files live. 

<br/>

<a name="PPT"></a>     
 
## LaTeX in Presentations


Use <a href="https://bitbucket.org/rivanvx/beamer/wiki/Home" target="_blank">BEAMER</a>. It's not easy, but to get started:

> First, go here <a href="http://www.informatik.uni-freiburg.de/~frank/ENG/latex-course/latex-course-3/latex-course-3_en.html" target="_blank">BEAMER CLASS EXAMPLES</a> and download the first example, example-1.tex.  Compile the file and MikTeX will automatically download everything it needs to compile the file if it is not there already (assuming you let MikTeX install what it needs on the fly - this is set in the MikTeX Options).     Play around with the file... make some minor changes and compile it again until you feel comfortable with what you're doing.

> Then go back to website and download each of the other example-x.tex files, play with them ... add or change some things ... and  compile them.  By the time you're done, you'll have a pretty good idea of how to work the beamer machine.  If  you still need help, google "beamer" and you'll find all sorts of examples (<a href="http://www.tug.org/teTeX/tetex-texmfdist/doc/latex/beamer/beameruserguide.pdf" target="_blank">Beamer User Guide</a>). 




- BUT, if you MUST use PowerPoint (you'll need Ghostscript),  use  <a href="https://www.jonathanleroux.org/software/iguanatex/" target="_blank"> Iguana Tex</a>.  I've tried it and it works like a charm.


 <br/>
 
<a name="code"></a>  

## Providing CODE in Your Documents

 After trying various methods, I think the best way to include code in a document is to use  the package called <a href="https://www.ctan.org/tex-archive/macros/latex/contrib/listings/" target="_blank">Listings</a>.   The <a href="https://en.wikibooks.org/wiki/LaTeX/Packages/Listings" target="_blank"> Wiki LaTeX Book</a> has a nice page on using the package. MikTeX will install it, if necessary, when you put `\usepackage{listings}` in the  preamble.
 
 <br/>

<a name="texhtml"></a> 	
## Math, TeX and HTML
	
<p>Javascript method: <a href="https://www.mathjax.org/" target="_blank">MathJax:</a>	

Here's what you can do. Inline math is kewl,  $ X_t = \int_{-\pi}^\pi e^{i\omega t}dZ(\omega)$. Even blackboard bold works:   $ \{X_t;\, t\in \mathbb Z  \} $. Then   some display:
$$  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}  $$
This is easy to use- just a line in your head (of your web page) does the trick.   Try it, your friends will be amazed.  _If you want to see the code for this stuff, right click on an expression and choose "Show Math As"_

For long and complicated math, I think using a pdf file is the best way to go. If you don't want to use javascript, then using html tables, you can do some complicated expressions ... the problem is that different browsers will display the expressions differently (see <a href="https://www.myphysicslab.com/web_math.html" target="_blank"> web math</a>).  Simple expressions such as <i class="eqn">X(t) = &int;	e<sup>i&omega;t</sup> dZ(&omega;)</i> are easy to do with <a href="https://www.w3.org/TR/REC-html40/sgml/entities.html" target="_blank">HTML 4</a>.</p>

<br/>

<a name="yousuck"></a>  

## You say you suck at LaTeX

... and you want to learn more.

- Do an internet search on "Latex Basics" or "Learn Latex"... you'll pull up a couple of million sites with useful info, some videos, and probably some porn.

- Here's an online <a href="https://en.wikibooks.org/wiki/LaTeX/" target=new> LaTeX Wiki Book</a>.

- Here's a free pdf text (~300 pages) on LaTeX: <a href="https://tobi.oetiker.ch/lshort/lshort.pdf" target=new>A Short Course</a>.



The key to getting started  with LaTeX, as with most things, is to start small; do something that you can throw away.  And use the internet to search on things like "latex union" to figure out how to write things like <em class="eqn">A &cup; B </em> .


<br/>
<a name="links"></a> 

## Some LinKs  

Here are some other  links to great TeX sites ...

- <a href="https://texblog.org/" target="_blank"> TeXblog</a> ... the name says it all ...   

- So you want to write something like  <i>A &cup; B</i>, but `$A \union B$` doesn't work!!! Can't think of the LaTeX name of that symbol??  Try this site: <a href="https://detexify.kirelabs.org/classify.html" target="_blank">Detexify</a>.

<a name="E2L"></a>
- <a href="https://www.ctan.org/tex-archive/support/excel2latex/" target="_blank">Excel2LaTeX</a>   When it comes to making tables, LaTeX is a PaiN ... especially if your editor does not allow or is inept at
column mode editing.  _Excel2LaTeX_ allows you to transform the current selection from Excel to LaTeX.  I've used this and it works pretty well... although, for the most part, I'll do my tables in [Crimson Editor](http://www.crimsoneditor.com)  and then paste it in my TeX document.  I do it this way because the column mode editing in CE is excellent. Some advanced editors have a table tool built into them. There is also an [online table generator](https://www.tablesgenerator.com). 


- <a href="http://www.ctan.org/what_is_tex.html" target="_blank">Why TeX?</a> Ten good reasons (check out reason number 8) and some history, too.

 

- <a href="https://mirrors.ibiblio.org/pub/mirrors/CTAN/info/short-math-guide/short-math-guide.pdf" target="_blank">AMS-LaTeX</a> If you're typing math, you should check out (and use) AMS-LaTeX. It's  included in the MikTeX distribution, but take a look at the short guide (a pdf file) for a quick start.


- Tips on using  <a href="https://www.sharelatex.com/learn/Using_colours_in_LaTeX" target="_blank">color </a>   in LaTeX.

-  <a href="https://cseweb.ucsd.edu/~swanson/papers/science-of-writing.pdf" target="_blank">The Science of Scientific Writing</a>. Well, if you're going to be writing, you might as well get a few tips.This is worth reading for fun and for profit!


-  <a href="https://www.tug.org/" target="_blank">TUG</a> the TeX Users Group.

- <a href="http://www.latex-project.org/" target="_blank">The LaTeX Project Page</a> where you can also...
<img src="figs/lion.png" alt="latex lion"> ... find out what  is up with the <a href="http://www.dream.kn-bremen.de/tex/merchandising/lion/"  target="_blank"> TeX lion</a> and try to figure out why it's wearing lipstick and has a perm and wears glasses, and why someone would associate a lion with TeX in the first place, and why you still see that damn thing. 

---
---

<br/>

_That's all Folks!_