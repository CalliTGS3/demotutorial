# Anleitung

## Schritt 1

Text 1 

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
})
```

## Schritt 2

Text2

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showIcon(IconNames.Diamond)
})
```

## Schritt 3

Text2

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.showIcon(IconNames.Diamond)
    let CO2 = SCD30.readCO2()
})
```

```package
SCD30=github:callitgs3/pxt-scd30#v0.9.0
```
