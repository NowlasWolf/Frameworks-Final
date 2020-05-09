---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Contact us
menutag: CONTACT
menupos: 6
---

<section class="row justify-content-center contenthead">
    <article class="col-4">
        <h1>{{page.title}}</h1>
    </article>
</section>

<section class="row justify-content-center slicenoborder">
    <article class="col-6 history">
        <h2>Contact</h2>
        <p>Interested in sharing a story or memory of the theater? Please submit it.<br><br>
            Have questions? We can answer them.<br><br>
            Want to get involved? Let us know!<br><br>
            We look forward to hearing from you.<br><br>
            libertytheaterlewiston@gmail.com
        </p>
    </article>
    <article class="col-6">
        <form action="https://formspree.io/mwknynjl" method="POST">
            <div class="form-group">
                <label for="name">Subject</label>
                <input type="text" class="form-control" id="name" name="_name" placeholder="Enter First and Last Name">
            </div>
            <div class="form-group">
                <label for="email">Email address</label>
                <input type="email" class="form-control" id="email" name="_replyto" placeholder="Enter Email">
            </div>
            <div class="form-group">
                <label for="subject">Subject</label>
                <input type="text" class="form-control" id="subject" name="_subject" placeholder="Enter Subject">
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea type="text" class="form-control" id="message" name="_content" rows="4"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
        </form>
    </article>
</section>