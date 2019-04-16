# wtf_teslax

FiveM Tesla X Model with custom handling

## Requirements
None

## wtf_teslax

- Tesla Model X
    - 3D model from https://www.gta5-mods.com/vehicles/tesla-model-x-p90d
    - Custom handling, mimicking real-life expectations
        - Best in class acceleration: 0-60 ~4sec, 0-100 ~7sec
        - Limited top end due to increased drag: ~160mph
        - Better than average handling
        - Low center of gravity, limited roll-over

## Download & Installation

This resource was developed alongside [wtf_ev], [wtf_tesla_supercharger]. This resource works without them, but you might be interested in installing them altogether.

### Using Git
```
cd resources
git clone https://github.com/wtf-fivem-mods/wtf_teslax [wtf]/wtf_teslax/

git clone https://github.com/wtf-fivem-mods/wtf_ev [wtf]/wtf_ev/
git clone https://github.com/wtf-fivem-mods/wtf_tesla_supercharger [wtf]/wtf_tesla_supercharger/
```

### Manually
- Download https://github.com/wtf-fivem-mods/wtf_teslax/archive/master.zip
- Create and place in in `[wtf]/wtf_teslax` directory

## Installation
- Add this in your `server.cfg`:

```lua
start wtf_teslax
-- if you downloaded related resources
start wtf_ev
start wtf_tesla_supercharger
```

## Screenshots

![photo_2019-04-14_00-43-29 (1)](https://user-images.githubusercontent.com/79330/56089931-47b54480-5e4f-11e9-9bdf-5183bf6a9ec6.jpg)

![photo_2019-04-14_00-43-29 (2)](https://user-images.githubusercontent.com/79330/56089930-4552ea80-5e4f-11e9-8ac3-8dbdf466dc5a.jpg)


[wtf_ev]: https://github.com/wtf-fivem-mods/wtf_ev
[wtf_tesla_supercharger]: https://github.com/wtf-fivem-mods/wtf_tesla_supercharger