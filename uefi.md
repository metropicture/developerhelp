# UEFI

Wikipedia

> O Unified Extensible Firmware Interface (UEFI), em português Interface Unificada de Firmware Extensível, é uma especificação que define uma interface de software entre o sistema operacional e o firmware da plataforma.

UEFI suporta primariamente o esquema de partição GPT.

## What is an UEFI bootable USB flash drive

[Answer](https://superuser.com/a/1128677)

<blockquote>

Most UEFI implementations can also boot from MBR-partitioned USB drives. They expect a file at `/efi/boot/bootx64.efi` to exist. For best compatibility, using the FAT32 filesystem is highly recommended.

An additional BIOS bootcode may exist on the drive. It will be ignored by UEFI.

Bottom line: Hybrid bootable USB drives are possible and do exist.

</blockquote>
