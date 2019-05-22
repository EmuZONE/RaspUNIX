<b>Ubuntu Linux install OpenSSH server</b>
<p>
  Introduction: sshd (OpenSSH Daemon or server) is the daemon program for ssh client. It is a free and open source ssh server. ssh replaces insecure rlogin and rsh, and provide secure encrypted communications between two untrusted hosts over an insecure network such as the Internet. Ubuntu Desktop and minimal Ubuntu server do not come with sshd installed. However, you can easily install SSH server in Ubuntu using the following steps.
  <p>
    <ulm>
      <li>Open the terminal application for Ubuntu desktop.</li>
     <li>For remote Ubuntu server you must use BMC or KVM or IPMI tool to get console access</li>
     <li>Type sudo apt-get install openssh-server</li>
     <li>Enable the ssh service by typing sudo systemctl enable ssh</li>
     <li>Start the ssh service by typing sudo systemctl start ssh</li>
     <li>Test it by login into the system using ssh user@server-name</li>
    </ulm>
    <p>$ sudo apt update</p>
<p>$ sudo apt upgrade</p>
