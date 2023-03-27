# Changelog

## 1.0.8
* Replace `offsetHeight`/`offsetWidth` with `getBoundingClientRect` to better support floating size values
* Spread all additional props onto out `HTMLDivElement`

## 1.0.7
* Add peer dependency for `"react"` / `"react-dom"` version 18

## 1.0.6
* Fixed rAF throttling issue caused by new Chrome flag (#39)

## 1.0.5
* Add peer dependency for `"react"` / `"react-dom"` version 17

## 1.0.4
* Do not use `innerHTML` when detecting element resize as this will throw an error if the page uses Trusted Types (#30)