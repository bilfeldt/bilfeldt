### Hi there 👋

<!--
**bilfeldt/bilfeldt** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```php
$me = Human::create([
    'first_name => 'Anders',
    'last_name' => 'Bilfeldt',
    'linkedin' => 'https://www.linkedin.com/in/andersbilfeldt/',
    'twitter' => 'https://twitter.com/AndersBilfeldt',
]);

$me->educations()->saveMany([
    new Education([
        'institution' => 'Technical University of Denmark',
        'degree' => 'Masters of Science'
        'subject' => 'Physics and Nanotechnology',
        'graduated' => 2014,
    ]),
    new Education([
        'institution' => 'Technical University of Denmark',
        'degree' => 'Bachelor of Science'
        'subject' => 'Physics and Nanotechnology',
        'graduated' => 2011,
    ]),
]);
```

