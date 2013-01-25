---
layout: post
title: {{ site.title }} - Signup
tagline: Signup to become a member of our community.
---
{% include JB/setup %}

# {{ site.title }} - Signup
We are looking for people invested in the ASD community who are interested in using our alpha products and giving us feedback.

We will not share your email with anyone.

<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>

<div class="form-horizontal">

  <script type="text/javascript">
  var submitted=false;
  </script>
  <iframe id="hidden_iframe" name="hidden_iframe" onload="if (submitted) {window.location='/signupthankyou.html';}" style="display: none;"> </iframe>
  
  <form action="https://docs.google.com/spreadsheet/formResponse?formkey=dHplV2FBWTJ1OS1Tc3ZMYmR2eFZNUkE6MQ&amp;theme=0AX42CRMsmRFbUy1iOGYwN2U2Mi1hNWU0LTRlNjEtYWMyOC1lZmU4ODg1ODc1ODI&amp;ifq" method="POST" id="ss-form" onsubmit="submitted=true;" target="hidden_iframe">
    <div class="control-group">
      <label class="control-label" for="entry_0">Email</label>
      <div class="controls">
        <input type="text" name="entry.0.single" id="entry_0" placeholder="Email"></input>
      </div>
    </div>
    <div class="control-group">
      <label class="control-label" for="entry_1">Comments</label>
      <div class="controls">
        <textarea name="entry.1.single" rows="8" cols="75" id="entry_1"> </textarea>
      </div>
    </div>
    <input type="hidden" name="pageNumber" value="0"></input>
    <input type="hidden" name="backupCache" value=""></input>

    <div class="control-group">
      <div class="controls">
        <button class="btn btn-large btn-success" type="submit" name="submit" value="Submit">Sign Up For Alpha</button>
      </div>
    </div>
  </form>
</div>
