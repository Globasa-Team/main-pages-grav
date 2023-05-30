---
title: 'Test Page'
form:
    name: contact-form
    fields:
        my_choice:
            type: radio
            label: Choice
            default: markdown
            options:
                markdown: Markdown
                twig: Twig
        name:
            label: Name
            placeholder: 'Enter your name'
            autofocus: true
            autocomplete: true
            type: text
            validate:
                required: true
        email:
            label: Email
            placeholder: 'Enter your email address'
            type: email
            validate:
                required: true
    buttons:
        submit:
            type: submit
            value: Submit
        reset:
            type: reset
            value: Reset
    process:
        email:
            from: '{{ config.plugins.email.from }}'
            to:
                - '{{ config.plugins.email.to }}'
                - '{{ form.value.email }}'
            subject: '[Feedback] {{ form.value.name|e }}'
            body: '{% include ''forms/data.html.twig'' %}'
        save:
            fileprefix: feedback-
            dateformat: Ymd-His-u
            extension: txt
            body: '{% include ''forms/data.txt.twig'' %}'
        message: 'Thank you for your feedback!'
        display: thankyou
cache_enable: false
visible: false
---

	
* Fund out-of-pocket expenses and projects via:
 	* [Patreon](https://www.patreon.com/Globasa)
 	* [Liberapay](https://liberapay.com/Globasa)
 	* [Paypal](https://www.paypal.com/paypalme/globayen)

<span class="fa fa-patreon"></span> <i class="fa fa-patreon"></i>


<span class="fa fa-mail"></span> <i class="fa fa-mail"></i> test