In the System Design, Architecture & Administration phase, a simulated
environment was created on Vmare, where three devices and two servers
were connected to an internal network. The IP addresses were assigned,
and the smb and ftb services were utilized to facilitate file transfers,
while http allowed access to the company website. Moreover, the mysql
service was employed to store data within the system.

In the Offensive Cybersecurity phase, social engineering and multiple
vulnerabilities were exploited, and several attacks were carried out.
The hacker leveraged the Password pattern vulnerability to execute a
brute-force attack and extract the admin device. Subsequently, the
Windows Shell Remote Code Execution Vulnerability (MS10-046) was
exploited on the employee\'s Windows 7 device through a malicious
shortcut file attack, enabling shell access. Further, the attacker
placed a malicious code within the project file, which was sent by an
employee to the CEO, thereby executing a trajon attack and spyware
attack, and gaining access to all the database passwords. The attacker
then demanded a sum of money from the company, and provided
recommendations to the red team, detailing the steps followed and the
risk associated with each attack.

In the Defensive Cybersecurity phase, the impact of the attack was
traced through the login files, and all back doors were removed to
prevent re-entry. The identified gaps were fixed by increasing
protection, installing antivirus on the devices, updating all devices to
address existing gaps in the old versions, and setting laws to guide
employee behavior. Finally, the employees were trained to mitigate the
risk of future attacks.

It is important to note that this was a simulated exercise, and the CEO
was fully briefed on each stage of the process. The reports presented
were designed to be comprehensible to all stakeholders, including
technical and management teams
