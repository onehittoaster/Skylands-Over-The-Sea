# Skylands Over The Sea - Skybound Edition

Worldgen of sky islands floating over an open ocean, tuned for the "Skybound"
server.

Forked from https://github.com/klinbee/Skylands-Over-The-Sea.

Special thanks to Klinbee for assisting via Discord chat.

## Features

- Sky islands over an open ocean.
- Generously tuned oregen to generate ores useful for Create and Valkyrien Skies.
- Diamonds and Wanderlite generate in the rare islands at Y >= 200.

## Dependencies

- https://modrinth.com/mod/chipped
  - https://modrinth.com/mod/athena-ctm
  - https://modrinth.com/mod/resourceful-lib
- https://modrinth.com/mod/create-dreams-and-desires
  - https://modrinth.com/mod/create
- https://modrinth.com/mod/more-density-functions
- https://modrinth.com/mod/valkyrien-skies
  - https://modrinth.com/mod/create-clockwork
- https://modrinth.com/mod/lithostitched/
  - lithostitched-fabric-1.20.1-1.1.6.jar  (seems sensitive to the exact version).

Not a pure dependency, per-se, but without "Feature Recycler", the mapgen will
crash when generating for Deep Dark.  This is a bug in our mapgen and needs
to be fixed.
- https://modrinth.com/mod/feature-recycler
