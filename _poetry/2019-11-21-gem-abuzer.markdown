---
layout: post
title: How to build a gem?
date: 2019-11-21 23:28:07
---

<blockquote>
Ruby gems are awesome :)<br>
</blockquote>


Finally, I tried to and built a gem.. Here's how..<br> 
Firstly, install bundler by:
<blockquote>
	gem install bundler
</blockquote>>

After its successful installation, generate a new gem, using the following:
<blockquote>
	bundle gem gem_name
</blockquote>

It will create some subdirectories and config files..<br>
Then, you can add some code in /lib/gem_name.rb file. Later, build it:<br>

<blockquote>
	gem build gem_name.gemspec
</blockquote>
After, you may install your gem in local by running the command below:<br>
<blockquote>
	gem install gem_name-0.1.0.gem
</blockquote>
Then, check it:<br>

`irb(main):001:0> require 'abuzer_gem'`<br>
`=> true`

That's all for today :)<br>

stay tuned..




