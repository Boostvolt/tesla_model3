# tesla_model3

FiveM Tesla Model 3 with custom handling

## Requirements
None

## tesla_model3

- Tesla Model 3
    - Custom handling, mimicking real-life expectations
        - Best in class acceleration: 0-60 ~4sec, 0-100 ~7sec
        - Limited top end due to increased drag: ~160mph
        - Better than average handling
        - Low center of gravity, limited roll-over

## Download & Installation

This resource was developed alongside [tesla_ev], [tesla_supercharger]. This resource works without them, but you might be interested in installing them altogether.

### Using Git
```
cd resources
git clone https://github.com/boostvolt/tesla_model3 [tesla]/tesla_model3/

git clone https://github.com/boostvolt/tesla_ev [tesla]/tesla_ev/
git clone https://github.com/boostvolt/tesla_supercharger [tesla]/tesla_supercharger/
```

### Manually
- Download https://github.com/boostvolt/tesla_model3/archive/master.zip
- Create and place in in `[tesla]/tesla_model3` directory

## Installation
- Add this in your `server.cfg`:

```lua
start tesla_model3
-- if you downloaded related resources
start tesla_ev
start tesla_supercharger
```

## Screenshots

![photo_2019-04-14_00-43-29 (1)](https://raw.githubusercontent.com/Boostvolt/images/master/7df1a4-PGTA5662461201.jpg?token=AMLBA7H57EHZMWS5K77VTAS5XHSFA)

![photo_2019-04-14_00-43-29 (2)](https://github.com/Boostvolt/images/blob/master/7df1a4-PGTA5970072599.jpg?raw=true)


[wtf_ev]: https://github.com/boostvolt/tesla_ev
[wtf_tesla_supercharger]: https://github.com/boostvolt/tesla_supercharger
