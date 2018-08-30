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
<script data-main="scripts/main.js" src="scripts/require.js">
    var mysql = require("mysql");

    var connection = mysql.createConnection({
      host: "35.232.215.112:3306",
      user: "root",
      password: "1234,qwer",
      database: "bitnami_wordpress"
    });
    connection.connect();
    var query = connection.query("Select FIELD1, FIELD2, FIELD3, FIELD4 from TopVeg", function (err, result) {
      console.log(result);

    });
</script>
<!-- /wp:html -->