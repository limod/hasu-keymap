# build qmk firmware
	cd qmk_firmware
	vagrant up
	vagrant ssh
		cd /vagrant
		sudo make converter/usb_usb:limod:dfu
