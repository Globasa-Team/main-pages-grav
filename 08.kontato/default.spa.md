---
title: Contacto
---

<h1>Contáctese con el equipo de Globasa</h1>
<form action="https://formspree.io/maylyonr" method="POST" class="w3-container" >
    <input type="hidden" name="Source" value="Main Globasa Website" />
    <input type="hidden" name="subject" value="Feedback: {{ user_subject }} {{topic}}" />
    
    <h3>Tema</h3>
    <input type="radio" name="topic" id="topic-content" value="Website content error">
    <label for="topic-content">Error de contenido en la página web</label><br/>
    <input type="radio" name="topic" id="topic-tech" value="Website tech error">
    <label for="topic-tech">Error de tecnología en la página web</label><br/>
    <input type="radio" name="topic" id="topic-other" value="Other / not sure" checked>
    <label for="topic-other">Otro</label><br/>
    
    <label><h3>Su dirección de correo electrónico (opcional)</h3></label>
    <input type="text" name="_replyto" class="" >

    <label><h3>Asunto</h3></label>
    <input type="text" name="user_subject" class="" >
    
    <label><h3>Su mensaje:</h3>
        <textarea name="message" class="" style="width: 100%; height: 6em;"></textarea>
    </label>

    <div class="feedbackSubmit">
    <button type="submit" class="">Enviar</button>
    </div>
</form>