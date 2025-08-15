---
title: "Pikachu (Cosplay)"
description: "Pikachu's Cosplay form, featuring unique battle stats and abilities."
---

# Pikachu (Cosplay)

!!! note
    Information not listed on this page can be found on the Pixelmon Wiki of the base form of this species.

    [Base info :material-pokeball:](https://pixelmonmod.com/wiki/Pikachu){: .md-button .md-button--primary target="_blank"}

## Cosplay Forms

=== "Belle"
    ![Pikachu Belle](https://images.weserv.nl/?url=archives.bulbagarden.net/media/upload/thumb/f/ff/0025Pikachu-Belle.png/1024px-0025Pikachu-Belle.png){ width=175 align=left}

    <h2>Types</h2>
    <div markdown="span">
    ![Electric type](electric-type.png){ width=100; align=left;}
    ![Ice type](ice-type.png){ width=100; align=right;}
    </div>

    <h2>Moves</h2>

    === "Level up"
        | Level |                                    Moves                                    | Replace (:octicons-check-16:) or Add (:octicons-x-16:) |
        | :---: | :-------------------------------------------------------------------------: | :----------------------------------------------------: |
        |  0  |  [Ice Punch](https://pixelmonmod.com/wiki/Ice_Punch){:target="_blank"}  |                  :octicons-x-16:

=== "PhD"
    ![Pikachu PhD](https://images.weserv.nl/?url=archives.bulbagarden.net/media/upload/thumb/c/c1/0025Pikachu-PhD.png/1024px-0025Pikachu-PhD.png){ width=175 align=left}

    <h2>Types</h2>
    <div markdown="span">
    ![Electric type](electric-type.png){ width=100; align=left;}
    ![Steel type](steel-type.png){ width=100; align=right;}
    </div>

    <h2>Moves</h2>

    === "Level up"
        | Level |                                    Moves                                    | Replace (:octicons-check-16:) or Add (:octicons-x-16:) |
        | :---: | :-------------------------------------------------------------------------: | :----------------------------------------------------: |
        |  0  |  [Magnet Bomb](https://pixelmonmod.com/wiki/Magnet_Bomb){:target="_blank"}  |                  :octicons-x-16:

=== "Pop Star"
    ![Pikachu Pop Star](https://images.weserv.nl/?url=archives.bulbagarden.net/media/upload/thumb/0/09/0025Pikachu-Pop_Star.png/1024px-0025Pikachu-Pop_Star.png){ width=175 align=left}

    <h2>Types</h2>
    <div markdown="span">
    ![Electric type](electric-type.png){ width=100; align=left;}
    ![Fairy type](fairy-type.png){ width=100; align=right;}
    </div>

=== "Rock Star"
    ![Pikachu Rock Star](https://images.weserv.nl/?url=archives.bulbagarden.net/media/upload/thumb/0/0a/0025Pikachu-Rock_Star.png/1024px-0025Pikachu-Rock_Star.png){ width=175 align=left}

    <h2>Types</h2>
    <div markdown="span">
    ![Electric type](electric-type.png){ width=100; align=left;}
    ![Fire type](fire-type.png){ width=100; align=right;}
    </div>

    <h2>Moves</h2>

    === "Level up"
        | Level |                                    Moves                                    | Replace (:octicons-check-16:) or Add (:octicons-x-16:) |
        | :---: | :-------------------------------------------------------------------------: | :----------------------------------------------------: |
        |  0  |  [Fire Punch](https://pixelmonmod.com/wiki/Fire_Punch){:target="_blank"}  |                  :octicons-x-16:

=== "Libre"
    ![Pikachu Libre](https://images.weserv.nl/?url=archives.bulbagarden.net/media/upload/thumb/0/03/0025Pikachu-Libre.png/1024px-0025Pikachu-Libre.png){ width=175 align=left}

    <h2>Types</h2>
    <div markdown="span">
    ![Electric type](electric-type.png){ width=100; align=left;}
    ![Fighting type](fight-type.png){ width=100; align=right;}
    </div>

## Battle stats

=== "Graph"

    ```vegalite
    {
      "description": "Battle stats of the pokemon.",
      "data": {"values": [
      {"Stats": "HP", "Power": 60},
      {"Stats": "Attack", "Power": 55},
      {"Stats": "Defense", "Power": 45},
      {"Stats": "Special Attack", "Power": 50},
      {"Stats": "Special Defense", "Power": 50},
      {"Stats": "Speed", "Power": 120}
    ]}
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

    {{ read_json('assets/pixelmon/pikachu/cosplay/battleStats.json') }}

Total: 380