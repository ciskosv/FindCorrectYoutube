# FindCorrectYoutubeID
Script en Python para encontrar el código ID correcto de un enlace de Youtube, cuando tenemos el código pero todas las letras son mayúsculas.

Basado en el script original de tonY1883 / ValidateYoutubeVideoId.js (https://gist.github.com/tonY1883/a3b85925081688de569b779b4657439b) y código de PotatoKingTheVII.

El script saca una lista de todas las posibles variaciones de mayúsculas y minúsculas, con esa lista revisa el thumbnail por default para detectar si el ID es el correcto o no. 
El string con el ID que tengamos en MAYUSCULAS debe detallarse en st = 'XXXXX'
