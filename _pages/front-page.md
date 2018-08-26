---
ID: 352
post_title: Front Page
author: Jonathan Green
post_excerpt: ""
layout: page
permalink: http://35.226.97.185/front-page/
published: true
post_date: 2016-03-22 18:41:55
---
<!-- wp:html -->
<script>jQuery(document).ready(function () {
    jQuery(".text").hide();
    jQuery("#r1").click(function () {
        jQuery(".text").show();
    });
    jQuery("#r2").click(function () {
        jQuery(".text").hide();
    });
});
	</script>
<p>Show textboxes
<input type="radio" name="radio1" id="r1" value="Show" onclick="getResults()">Do nothing
    <input type="radio" name="radio1" id="r2" value="Nothing">
</p>Wonderful textboxes:
<div class="text">
    <p>Textbox #1
        <input type="text" name="text1" id="text1" maxlength="30">
    </p>
</div>
<div class="text">
    <p>Textbox #2
        <input type="text" name="text2" id="text2" maxlength="30">
    </p>
</div>
[CP_CALCULATED_FIELDS id="1"]
<!-- /wp:html -->