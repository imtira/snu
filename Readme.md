# Notes on the .SNA format
Used by the Disk Snapshot software. Proprietary.

`0x0`: The magic `0x534E5445` ["SNTE"]
- Magic
`0x14`:  `Jan 14 2021`
`0x28`: `08:49:44`
- I have no idea why this date is here. It was weeks before the date set in the VM, over 12 hours before the time too.
`0x48`: `*IMAGELIST="100MB-Empty-NTFS-aaaaaaaaaa.SNA"*` `0x00` `*OSName=Windows 10 64-bit (14393)*` `0x00` `*MemInfo=Total: 4095Mb, Free: 2584Mb, Pagefile total: 5503Mb, Pagefile free: 3975Mb*` `0x00` `*CmdLine="C:\Users\re\Desktop\Untouched\snapshot.exe"``0x20` `*`

EOF: `0x0000534e5245`
