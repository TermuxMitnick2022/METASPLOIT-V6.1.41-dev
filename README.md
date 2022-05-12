# METASPLOIT-V6.1.41-dev

Metasploit é um projeto de segurança da informação, usado para investigar vulnerabilidades em plataformas, servidores e sistemas operacionais.
______________________________________________________________________________________________________________________________________________

~$ apt update && apt upgrade -y 

~$ pkg install git
 
~$ git clone https://github.com/efxtv/Metasploit-in-termux

~$ cd Metasploit-in-termux

~$ chmod +x metasploit-6-termux.sh

~$ bash metasploit-6-termux.sh

~$ msfconsole

SE DER ERRO NA INSTALAÇÃO, CONTINUEM COM OS COMANDS ABAIXO:

~$ cd metasploit-framework;
sed -i '13,15 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/encryption_algorithm/functionable.rb; sed -i '14 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/server_host_key_algorithm/ecdsa_sha2_nistp256.rb; sed -i '14 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/server_host_key_algorithm/ecdsa_sha2_nistp384.rb; sed -i '14 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/server_host_key_algorithm/ecdsa_sha2_nistp521.rb

~$ msfconsole
