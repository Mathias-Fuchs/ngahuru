## Screenshot ##

<img src='http://ngahuru.googlecode.com/files/Ngahuru_screenshot.png' align='middle' width='380'>

<h1>What is it?</h1>
There are lots of distraction-free text editors out there.<br>
Here's mine: it's just my re-interpretation of the theme.<br>
In short, it is intendend to be the ultra-simplistic editor, but with syntax highlighting.<br>
There's a menu bar for the most basic of needs (open, save, choose font), which is readily hidden by Ctr-m.<br>

Working on a paper in LaTeX? This editor might be worth a try.<br>
<br>
It is based on gtk+, featuring<br>
<ul><li>a beautiful interface<br>
</li><li>syntax highlighting.</li></ul>

No dependence on huge Qt libraries, no Python messages at runtime, everything in barely more than a few hundred kilobytes of pure C. Compilation should be as painless as possible. Since it is based on gtk, it is fully configurable by the .gtkrc-2.0 configuration file in your home folder; this concerns appearance, background/foreground color, menu bar fonts etc.<br>
<br>
The editor font itself can be chosen in the menu bar, the screenshot has used "Gentium 15".<br>
<br>
The closest software in the debian packages, for instance, is Pyroom, which is much larger, but lacks syntax highlighting (at least in my debian stable) and depends on Python.<br>
<br>
It is supposed to be a program in which you can't do anything - EXCEPT type, which is exactly what you might want to do.<br>
Just hide the menu bar with Ctrl-m, and write.<br>
<br>
Basically, Ngahuru is a leafpad fork, but uses the gtksourceview library for syntax highlighting.<br>
<br>
Ngahuru is Maori for "autumn" - which is reminiscent of the "leaf" in "leafpad".<br>
<br>
<h1>Installation</h1>
<ul><li>Download <code>Ngahuru-0.1.tar.gz</code> from "Downloads", or alternatively, if git is installed (sudo apt-get install git-core)</li></ul>

<pre><code>git clone https://code.google.com/p/ngahuru/<br>
</code></pre>

from the git repository.<br>
<ul><li>Ngahuru should compile easily on any GNU/Linux on which the dev-versions of gtk+-2.0 and gtksourceview-2.0 are installed. For instance, on any Debian-based system,</li></ul>

<pre><code>sudo apt-get install libgtk2.0-dev libgtksourceview2.0-dev intltool<br>
</code></pre>

installs all dependencies.<br>
<ul><li>change to your download folder.<br>
</li><li>extract the source</li></ul>

<pre><code>tar xzvf Ngahuru-0.1.tar.gz<br>
</code></pre>

if you downloaded the tar.gz-archive.<br>
<ul><li>go there</li></ul>

<pre><code>cd Ngahuru<br>
</code></pre>

<ul><li>compile!</li></ul>

<pre><code>./configure &amp;&amp; make<br>
</code></pre>

(requires a basic build environment with gcc and make)<br>
<ul><li>test it with</li></ul>

<pre><code>./src/ngahuru<br>
</code></pre>

from the source tree.<br>
<br>
<ul><li>if you like it:</li></ul>

<pre><code>make install<br>
</code></pre>

as superuser.<br>
<br>
<h1>Wiki</h1>
Did you get your Nature paper finished with it? Did it ruin your system? Leave a comment on the wiki.<br>
<br>
<h1>Artist wanted</h1>
Anyone is invited to join. For instance, artwork would be great. That little symbol that represents the window when you switch with Ctr-Tab, for instance.<br>
<br>
Enjoy!