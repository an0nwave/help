## Как починить поиск для YouTube

Есть несколько способов починить неработающий поиск треков из YouTube. Все они основаны на частных API-ключах Youtube. Ключ это последовательность из 39 символов, при помощи которой твой браузер доказывает серверам YouTube, что ты добропорядочный человек. Ключ как правило начинается с символов `AIzaSy`.

Прежде чем узнать о способах фикса, посмотри сюда. Чтобы сильно не нагружать API-ключ и чтобы он дольше проработал, выполняй поиск youtube-треков следующим образом:
1. на самом сайте youtube.com ищи музыку, которую планируешь добавить в плейлист, открой там же найденный и выбранный тобой трек;
1. скопируй ссылку выбранного тобой на youtube трека;
1. вставь эту ссылку в поле поиска уже в руме на плаге, нажми Enter;
1. среди тех треков, которые отобразит плаг после нажатия тобой Enter, выбери нужный и добавь в свой плейлист.

### Способ 1: Закладка в браузере

Создай закладку с одним из следующих адресов. Затем, находясь в руме, нажми на закладку. Это придется повторять при каждом новом входе в руму.

1. `javascript:(function(){gapi.client.setApiKey("AIzaSyAHB2NzxjWTknbepmzCAI2rRk7eI98ksqY"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyD1prSlu74GYzGp5LzriyjCth6tEv-6bXA"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyD--___tekD3NI_-Sj8cAnNyuDKFmdtOkM"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyBem6ljx-MJR2PqEeRJOL8FywRBTYnP3Rs"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyCTeoqqGhpRo5wR7w5TJIp2LMiZsqOPRZg"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyCF_lhF-23CpBzmF1c-35kCRlfqkMVmVyA"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyABkYKliRh3Gww3fglwaA2e7MQQqlmSds8"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyD8BjYmTkgesViFVSNLBSUr0CklMtcbEvA"); alert("Youtube search hotfix loaded.");}());`
1. `javascript:(function(){gapi.client.setApiKey("AIzaSyDjOCS9B-jIYJnq9OLT0e2gjIuAodTREjQ"); alert("Youtube search hotfix loaded.");}());`

### Способ 2: Консоль браузера

Открой консоль браузера нажатием `Shift + Ctrl + I` и вставь в консоль любую из перечисленных ниже строк, нажми `Enter`. Это тоже придется повторять при каждом новом входе в руму.

1. `gapi.client.setApiKey("AIzaSyAHB2NzxjWTknbepmzCAI2rRk7eI98ksqY")`
1. `gapi.client.setApiKey("AIzaSyD1prSlu74GYzGp5LzriyjCth6tEv-6bXA")`
1. `gapi.client.setApiKey('AIzaSyD--___tekD3NI_-Sj8cAnNyuDKFmdtOkM')`
1. `gapi.client.setApiKey('AIzaSyBem6ljx-MJR2PqEeRJOL8FywRBTYnP3Rs')`
1. `gapi.client.setApiKey('AIzaSyCTeoqqGhpRo5wR7w5TJIp2LMiZsqOPRZg')`
1. `gapi.client.setApiKey('AIzaSyCF_lhF-23CpBzmF1c-35kCRlfqkMVmVyA')`
1. `gapi.client.setApiKey('AIzaSyABkYKliRh3Gww3fglwaA2e7MQQqlmSds8')`
1. `gapi.client.setApiKey('AIzaSyD8BjYmTkgesViFVSNLBSUr0CklMtcbEvA')`
1. `gapi.client.setApiKey('AIzaSyDjOCS9B-jIYJnq9OLT0e2gjIuAodTREjQ')`

### Способ 3: Через дополнение RCS
RCS может оказаться полезным не только для починки поиска. Об RCS у нас [отдельный гайд](https://an0nwave.github.io/help/rcs.html).

### Как создать новый API-ключ

Все API-ключи, что ты видишь выше, были созданы усилиями добрых анонов. У Гугла есть [гайд (инглиш онли)](https://developers.google.com/youtube/v3/getting-started) для их получения. Ты можешь помочь руме, создав еще один ключ и скинув его в [наш Дискорд](https://discord.gg/VwGKu9V).

[На главную](https://an0nwave.github.io/help/)
