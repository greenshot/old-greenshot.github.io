---
layout: page
status: publish
published: true
title: Update Greenshot
author:
  display_name: greenshot
  login: admin
  email: greenshot-developers@lists.sourceforge.net
  url: http://getgreenshot.org/
author_login: admin
author_email: greenshot-developers@lists.sourceforge.net
author_url: http://getgreenshot.org/
wordpress_id: 353
wordpress_url: http://getgreenshot.org/
date: !binary |-
  MjAxMi0wNC0wMiAyMjo1NDozOSArMDIwMA==
date_gmt: !binary |-
  MjAxMi0wNC0wMiAyMDo1NDozOSArMDIwMA==
categories: []
tags: []
comments: []
---
<p>
<?php<br />
$latest_version = '0.8.0-0627';<br />
$check_version = $_GET['version'];</p>
<p>if(isset($check_version)) {<br />
	$cmp = version_compare($check_version, $latest_version);<br />
	if($cmp >= 0) echo "You are already using the latest version of Greenshot (".$latest_version."). If needed, you can download the installer again by clicking the link below.";<br />
	else echo "Your Greenshot installation is out of date, please download and install the latest version (".$latest_version.") by clicking the link below.";<br />
} else {<br />
	echo "The latest Greenshot version is ".$latest_version." You can download it below.";<br />
}<br />
?></p>
<p><a class="button" href="/current/" title="Download the latest stable version of Greenshot" rel="nofollow" target="_blank">Download</a></p>
