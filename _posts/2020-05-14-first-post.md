---
layout: post
title: First-post
tags: [Test, Markdown]
---


Search should be working even for complicated escape symbols
```
sed -i 's/\"hostname\"\:.*$/\"hostname\"\: \"'$IPADDR'\"\,/g' open-falcon/agent/config/cfg.json
```

## Some tech stuff blog

Because you might put code in your blog post and you want to make sure 
it will look good in here.
And that the search function is working!

### Java

java example

```java
public class Demo {
  private static final String CONSTANT = "String";
  private Object o;
  /**
   * Creates a new demo.
   * @param o The object to demonstrate.
   */
  public Demo(Object o) {
    this.o = o;
    String s = CONSTANT + "Other";
    int i = 123;
  }
  public static void main(String[] args) {
    Demo demo = new Demo();
  }
}
```

### HTML

html example

```html
HTML
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2//EN">
<!-- Sample comment -->
<HTML>
<head>
<title>IntelliJ IDEA</title>
</head>
<body>
  <h1>IntelliJ IDEA</h1>
  <p><br><b><IMG border=0 height=12 src="images/hg.gif" width=18 >
    Hello&nbsp;World! &#x00B7; &Alpha; </b><br><br>
</body>
</html>

```

### Ruby

ruby example

```ruby
require "test"
CONSTANT = 777

# Sample comment

class Module::Class
  include Testcase

  render :action => 'foo'
  def foo(parameter)
    @parameter = parameter
  end

  local_var = eval <<-"FOO";\
  printIndex "Hello world!"
  And now this is heredoc!
  printIndex "Hello world again!"
  FOO
  foo("#{$GLOBAL_TIME >> $`} is \Z sample \"string\"" * 777);
  if ($1 =~ /sample regular expression/ni) then
  begin
    puts %W(sample words), CONSTANT, :fooo;
    do_something :action => "action"
  end
  expect{counter[0]}.to_be eq 1
  1.upto(@@n) do |index| printIndex 'Hello' + index end
  \\\\\\\\\
  end
end
```

### YAML

You can also render some yaml, like this `_config.yml`:

```yml

# Welcome to Jekyll!
#
# This config file is meant for settings that affect your whole blog, values
# which you are expected to set up once and rarely edit after that. If you find
# yourself editing this file very often, consider using Jekyll's data files
# feature for the data you need to update frequently.
#
# This file, "_config.yml" is *NOT* reloaded automatically when you use
# 'bundle exec jekyll serve'. If you change this file, please restart the server process.

# Site settings
# These are used to personalize your new site. If you look in the HTML files,
# you will see them accessed via {{ site.title }}, {{ site.email }}, and so on.
# You can create any custom variable you would like, and they will be accessible
# in the templates via {{ site.myvariable }}.

# SITE CONFIGURATION
baseurl: "/Type-on-Strap"
url: "https://sylhare.github.io"

# THEME-SPECIFIC CONFIGURATION
title: Type on Strap                                    # site's title
description: "A website with blog posts and pages"      # used by search engines
avatar: assets/img/triangle.png                         # Empty for no avatar in navbar
favicon: assets/favicon.ico                             # Icon displayed in the tab

remote_theme: sylhare/Type-on-Strap                     # If using as a remote_theme in github
```
