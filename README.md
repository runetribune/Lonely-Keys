# Platformer

This is a game made with Lua and the framework [LOVE2D](https://love2d.org).
The tiles, players, enemies, items and HUD-elements are from the [Platformer Pack Redux](https://kenney.nl/assets/platformer-pack-redux) made by [Kenney.nl](https://kenney.nl/) with some slight modifications done by me.
The maps are made using [Tiled](https://www.mapeditor.org).

### TODO:
`No particular order`
- [ ] Fix all known bugs
    - [ ] Unducking cause issues when there is a block above (considering not fixing, not very noticable) 
    - [ ] Player suddenly stop when walking on flat surface
    - [x] Coins duplicate when restarting (pressing R)
    - [x] Editing number of keys in Tiled messes up the HUD
    - [x] If user hasn't added a required layer in Tiled, it crashes
    - [ ] Land sound doesn't play when just falling of a ledge
- [ ] Add HUD
    - [ ] Level
    - [x] Lives (hearts)
    - [x] Have key or not
    - [x] Time
    - [x] FPS
    - [x] Score
    - [x] Coins
- [x] Switch to next level
- [ ] All levels complete
    - [ ] Add startingscreen / tutoriallevel
        - [x] Change character
        - [x] Collecting coins
        - [x] Wasting time lowers score
        - [x] Keys
        - [x] Press E to go to next level when all available keys are collected
    - [ ] Complete level 1
    - [ ] Add level 2
    - [ ] Add level 3
    - [ ] Add level 4
- [x] Add key and lock
- [x] Add coins
- [x] Restart when dead
- [ ] Spikes
- [x] Add gameoverscreen
- [ ] Music
- [ ] Soundeffects
    - [x] Coins
    - [x] Land
    - [x] Jump
    - [x] Key
    - [ ] Hurt
- [ ] Highscoresystem
