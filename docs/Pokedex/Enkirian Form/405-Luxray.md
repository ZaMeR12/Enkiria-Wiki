# 405 - Luxray

!!! note
    Information not listed on this page can be found on the Pixelmon Wiki of the base form of this species.

    [Base info :material-pokeball:](https://pixelmonmod.com/wiki/Luxray){: .md-button .md-button--primary target="_blank"}

<div class="grid" markdown>
Normal palette
![Luxray normal](luxray.png){ width=150;}
{ .card }

Shiny palette
![Luxray shiny](luxray-shiny.png){ width=150;} 
{ .card }

</div>

## Entry
This Luxray variant evolved to thrive in Enkiria’s volcanic plains, where nights are long and skies often stormy. Unlike its regular form, it doesn't rely on sight—it detects movement through faint electrical pulses in the air. Its fangs carry a paralyzing current, and it prefers ambush tactics, striking from high rocks or dense underbrush. Rangers use its presence as a sign of a healthy but dangerous ecosystem.

### Category
Shadow Fang Pokémon

## Types
<div markdown="span">
![Electric type](electric-type.png){ width=100; align=left;}
![Dark type](dark-type.png){ width=100; align=right;}
</div>

## Evolutions

``` mermaid
graph LR
  A[Shinx] -->  B{Level 15};
  B --> C[Luxio];
  C --> D{Level 30};
  D --> E[Luxray];
  C --> | Using a Dusk Stone </br> <img title="Dusk Stone" src="https://images.weserv.nl/?url=archives.bulbagarden.net/media/upload/e/e1/Bag_Dusk_Stone_LA_Sprite.png" width="100">| F{  };
  F --> |Holding a Razor Fang </br> <img title="Razor Fang" src="https://images.weserv.nl/?url=archives.bulbagarden.net/media/upload/f/f1/Bag_Razor_Fang_LA_Sprite.png" width="100">| G[Enkirian Luxray];
```


## Battle stats

=== "Graph"

    ```vegalite
    {
      "description": "Battle stats of the pokemon.",
      "data": {"url": "assets/pixelmon/luxray/battleStats.json"}
      ,
      "mark": {"type": "bar", "tooltip": true,"cornerRadiusEnd": 4},
      "encoding": {
        "y": {"field": "Stats", "type": "nominal", "axis": {"labelAngle": 0}},
        "x": {"field": "Power", "type": "quantitative"},
        "color": {"field": "Stats"}
      }
    }
    ```

=== "Table"

    {{ read_json('assets/pixelmon/luxray/battleStats.json') }}


Total: 523
                   
