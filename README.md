# build qmk firmware
	cd qmk_firmware
	vagrant up
	vagrant sshqmk chaining
		cd /vagrant
		sudo make converter/usb_usb:limod:dfu
