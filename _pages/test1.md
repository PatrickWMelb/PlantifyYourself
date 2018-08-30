---
ID: 558
post_title: Test1
author: user
post_excerpt: ""
layout: page
permalink: http://plantifyourself.tk/test1/
published: true
post_date: 2018-08-30 14:04:53
---
<!-- wp:html -->
<script>
var mysql = require('mysql');

var con = mysql.createConnection({
host: "35.232.215.112:3306",
user: "root",
password: "1234,qwer",
database: "VegNutr"
});
con.connect();
var query = con.query("Select FIELD1, FIELD2, FIELD3, FIELD4 from TopVeg;", function (err, result);
console.log(result);
});
});
</script>
<!-- /wp:html -->