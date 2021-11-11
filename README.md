# MCPI-Better-Creative-Inventory
This is a mod for minecraft: pi edition reborn that expands the creative inventory so that you have access to all items.
## Using
To use this mod you will need to download the shared library and place it in the mods folder of minecraft: pi edition, to do this download libbci.so and run 
```bash
mv ~/Downloads/libbci.so /opt/minecraft-pi-reborn-client/mods/libbci.so 
``` 
Then all you need to do is run minecraft: pi edition with the Expand Creative Inventory mod activated.
## Compiling
To compile your own version of it you will need the libreborn folder and the creative.cpp file, then once you finish editing creative.cpp, you run:
```bash
arm-linux-gnueabihf-g++ -shared -o libbci.so creative.cpp -DREBORN_HAS_COMPILED_CODE
``` 
This will compile a version of libbci.so with your changes.
