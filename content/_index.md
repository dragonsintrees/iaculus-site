+++
template = 'home.html'

[extra]
lang = 'en'

footer = true

name = "I A C U L U S"
# id = "iaculus"
bio = "Empowering dragons in complex trees"
avatar = "/assets/logo-000a.png"
links = [
    { name = "Github", icon = "github", url = "https://github.com/dragonsintrees" },
    { name = "Email", icon = "email", url = "mailto:<team@iaculus.xyz" }
]

recent = false
recent_max = 5
recent_more_text = "more »"
date_format = "%b %-d, %Y"

+++

We're a team of AI Engineering Consultants possessing expertise in implementing Agentic AI within Site Reliability Engineering. Our specialization in Agentic Systems yields measurable success in:

{{ collection(file="foundations.toml") }}

We have particular passion for:

{{ collection(file="specialties.toml") }}

---

{{ collection(file="contact.toml") }}
