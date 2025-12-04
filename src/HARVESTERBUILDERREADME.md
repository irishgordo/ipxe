1. make bin/ipxe.lkrn bin-x86_64-efi/ipxe.efi EMBED=harvester-airgap-hotpatch.ipxe
2. ./util/genfsimg -o ipxe.iso bin/ipxe.lkrn bin-x86_64-efi/ipxe.efi


## Likely will need to resolve dependencies to build correctly