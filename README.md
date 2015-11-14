# Mokamentary Icon Set
A combination of the "Moka" and the elementary OS icon sets

I love almost everything about the elementary OS look and feel, except for the icon set used for applications.
It's not bad, but I prefer Moka. But then again, I don't like the other icons of Moka (folders, actions, etc).
So I mashed them together. It's not pretty - well the result is, but not the process of getting there - as it
involves a lot of symbolic linking. But if you don't mind, feel free to give this icon theme a spin.

## Prerequisites

* The original elementary OS theme
* The [original Moka](http://samuelhewitt.com/moka) theme or [my fork](http://github.com/danielroehrig/moka-icon-theme) (you know, for them extra jetbrains icons)

## Installation

    chmod +x Install
    ./install

Use whatever you use to set the icon theme. I am lazy and use elementary tweaks which
is deprecated, so I won't link to that. But this also works:

    gsettings set org.gnome.desktop.interface icon-theme 'Mokamentary'
