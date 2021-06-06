---
layout: layouts/post.njk
title: Contact Us
templateClass: tmpl-post
eleventyNavigation:
  key: Contact Us
  order: 3
---

<form name="contact" method="POST" data-netlify="true">
        <fieldset>
            <legend>Contact Us:</legend>
            <label for="uname">User name:</label><br>
            <input type="text" id="uname" name="uname"><br><br>
            <label for="email">Email Address :</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="password">Password :</label><br>
            <input type="password" id="password" name="password"><br><br>
            <label for="telephone">Telephone number :</label><br>
            <input type="tel" id="telephone" name="telephone"><br><br>
            <label for="date">Date of Purchase :</label><br>
            <input type="date" id="date" name="date"><br><br>
            <label for="mails">Mailing list Signup :</label>
            <select id="mails" name="mails" size="2" multiple>
                <option value="News">News</option>
                <option value="Offers">Offers</option></select>
            <p>Star Signs :</p>
            <label for="Aries">Aries</label>
            <input type="radio" id="Aries" name="stars" value="Aries">
            <label for="Libra">Libra</label>
            <input type="radio" id="Libra" name="stars" value="Libra">
            <label for="other">Other</label>
            <input type="radio" id="other" name="stars" value="other"><br><br>
            <button type="submit">Send</button>
        </fieldset>
</form>