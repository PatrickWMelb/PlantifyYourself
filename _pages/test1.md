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
var mysql = require('mysql');

var con = mysql.createConnection({
host: "35.232.215.112",
user: "root",
password: "1234,qwer",
database: "VegNutr"
});
con.connect();
var query = con.query("SELECT * FROM VegNutr", function (err, result);
console.log(result);
});
});