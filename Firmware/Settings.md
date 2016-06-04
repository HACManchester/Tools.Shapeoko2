# Grbl Settings

## Original Setttings 0.8c

These are the settings from the original setup 0.8c
```
$0=40.020 (x, step/mm)
$1=40.020 (y, step/mm)
$2=320.000 (z, step/mm)
$3=30 (step pulse, usec)
$4=500.000 (default feed, mm/min)
$5=500.000 (default seek, mm/min)
$6=252 (step port invert mask, int:11111100)
$7=255 (step idle delay, msec)
$8=25.000 (acceleration, mm/sec^2)
$9=0.050 (junction deviation, mm)
$10=0.100 (arc, mm/segment)
$11=25 (n-arc correction, int)
$12=3 (n-decimals, int)
$13=0 (report inches, bool)
$14=1 (auto start, bool)
$15=0 (invert step enable, bool)
$16=0 (hard limits, bool)
$17=0 (homing cycle, bool)
$18=0 (homing dir invert mask, int:00000000)
$19=25.000 (homing feed, mm/min)
$20=250.000 (homing seek, mm/min)
$21=100 (homing debounce, msec)
$22=1.000 (homing pull-off, mm)
```

## New Setttings 0.9j

These are the settings for the new updated firmware

  * http://www.shapeoko.com/wiki/index.php/Grbl_Settings

```
$0=10 (step pulse, usec)
$1=255 (step idle delay, msec)
$2=252 (step port invert mask:11111100)
$3=7 (dir port invert mask:00000000)
$4=0 (step enable invert, bool)
$5=0 (limit pins invert, bool)
$6=0 (probe pin invert, bool)
$10=3 (status report mask:00000011)
$11=0.020 (junction deviation, mm)
$12=0.002 (arc tolerance, mm)
$13=0 (report inches, bool)
$20=0 (soft limits, bool)
$21=0 (hard limits, bool)
$22=0 (homing cycle, bool)
$23=1 (homing dir invert mask:00000001)
$24=25.000 (homing feed, mm/min)
$25=635.000 (homing seek, mm/min)
$26=100 (homing debounce, msec)
$27=1.000 (homing pull-off, mm)
$100=40.020 (x, step/mm)
$101=40.020 (y, step/mm)
$102=320.000 (z, step/mm)
$110=500.000 (x max rate, mm/min)
$111=500.000 (y max rate, mm/min)
$112=500.000 (z max rate, mm/min)
$120=25.000 (x accel, mm/sec^2)
$121=25.000 (y accel, mm/sec^2)
$122=25.000 (z accel, mm/sec^2)
$130=200.000 (x max travel, mm)
$131=200.000 (y max travel, mm)
$132=200.000 (z max travel, mm)
```

### Differences from Defaults

This is a list of changes from the defaults that need to be applied when updating the firmware to 0.9

```
$0=30 (step pulse, usec)
$1=255 (step idle delay, msec)
$2=252 (step port invert mask:11111100)
$3=7 (dir port invert mask:00000000)
$11=0.020 (junction deviation, mm)
$23=1 (homing dir invert mask:00000001)
$25=635.000 (homing seek, mm/min)
$26=100 (homing debounce, msec)
$100=40.020 (x, step/mm)
$101=40.020 (y, step/mm)
$102=320.000 (z, step/mm)
$120=25.000 (x accel, mm/sec^2)
$121=25.000 (y accel, mm/sec^2)
$122=25.000 (z accel, mm/sec^2)
```

### Settings unique to this device

First one setting that's different for the g-sheild is the one that inverts the step pins
```
$2=252 (step port invert mask:11111100)
```

Next this one inverts the direction of the axis for all 3 axis
```
$3=7
```

### Micro Stepping

Currently the microstepping jumpers on the board are set to

  * 8x for the X / Y Axis (no jumper)
  * 2x for the Z Axis
