---
title: Kontakti
---

<h1>Kontaktu la Teamon de Globaso</h1>

<form action="https://formspree.io/maylyonr" method="POST" class="w3-container" >
    <input type="hidden" name="subject" value="Feedback: {{ user_subject }} {{ topic }}" />
    <input type="hidden" name="Source" value="Main Globasa Website" />
    
    <h3>Kategorio</h3>
    <input type="radio" name="topic" id="topic-content" value="Enhava eraro de la retejo">
    <label for="topic-content">Enhava eraro de la retejo</label><br/>
    <input type="radio" name="topic" id="topic-tech" value="Teknika eraro de la retejo">
    <label for="topic-tech">Teknika eraro de la retejo</label><br/>
    <input type="radio" name="topic" id="topic-other" value="Alia / ne certa" checked>
    <label for="topic-other">Alia / ne certa</label><br/>
    
    <label><h3>Via retpoŝto (nedeviga)</h3></label>
    <input type="text" name="_replyto" class="" >
    <label><h3>Temo</h3></label>
    <input type="text" name="user_subject" class="" >
    
    <label><h3>Via mesaĝo:</h3>
        <textarea name="message" class="" style="width: 100%; height: 6em;"></textarea>
    </label>
    <div class="feedbackSubmit">
    <button type="submit" class="">Sendu</button>
    </div>
</form>
