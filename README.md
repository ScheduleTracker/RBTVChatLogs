# RBTV Chat logs

**Twitch chat wird nicht geloggt! Dafür auf overrustlelogs schauen!**

Das logging basiert auf der [YouTube Live Chat API](https://developers.google.com/youtube/v3/live/docs/liveChatMessages). Die Daten werden in einem Format ähnlich dem Logging-Format von ZNC konvertiert und dann als Textdatei gespeichert.

Ein automatisches Update des Repository wird ein mal pro Stunde ausgeführt.

Zukünfigt werden ggf. logs für einzelne User (ähnlich Overrustellogs) möglich sein.

## Updates
### 21.09.2016:
* Vorm Username sind nun Symbole ähnlich IRC zu sehen:
    * @, % und + für Owner, Moderator und Sponsor (Subscriber)
	* Es gibt immer nur ein Symbol, hierbei gilt Owner > Mod > Sub
    * Diese Änderung dient dazu die echten Moderatoren mit solche die den selben Nick habe im Log auseinanderzuhalten (YouTube verlangt keine einzigartigen Nicknames)
    * Diese Änderung kann nicht Rückwirkend angewendet werden
