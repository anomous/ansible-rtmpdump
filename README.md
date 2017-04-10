# ansible-rtmpdump

Build and install rtmpdump

## Requirements

Same requirements as rtmpdump in order to build it.

## Role Variables

`rtmpdump_ksv_patch`:
- Default: `True`
- Apply a patch from [@K-S-V](https://github.com/K-S-V/Scripts/releases) to rtmpdump before building it, more informations [here](http://stream-recorder.com/forum/customized-rtmpdump-binaries-patch-file-t16103.html)

## Dependencies

None.

## Example Playbook

```YAML
- hosts: servers
  roles:
     - { role: t0n3.rtmpdump }
```

## License

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```
