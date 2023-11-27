# Globals
## GWorld (sigs potentially wrong, but most likely right)
- Offset: 0x65A5CF0

## GObjects
- Offset: 0x64A0090

## GNames
- Offset: 0x45176C0

## GEngine
- Offset: 0x0


# Functions
## StaticFindObject
- Offset: 0x22FB1E0
- IDA Sig: 48 89 5C 24 ? 48 89 74 24 ? 55 57 41 54 41 56 41 57 48 8B EC 48 83 EC 60 80 3D ? ? ? ? ? 45 0F B6 F1 49 8B F8 48 8B DA 4C 8B F9 74 4E 48 8B 05 ? ? ? ?
- Code Pattern: \x48\x89\x5C\x24\x00\x48\x89\x74\x24\x00\x55\x57\x41\x54\x41\x56\x41\x57\x48\x8B\xEC\x48\x83\xEC\x60\x80\x3D\x00\x00\x00\x00\x00\x45\x0F\xB6\xF1\x49\x8B\xF8\x48\x8B\xDA\x4C\x8B\xF9\x74\x4E\x48\x8B\x05\x00\x00\x00\x00, xxxx?xxxx?xxxxxxxxxxxxxxxxx?????xxxxxxxxxxxxxxxxxx????

## GetBoneMatrix (potentially wrong, but most likely right)
- Offset: 0x2FBD3F0
- IDA Sig: 48 8B C4 55 53 56 57 41 54 41 56 41 57 48 8D 68 A1 48 81 EC ? ? ? ? 0F 29 78 B8 33 F6 44 0F 29 40 ? 4C 8B E2 44 0F 29 48 ? 48 8B F9 44 0F 29 50 ?
- Code Pattern: \x48\x8B\xC4\x55\x53\x56\x57\x41\x54\x41\x56\x41\x57\x48\x8D\x68\xA1\x48\x81\xEC\x00\x00\x00\x00\x0F\x29\x78\xB8\x33\xF6\x44\x0F\x29\x40\x00\x4C\x8B\xE2\x44\x0F\x29\x48\x00\x48\x8B\xF9\x44\x0F\x29\x50\x00, xxxxxxxxxxxxxxxxxxxx????xxxxxxxxxx?xxxxxxx?xxxxxxx?

## LineOfSightTo (potentially wrong, but most likely right)
- Offset: 0x352C330
- IDA Sig: 48 89 5C 24 ? 56 57 41 56 48 83 EC 40 33 FF 48 8B F1 4D 8B F0 48 8B DA 48 8B CA 48 89 7C 24 ? 48 39 7A 20 74 10 48 8B 52 18 4C 8D 44 24 ? E8 ? ? ? ? EB 1C
- Code Pattern: \x48\x89\x5C\x24\x00\x56\x57\x41\x56\x48\x83\xEC\x40\x33\xFF\x48\x8B\xF1\x4D\x8B\xF0\x48\x8B\xDA\x48\x8B\xCA\x48\x89\x7C\x24\x00\x48\x39\x7A\x20\x74\x10\x48\x8B\x52\x18\x4C\x8D\x44\x24\x00\xE8\x00\x00\x00\x00\xEB\x1C, xxxx?xxxxxxxxxxxxxxxxxxxxxxxxxx?xxxxxxxxxxxxxx?x????xx
