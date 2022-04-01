# Metasploit Fix Errors
<h1>METASPLOIT INSTALL TERMUX WITHOUT ANY ALL ERROR FIXED</h1>
all fixed metasploit errors gems ruby 

open termx type and execute commands

<code>
pkg update; pkg upgrade
</code>
<code>pkg install wget curl</code>

<code>cd $HOME;wget https://raw.githubusercontent.com/SIDHARTH-GHULE/metasploit/main/metasploit-sid-termux.sh -q;bash metasploit-sid-termux.sh</code>

<code>rm -rf /data/data/com.termux/files/usr/bin/msfvenom</code>

<code>cd;cd metasploit-framework;ln -s $HOME/metasploit-framework/msfvenom /data/data/com.termux/files/usr/bin/</code>
 <h3>after type msfconsole showing this ciphererror</h3>
 <h1> unsupported (OpenSSL::Cipher::CiPherError)</h1>
 after installing metasploit-sid-termux go to home page and pest this bellow code 
 <code>sed -i '13,15 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/encryption_algorithm/functionable.rb; sed -i '14 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/server_host_key_algorithm/ecdsa_sha2_nistp256.rb; sed -i '14 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/server_host_key_algorithm/ecdsa_sha2_nistp384.rb; sed -i '14 {s/^/#/}' /data/data/com.termux/files/usr/lib/ruby/gems/3.1.0/gems/hrr_rb_ssh-0.4.2/lib/hrr_rb_ssh/transport/server_host_key_algorithm/ecdsa_sha2_nistp521.rb;
clear;echo "Done...."</code>

after type <code>msfconsole</code> its 
