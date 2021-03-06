---
layout: faq
status: publish
published: true
title: How can I paste screenshots into Skype?
author:
  display_name: greenshot
  login: admin
  email: greenshot-developers@lists.sourceforge.net
  url: http://getgreenshot.org/
author_login: admin
author_email: greenshot-developers@lists.sourceforge.net
author_url: http://getgreenshot.org/
wordpress_id: 1009
wordpress_url: http://getgreenshot.org/?post_type=faq&#038;p=1009
date: !binary |-
  MjAxMy0xMC0xMCAyMTo1NDo1MSArMDIwMA==
date_gmt: !binary |-
  MjAxMy0xMC0xMCAxOTo1NDo1MSArMDIwMA==
categories: []
tags: []
comments: []
---
<p>If you need to copy&paste into Skype, have a look into the settings dialog, Expert tab. After confirming that you are knowing what you are doing you can configure the list of formats that are stored into the clipboards. Skype requires Windows Bitmap (at the bottom of the list).</p>
<p>Unfortunately, supporting copy and paste to different programs via the Windows clipboard is a tedious task. Different programs expect different formats from the clipboard. When adding more formats to support more programs, it usually breaks support for other programs, so there is no perfect configuration which works for everyone.</p>
<p>Anyways, we generally advice to prefer other ways than the clipboard to send images to other programs, because clipboard usage most often results in an image that is a lot larger in file size than the original.</p>
<p>Skype users might want to have a look at our blog post explaining <a href="/2013/02/17/how-to-send-an-image-to-skype-using-command-line-arguments/">how to directly send files to Skype</a> using the External Command plugin, once set up this requires even less interaction than using the clipboard.</p>
