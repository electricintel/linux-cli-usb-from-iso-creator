# linux-cli-usb-from-iso-creator

sudo dd if=(<name of usb disk>).iso of=/dev/(<name of usb>) bs=1M status=progress
  
example:
  sudo dd if=Windows10.iso of=/dev/sdb1 bs=1M status=progress



