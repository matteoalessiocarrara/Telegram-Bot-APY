# Telegram Bot APY #

Semplicissimo wrapper in python per le Telegram Bot API.

## Funzionamento ##

Tutti i metodi delle Telegram Bot API dovrebbero esssere utilizzabili con il metodo Method() della classe Bot; basta specificare il nome del metodo ed eventualmente i parametri, e verrà restituito l'output in json decodificato.
Per i metodi disponibili e relativi return vedere https://core.telegram.org/bots/api

Esempio:

```python
tbot.Method("sendMessage", {'chat_id' : 999, 'text' : "KI 666 TU???"})
```
----

>  Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface.
 
Programmatore\: Matteo Alessio Carrara
Aggiornamenti\: [https://github.com/matteoalessiocarrara] (GitHub)
Email\: sw.matteoac@gmail.com