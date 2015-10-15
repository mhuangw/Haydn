#Haydn in Alda

This is a project written in Alda, a music programming language. I'm translating the first movement of Haydn's Sonata No. 60 in C Major into code. 

To run the code, you'll need the Clojure build tool <i>Boot</i>. If you're runing Mac OS X with Homebrew installed, you can install Boot by running the following:

<code>brew install boot-clj</code>
  
You'll also need the <i>alda execution file</i>, which you can install by copying and pasting the following:

<code>curl https://raw.githubusercontent.com/alda-lang/alda/master/bin/alda -o /usr/local/bin/alda && chmod +x /usr/local/bin/alda</code>

To play the music, navigate to the directory where the code is located and type the following:

<code>alda play --file haydn.alda</code>

Visit <a href="http://daveyarwood.github.io/alda/2015/09/05/alda-a-manifesto-and-gentle-introduction/">here</a> for more information on Alda.
