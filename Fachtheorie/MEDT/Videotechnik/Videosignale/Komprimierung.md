### Verlustfrei

- Wörterbuch-Methode: Zu häufigen Folgen werden nur Tokens gespeichert die in Wörterbuch nachgeschlagen werden
- Entropiekodierung (zb Huffman): vorkommende Werte werden nach Häufigkeit geordnet und Werte die am häufigsten vorkommen werden mit kürzeren Codes (weniger Bit) gespeichert als Werte die weniger häufig vorkommen (mehr Bit). zB: 0 kommt am häufigsten vor -> Code 0, 2 kommt am 2. häufigsten vor -> Code 10
  genauere Erklärung: https://chatgpt.com/c/680e3e54-df64-8012-baf2-aabc62672a42

### Verlustbehaftet

-> Irrelevanzreduktion = Informationen die nicht oder kaum wahrgenommen werden, werden eliminiert

##### Chromasubsampling

Mensch nimmt Farbunterschiede weniger stark wahr als Helligkeitsunterschiede
-> Chrominanz kann mit geringerer Abtastfrequenz digitalisiert werden als Luminanz

bei 4:2:2 würde also jeder Pixel einen eigenen Helligkeits-Wert annehmen aber jeder 2te Pixel die gleichen Farbwerte Cb Cr des vorherigen Pixels

![[Pasted image 20250427165005.png]]

YUV ~= YCbCr, siehe [[YCbCr vs YUV]]