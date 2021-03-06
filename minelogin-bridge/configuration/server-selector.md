---
description: Allows you to configure the server election gui by the player
---

# 馃枿 Server selector

> ![馃嚭馃嚫](https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg) Here you can configure the server election gui. Whether it should be enabled, how many slots it should have, what should be displayed, where should it redirect to, what should be the background, what attributes should the displayed item or the slot it should appear on have.\
> \
> ![馃嚨馃嚤](https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg) W tym miejscu mo偶esz skonfigurowa膰 gui wybor贸w serwer贸w. Czy ma by膰 ono w艂膮czone, ila ma mie膰 slot贸w, co ma si臋 wy艣wietla膰, gdzie ma przekierowywa膰, z czego b臋dzie wype艂nione t艂o, jakie atrybuty b臋dzie posiada艂 wy艣wietlany przedmiot lub slot na kt贸rym b臋dzie si臋 pojawia艂.

```yaml
#PL: Konfiguracja GUI wyboru serwer贸w.
#EN: Configuration GUI server selector.
server-selector:
  #PL: Czy przedmiot wyboru serwera ma by膰 w艂膮czony?
  #EN: Is the server selector item to be enabled?
  enabled: true
  #PL: Miejsce na pasku szybkiego dostepu do pojawiania przedmiotu wyboru serwera.
  #EN: A place in the HotBar for the server selector item to appear.
  selector-slot: 4
  #PL: Przedmiot wyboru serwera.
  #EN: Server selector item.
  selector-item:
    material: COMPASS
    item-meta:
      display-name: '&cSelect server (RMB)'
      enchantments:
        LURE: 1
      item-flags:
      - HIDE_ENCHANTS
  #PL: Konfiguracja GUI wyboru serwera.
  #EN: Configuration server selector GUI.
  gui:
    #PL: Nazwa gui.
    #EN: Gui title.
    title: <green>Select server
    #PL: Ilo艣膰 linijek gui.
    #EN: Gui rows.
    rows: 5
    #PL: Jak wype艂niane ma by膰 gui.
    #EN: How the gui is to be populated.
    filler-type: FULL
    #PL: Jakim przedmiotem ma by膰 wype艂nione gui.
    #EN: What object the gui is to be filled with.
    filler-item:
      material: BLACK_STAINED_GLASS_PANE
    #PL: Przedmioty w gui.
    #EN: Gui items.
    items:
      22:
        item:
          material: GRASS
          item-meta:
            display-name: '&aServer survival'
            lore:
            - '&7This is survival server!'
            - '&6Click to select this server'
        changes-server: true
        server: survival
```

