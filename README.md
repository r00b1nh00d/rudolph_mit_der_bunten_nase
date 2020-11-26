# Rudolph mit der bunten Nase
## ~avatar avatar @unplugged
![Rudolph](https://github.com/r00b1nh00d/rudolph_mit_der_bunten_nase/blob/master/Rudolph2.gif?=true) <br>

## ~ @unplugged
Um deinen eigenen Rudolph zu zeichnen kannst du gerne diese Skizze nutzen. <br>
![Skizze](?=true)


## Programmierung
Um Rudolph's Nase in verschiedenen Farben leuchten zu lassen, kannst du in eine ``||basic:dauerhaft||`` - Schleife einfach mehrere Blöcke zum ``||basic:setzen der RGB-Led||`` und einer anschließenden ``||basic:Pause||`` hineinsetzen. <br>
Um später auch zufällige Farben anzeigen zu lassen kannst du diese beispielsweise mit ``||math:Zufalls||`` Zahlen erstellen lassen. 
```blocks

basic.forever(function () {
    basic.setLedColor(0xffff00)
    basic.pause(100)
    basic.setLedColor(0xff0000)
    basic.pause(100)
    basic.setLedColor(0xb09eff)
    basic.pause(100)
    basic.setLedColor(0x00ffff)
    basic.pause(100)
    basic.setLedColor(0xff8000)
    basic.pause(100)
    basic.setLedColor(0xff0080)
    basic.pause(100)
    basic.setLedColor(0x00ff00)
    basic.pause(100)
})
```
