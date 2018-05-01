# ansible-role-pxe-server
Ansible role to setup a Ubuntu pxe server

## Variable(s)
Variable(s) you can use in your own playbook.

  ### PXE server settings
  pxe_subnet                     : '192.168.0.0'
  pxe_tftpboot_dir               : '/opt/tftpboot'


  ### Preseed.cfg Variable(s)

  # Kernel Options
  pxe_preseed_locale             : 'en_GB.UTF-8'
  pxe_preseed_keyboard           : 'us'

  # Timezone
  pxe_preseed_timezone           : 'Europe/Amsterdam'

  # Username & Password
  pxe_preseed_user               : 'administrator'
  pxe_preseed_user_password      : 'Welkom123'

  # Mirror
  pxe_preseed_mirror             : 'nl.archive.ubuntu.com'

## Source(s)
https://www.theurbanpenguin.com/pxelinux-using-proxy-dhcp/
https://www.theurbanpenguin.com/pxe-install-ubuntu-16-04/
