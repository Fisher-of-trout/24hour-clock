# 24hour-clock
24 hours clock with discrete components
simple clock with common anode display, simple 555 timer to generate 100hz clock, not quite at 50% duty cycle
Added one shot monostable because the reset pulse was too short and unstable
With a power up the FF latches and commits a flasher to all the Leds, a reset is required to start the clock
hour and minute adjust are multiplexed at anytime to adjust the time.
With a 555 timer the clock is fairly accurate as long as there is no large temp change
