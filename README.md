# WTRTI-Profiles

1. Profile_RTSS_OSD - Intended for use with Riva Tuner Statistics Server and won't work without it
2. Profile_WTRTI_OSD - Uses WTRTI's own OSD and doesn't require RTSS
3. Profile_RTSS_OSD_4K - Same as 1 but for 4K monitors
4. Profile_WTRTI_OSD_4K - Same as 2 but for 4K monitors
5. Profile_RTSS_OSD_1440p - Same as 1 but for 1440p monitors
6. Profile_WTRTI_OSD_1440p - Same as 2 but for 1440p monitors

The only difference between the profiles is the position of the groups, which needs to be halved in RTSS OSD to end up in the same position.
Due to the fact that positions are set with absolute values and not percentages, the groups will only appear in intended positions when a preset with your monitor's native resolution is loaded.

# Tips

When loading a different profile, don't forget to change the OSD Type in WTRTI's settings.
If the RTSS OSD doesn't appear after starting the game, press Alt + Z to open the Nvidia overlay to make RTSS OSD appear.
