---
title: "Contatti"
date: 2022-05-24T17:14:41+02:00
draft: false
---

Puoi contattarmi attraverso questi canali:
------------------------------------------

* [Chiamandomi sul mio numero](tel:+393317438243)
* Scrivendomi su [WhatsApp](https://wa.me/393317438243) o [Telegram](https://t.me/nickciava98)
* Attraverso [Facebook](https://www.facebook.com/nciavarellait), [Instagram](https://www.instagram.com/niccolo.ciavarella), [Twitter](https://www.twitter.com/nickciava98) o [LinkedIn](https://www.linkedin.com/in/nickciava98)
* [Inviandomi una mail](mailto:niccolo.ciavarella@email.com)

[Puoi anche venirmi a trovare, previo appuntamento, a casa mia!](https://goo.gl/maps/VtGP3vzKpfs1mSwZ7)

{{< netlify-form name="contact" >}}
  {{< form-input id="firstname" type="text" placeholder="John" label="First Name:" required="true" >}}
  {{< form-input id="lastname" type="text" placeholder="Doe" label="Last Name:" >}}
  {{< form-input id="reply_email" type="email" placeholder="john.doe@email.com" label="Reply-To Email:" required="true" >}}
  {{< mult-input label="Gender:" name="gender" required="true" add_other="true" type="select" >}}
    {{< form-option label="Male" value="male" >}}
    {{< form-option label="Female" value="female" >}}
  {{< /mult-input >}}
  {{< form-input type="text" id="submit_reason" required="true" label="Reason for contacting:" placeholder="Problem with site" >}}
  {{< form-input id="contact_description" type="textarea" label="Explain:" required="true" >}}
{{< /netlify-form >}}
