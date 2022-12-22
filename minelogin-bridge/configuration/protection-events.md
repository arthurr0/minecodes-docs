---
description: Configuring blocked interactions on your lobby server
---

# ⏰ Protection events

{% hint style="danger" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1fa-1f1f8.svg" alt="🇺🇸" data-size="line"> To unlock all blocked interactions, grant the `sminelogin.protection.bypass` permissions for the player in question.
{% endhint %}

{% hint style="danger" %}
<img src="https://twemoji.maxcdn.com/2/svg/1f1f5-1f1f1.svg" alt="🇵🇱" data-size="line"> Aby odblokować wszystkie zablokowane interakcje, należy nadać dla danego gracza permisje `sminelogin.protection.bypass`
{% endhint %}

```yaml
protection-events:
  #PL: Ochrona przed otrzeniem obrażeń.
  #EN: Protection for damage.
  entity-damage-event: true
  #PL: Ochrona przed wurzucaniem przedmiotów.
  #EN: Protection for drop items.
  drop-item-event: true
  #PL: Ochrona przed podnoszeniem przedmiotów.
  #EN: Protection for pickup items.
  pick-up-item-event: true
  #PL: Ochrona przed integracją z blokami.
  #EN: Protection for interact with blocks.
  interact-event: true
```
