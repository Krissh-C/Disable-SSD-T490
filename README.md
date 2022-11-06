# Why does this exist?
This SSDT exists so that anyone who had a PM981 drive installed in their ThinkPad T490 can disable it in case they have another OS installation or are physically unable to remove it.

# Compatibility
Compatibility with newer versions is not guarenteed. Tested upto macOS Monterey 12.6.1 using Opencore v0.8.5.

# Note
This SSDT disables the slot so any SSD installed in it will not work with this.
The SSD still shows up in the Opencore picker so if you boot any other OS using Opencore, you can still use this SSDT as it only affects macOS.
