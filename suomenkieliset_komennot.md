# Turtle Roy suomeksi

[Turtle Royn](https://github.com/raimohanska/turtle-roy/blob/master/README.md) komennot käännettynä suomeksi. Voit ladata komennot suoraan editoriin täältä: [http://turtle-roy.herokuapp.com/?turtle=XDPNCMH7VQ](http://turtle-roy.herokuapp.com/?turtle=XDPNCMH7VQ)

# Turtle Roy -komennot

    et 100                      | siirry 100 pikseliä eteenpäin
    v 45                        | käänny vasemmalle 45 astetta
    o 90                        | käänny oikealle 90 astetta
    ky                          | kynä ylös, ei piirrä liikkuessa
    ka                          | kynä alas, piirtää taas
    ty                          | tyhjentää paperin ja siirtää kilpikonnan keskelle
    koti                        | siirtää kilpikonnan keskelle
    sano "omg"                  | puhu ääneen
    kirjoita "x"                | kirjoita konsoliin
    soita c                     | soita C-sävel
    soita c 500                 | soita C-säveltä 500 millisekuntia
    soita c*2                   | soita C2-sävel (taajuus = C * 2)
    sarja [et 100, o 90]        | 100 pikseliä eteenpäin, sitten oikea käännös
    s [et 100, o 90]            | sama kuin yllä
    toista 4 (sano "hello")     | sanoo "hello" 5 kertaa
    t 4 (say "hello")           | sama kuin yllä
    y [soita c, soita e]        | soittaa C- ja E-sävelet yhtäaikaa
    väri "red"                  | vaihda kynän väri (red, rgb(255,0,0), #FF0000)
    teksti "HELLO"              | kirjoita "HELLO"-teksti kilpikonnan viereen

Lisäksi voit käyttää kaikkia Turtle Royn [alkuperäisiä komentoja](https://github.com/raimohanska/turtle-roy/blob/master/README.md#turtle-roy-api) sekä [Roy](http://roy.brianmckenna.org/)-ohjelmointikieltä.

# Esimerkkejä

Perusliikkeitä

    et 100
    v 90
    o 45

Neliö

    let neliö = toista 4 (sarja [et 50, v 90])
    neliö

Kukka

    let kukka = toista 36 (o 10, neliö)
    kukka


