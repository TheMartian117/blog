<link rel = "icon" href = "https://themartian117.github.io/favico.ico" file type = "image/x-icon">
<section class="content">
        <div class="post-container">
  <a class="post-link" href="/blog/teaching/jekyll">
    <h2 class="post-title">How To Make A Jekyll Website: Made Easy</h2>
  </a>
  <div class="post-meta">
    <ul class="post-categories"><li>teaching</li></ul>
    <div class="post-date"><i class="icon-calendar"></i>April 17, 2020</div>
  </div>
  <div class="post">
  <p>I've found that using Jekyll on GitHub with unsupported themes can be pretty intimidating, since some of it isn't very well documented, and they skim through instructions that beginners might need. 
  If you don't know what Jekyll is already, it's basically a static site generator that can be used with Github pages to give your website some cool themes. 
  </p>
  <p> Now, if you already have a Github Pages, but want to have a theme on a seperate part of the website,
  you can create a new repository called "blog" (or whatever you want), and initialize it with a <code class="language-plaintext highlighter-rouge">README.md</code>. This will essentially be 
  repository will hold the code for all of <code class="language-plaintext highlighter-rouge">https://[your-username].github.io</code>. </p>
  
  <p>We want to make the repository we just created a GithubPage as well, so to do that, go to the settings of the repository, scroll down
  to Github Pages, and you will see "source". It should say "None", now change it so that it says "master branch for Github Pages".
  </p>
  
  <p> Now, you can go to the <a href = "https://jekyllthemes.org">Jekyll Themes</a> website, and find which theme you like. I'm using 
  "plainwhite", and I encourage you do the same as well until you know how to use jekyll fully, and then you cam switch themes. 
  To use the theme on your website, you have to create a config file of the name <code class="language-plaintext highlighter-rouge">_config.yml</code>.
  In the plainwhite Github, you will see that to install the theme you have to put <code class="language-plaintext highlighter-rouge">remote_theme: thelehhman/plainwhite-jekyll</code>.
  After this, you want to add more details into the config file. I personally added: </p>
  
<div class="language-bash highlighter-rouge"><div class="highlight"><pre class="highlight"><code>  
  <span class = "k">plainwhite</span>:
    <span class = "k">name</span>: Ani Bharadwaj
    <span class = "k">tagline</span>: Developer
    <span class = "k">date_format</span>: "%b %-d, %Y"
    <span class = "k">social_links</span>:
      github: themartian117
</code></pre></div></div>

<p>You can add more stuff if you want, but this should be good enough to get you started. <b>One thing that is very important to note about Jekyll is that all your code should go on markdown files (.md)</b> Your <code class="language-plaintext highlighter-rouge">README.md</code> is a markdown file, and that is where your base page is. The code for<code class="language-plaintext highlighter-rouge">https://[your-username].github.io</code> should go on <code class="language-plaintext highlighter-rouge">README.md</code>. </p>
 
<p> Whever you want to create a new page on your site, you have to create another <code class="language-plaintext highlighter-rouge">.md</code> file, <b>not an html one, or else it wont work!</b>Also, note that you can (and obviously should) use HTML on markdown files without worry.</p>

<p>I hope that in this post I helped you get a Jekyll site on Github Pages up and running. </p>
  
