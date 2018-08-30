---
ID: 558
post_title: Test1
author: user
post_excerpt: ""
layout: page
permalink: https://plantifyourself.tk/test1/
published: true
post_date: 2018-08-30 14:04:53
---
<!-- wp:html -->
<script>
var mysql = require('mysql');

var connection = mysql.createConnection({
host: "localhost",
user: "root",
password: "1234,qwer",
database: "TopVeg"
});
connection.connect();
var query = connection.query("Select FIELD1, FIELD2, FIELD3, FIELD4 from TopVeg", function (err, result){
console.log(result);
});

</script>
<!-- /wp:html -->