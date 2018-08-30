---
ID: 354
post_title: Level 1
author: Jonathan Green
post_excerpt: ""
layout: page
permalink: http://plantifyourself.tk/level-1/
published: true
post_date: 2016-03-22 18:42:19
---
&lt;?php

$link = mysql_connect('35.232.215.112', 'root', '1234,qwer');
if (!$link) {
die('Not connected : ' . mysql_error());
}

// make foo the current db
$db_selected = mysql_select_db('VegNutr', $link);
if (!$db_selected) {
die ('Can\'t use foo : ' . mysql_error());
}
?&gt;