<b>Particularity of network in Debian 9:</b>

The old standard "ethX", will no longer be used.
New standard: Predictable Network Interface Names (v197)

#Edit: /etc/default/grub
GRUB_CMDLINE_LINUX="net.ifnames=0 biosdevname=0"

#After, run the command below (on command line):
sudo grub-mkconfig -o /boot/grub/grub.cfg


SOURCE: https://www.vivaolinux.com.br/dica/Como-mudar-o-nome-da-interface-de-rede-padrao-do-Ubuntu