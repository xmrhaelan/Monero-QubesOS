# A Guide to Monero + Qubes OS

Join the conversation on Matrix: #monero-qubesos:matrix.org

## Introduction 

Using Monero + Qubes OS (running Whonix) you can have a Monero wallet that is without networking and running on a virtually isolated system from the Monero daemon which has all of its traffic forced over Tor.

## Things to Know About Qubes OS

Qubes OS requires a dedicated machine. Qubes OS is not a Linux distro. It is a specialized operating system that runs on hypervisor technology, allowing you to run Linux distros on a virtual machine within the Qubes OS.

If you do not already have a Qubes machine, you will want to consult the Qubes OS [Hardware Compatibility List](https://www.qubes-os.org/hcl/). You may find a device on this list you already own, or it may help you shop around for one that will work. Tip: plan to max out the capable RAM capacity for max performance.

Qubes OS has built in Linux distros including Debian, Fedora, and Whonix. For the sake of using Monero + Qubes OS you will be utilizing Whonix, which enables you to have two separate virtual machines (VMs) working together for the maximum security and privacy while using Monero. One Whonix VM will be disconnected from any internet connection and will control the wallet, the other will force all traffic through Tor and allow your wallet to interact with the Monero network in safety.

https://www.reddit.com/r/Qubes/comments/isrty8/plans_to_update_qrexec_documentation/
