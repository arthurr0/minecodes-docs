---
description: Allows you to configure the server election gui by the player
---

# 🖨 Server selector

> <img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> Here you can configure the server election gui. Whether it should be enabled, how many slots it should have, what should be displayed, where should it redirect to, what should be the background, what attributes should the displayed item or the slot it should appear on have.\
> \
> <img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> W tym miejscu możesz skonfigurować gui wyborów serwerów. Czy ma być ono włączone, ila ma mieć slotów, co ma się wyświetlać, gdzie ma przekierowywać, z czego będzie wypełnione tło, jakie atrybuty będzie posiadał wyświetlany przedmiot lub slot na którym będzie się pojawiał.

```yaml
#PL: Konfiguracja GUI wyboru serwerów.
#EN: Configuration GUI server selector.
server-selector:
  #PL: Czy przedmiot wyboru serwera ma być włączony?
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
    #PL: Ilość linijek gui.
    #EN: Gui rows.
    rows: 5
    #PL: Jak wypełniane ma być gui.
    #EN: How the gui is to be populated.
    filler-type: FULL
    #PL: Jakim przedmiotem ma być wypełnione gui.
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

