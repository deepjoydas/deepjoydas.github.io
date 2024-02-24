---
layout: entitled
title: contact
---

<form action="https://formspree.io/f/xwkypvwj"
    method="POST">
  <div class="row">
    <div class="col-6">
      <input class="form-control" type="text" id="name" name="name" placeholder="Your Name" required>
    </div>
    <div class="col-6">
      <input class="form-control" type="email" id="email" name="_replyto" placeholder="Your E-mail" required>
    </div>
  </div>
  <div class="form-group my-2">
    <textarea class="form-control" style="resize: none;" id="message" name="message" rows="4"  placeholder="Your Message" required></textarea>
  </div>
  <button class="btn btn-primary mt-2" type="submit">Send</button>
</form>