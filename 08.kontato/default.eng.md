---
title: Contact
---

<h1>Contact the Globasa Team</h1>
<form action="https://formspree.io/maylyonr" method="POST" class="w3-container" >
    <input type="hidden" name="Source" value="Main Globasa Website" />
    <input type="hidden" name="subject" value="Feedback: {{ user_subject }} {{topic}}" />
    
    <h3>Topic</h3>
    <input type="radio" name="topic" id="topic-content" value="Website content error">
    <label for="topic-content">Website content error</label><br/>
    <input type="radio" name="topic" id="topic-tech" value="Website tech error">
    <label for="topic-tech">Website tech error</label><br/>
    <input type="radio" name="topic" id="topic-other" value="Other / not sure" checked>
    <label for="topic-other">Other / not sure</label><br/>
    
    <label><h3>Your email (optional)</h3></label>
    <input type="text" name="_replyto" class="" >

    <label><h3>Subject</h3></label>
    <input type="text" name="user_subject" class="" >
    
    <label><h3>Your message:</h3>
        <textarea name="message" class="" style="width: 100%; height: 6em;"></textarea>
    </label>

    <div class="feedbackSubmit">
    <button type="submit" class="">Send</button>
    </div>
</form>