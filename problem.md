This is the ordering flow of my clients: 

Firstly they land on this page
https://www.servizidiamond.it/ordina-i-tuoi-video-ads?lmref-test=CSmWd
this page haven't any javascript code, it has only the reference of the lm.js script on the header
<script src="https://cdn.linkmink.com/lm-js/2.3.1/lm.js"></script>
The first problem is here, checking in the browser developer tools sometimes the cookie appears (rarely) and sometimes it doesn't.

After that when someone clicks on the buy button it will redirect on a stripe hosted checkout (the newly checkout link service)

When the checkout is completed the client is redirected to a success page
https://www.servizidiamond.it/modulo-creazione-video-ads
This is the javascript code of the page
https://github.com/ChrisCoder9000/LinkMinkStuff/blob/main/moduloCreazioneVideoAds

After that, when the module is filled and the send button is pressed, users will be redirected to the following success page which has no javascript code
https://www.servizidiamond.it/ringraziamenti-video-ads

I can't understand which implementation is better and how to implement it.
