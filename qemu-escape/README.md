# qemu-escape

some interesting qemu-escape game.

* BlizzardCTF2017-Strng
	
	fescription: Sombra True Random Number Generator (STRNG) is a QEMU-based challenge I developed for Blizzard CTF 2017. The challenge was to achieve a VM escape from a QEMU-based VM and capture the flag located at /root/flag on the host.

	finished date: 2019.08.04

	writeup: [qemu pwn-Blizzard CTF 2017 Strng writeup](https://ray-cp.github.io/archivers/qemu-pwn-Blizzard-CTF-2017-Strng-writeup)

	officail link: [blizzardctf2017](https://github.com/rcvalle/blizzardctf2017)

* qemu-basic-knowledge

	description: Some basic knowledge for qemu, such as address transformation and basic pci device(edu.c).

	related link: None

	writeup: [qemu-pwn-基础知识](https://ray-cp.github.io/archivers/qemu-pwn-basic-knowledge)

* hitb-gsec-2017-babyqemu

	description: babyqemu pci device `hitb` with mmio, which implemented dma function.

	finished date: 2019.08.07

	writeup: [qemu pwn-hitb gesc 2017 babyqemu writeup](https://ray-cp.github.io/archivers/qemu-pwn-hitb-gesc-2017-babyqemu-writeup)

* DefconQuals-2018-EC3

	description: EC3 pci device `ooo` with mmio, uaf vuln with no symbols.

	finished date: 2019.08.16

	writeup: [qemu-pwn-DefconQuals-2018-EC3](https://ray-cp.github.io/archivers/qemu-pwn-DefconQuals-2018-EC3)

* seccon-2018-q-escape

  description: EC3 pci device `cydf-vga`, out-of-bound vuln with vga device.

  finished date: 2019.08.21

  writeup: [qemu-pwn-seccon-2018-q-escape](https://ray-cp.github.io/archivers/qemu-pwn-seccon-2018-q-escape)	

  officail link: [q-escape](https://github.com/SECCON/SECCON2018_online_CTF/tree/master/Pwn/q-escape)

* xnuca-2019-vxee

	description: vxee pci device `vxee`, out-of-bound vuln with qemu timer to control rip.

	finished date: 2019.08.24

	writeup: [qemu-pwn-xnuca-2019-vexx](https://ray-cp.github.io/archivers/qemu-pwn-xnuca-2019-vexx)

	officail link: None

* qwb-preliminary-2019-qwct

	description: pci device `qwb`, out-of-bound vuln in crypto algorithm.

	finished date: 2019.08.28

	writeup: [qemu-pwn 强网杯2019 两道qemu逃逸题writeup](https://ray-cp.github.io/archivers/qemu-pwn-%E5%BC%BA%E7%BD%91%E6%9D%AF2019-%E4%B8%A4%E9%81%93qemu%E9%80%83%E9%80%B8%E9%A2%98writeup)

	officail link: None

* qwb-final-2019-ExecChrome

	description: pci device `nvme`, overwrite read and write.

	finished date: 2019.08.29

	writeup: [qemu-pwn 强网杯2019 两道qemu逃逸题writeup](https://ray-cp.github.io/archivers/qemu-pwn-%E5%BC%BA%E7%BD%91%E6%9D%AF2019-%E4%B8%A4%E9%81%93qemu%E9%80%83%E9%80%B8%E9%A2%98writeup)

	officail link: None

* cve-2015-5165_and_cve-2015-7504

	description: cve-2015-5165 info leak in rtl8139 and cve-2015-7504 heap overflow in pncet.

	finished date: 2019.09.17

	writeup: [qemu-pwn-cve-2015-5165信息泄露漏洞分析](https://ray-cp.github.io/archivers/qemu-pwn-cve-2015-5165%E4%BF%A1%E6%81%AF%E6%B3%84%E9%9C%B2%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90)

	officail link: [QEMU Case Study](http://www.phrack.org/papers/vm-escape-qemu-case-study.html)

* cve-2019-6778

	description: heap overflow in slirp module.

	finished date: 2019.09.28

	writeup: None

	officail link: [qemu-vm-escape](https://github.com/Kira-cxy/qemu-vm-escape/)