# PicoFeeder
RP2040 Pico W with integrated Stepper Driver Board

See https://ell-tech.com/dog-feeder/ running ESPHome 2023.6.4 for more information

Adapted from the Big Easy Driver by Brian Schmalz https://www.schmalzhaus.com/BigEasyDriver/ and adapted by Sparkfun https://github.com/sparkfun/Big_Easy_Driver/tree/V_HW1.6a_FW1.0 

Licenced under https://creativecommons.org/licenses/by-sa/3.0/

Please note the following changes in this Big Easy Driver V1.6E from the original V1.6:
- Buck converter has been incorporated to replace LM317 linear regulator to provide additional power for the RP2040.
- Enable pin now pulled-up by default (instead of down) to start stepper driver disabled. Cut and solder JP15 to enable by default.
