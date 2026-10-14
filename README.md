# smm-cheat-reversal
reversal of smm based valorant cheat
- this slop consists of 2 modules: smm.bin and dxe.bin

# dxe.bin
- installs wmi acpi device 

# smm.bin
- actual smm module which handles communication, cheat logic and auth logic
- interestingly the entire cheat is packed within the smm module

# end
- this is just big modified paste of (SmmMem)[https://github.com/RayanZiani/SmmMem], relies on the same "detected" method
