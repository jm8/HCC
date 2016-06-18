<h2>Heritage CC Website</h2>
Before cloning, you'll need to install <a href=http://jekyllrb.com>Jekyll</a>.
<pre>  gem install jekyll</pre>
Then clone the repository and CD inside. Now run,
<pre>  jekyll serve --watch</pre>
You should be able to go to <i>localhost:4000</i> and see the clone of you're website. Edit and commit and your changes will be live!
<br><br>
<h6>Adding Posts</h6>
In the _posts folder, add a file with format <pre>YYYY-MM-DD-titlelowercasenospaces.markdown</pre> Inside it add these lines:
<pre>
layout: post
title:  "Title in Title Case with Spaces"
date:   YYYY-MM-DD HH:MM:SS -0400
---
</pre>
After that, write the post.
<h6>Adding Other Pages</h6>
To add another page, create a file named <pre>titlelowercasenospaces.html</pre> Inside it put these lines:<pre>---
layout: default
---</pre>
Then inside _config.yml add, in the navigation section, <pre>
\- text: Title in Title Case with Spaces
  url: /titlelowercasenospaces.html
</pre>
