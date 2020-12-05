## Как починить поиск для YouTube

Есть несколько способов починить неработающий поиск треков из YouTube. Все они основаны на частных API-ключах Youtube. Ключ это последовательность из 39 символов, при помощи которой твой браузер доказывает серверам YouTube, что ты добропорядочный человек. Ключ как правило начинается с символов `AIzaSy`.

### Способ 1: Закладка в браузере

Создай закладку с одним из следующих адресов. Затем, находясь в руме, нажми на закладку. Это придется повторять при каждом новом входе в руму.

1. `javascript:(function(){gapi.client.setApiKey("AIzaSyAHB2NzxjWTknbepmzCAI2rRk7eI98ksqY"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyD1prSlu74GYzGp5LzriyjCth6tEv-6bXA"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyD--___tekD3NI_-Sj8cAnNyuDKFmdtOkM"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyBem6ljx-MJR2PqEeRJOL8FywRBTYnP3Rs"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyCTeoqqGhpRo5wR7w5TJIp2LMiZsqOPRZg"); alert("Youtube search hotfix loaded.");}());`

### Способ 2: Консоль браузера

Открой консоль браузера нажатием `Shift + Ctrl + I` и вставь в консоль любой из пяти ключей, перечисленных выше, нажми `Enter`. Это тоже придется повторять при каждом новом входе в руму.

#### Способ 3: Через дополнение RCS
RCS может оказаться полезным не только для починки поиска. Об RCS у нас [отдельный гайд](https://an0nwave.github.io/help/rcs.html).

### Как создать новый API-ключ

Все API-ключи, что ты видишь выше, были созданы усилиями добрых анонов. У Гугла есть [гайд (инглиш онли)](https://developers.google.com/youtube/v3/getting-started) для их получения. Ты можешь помочь руме, создав еще один ключ и скинув его в [наш Дискорд](https://discord.gg/VwGKu9V).

[На главную](https://an0nwave.github.io/help/)
