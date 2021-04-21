# 👀 Setup an Oculus Rift on a Windows 10 VM made with KVM on Linux

👋 Hey!
I'll explain you how to setup an Oculus Rift/Rift S/Quest (1/2) on a Windows 10 VM made with Qemu and KVM with a GPU Passthrough.

## 📂 Prerequisites
- A Windows 10 VM made with KVM and with a GPU passthrough
- Obviously an Oculus (Any Oculus, tested with a CV1 and a Quest 2)
- *If it's a Quest, an Oculus link*
- And a brain

## 🛠 How to make?

You'll need to made a USB passthrough, so your virtual Windows can detect the Oculus device.
The disadvantage is that you can't use Linux and Windows at the same time (For now, I'm working on it 😄).
I'll show in this tutorial how to make a USB passthrough and make a little .sh for unbind your CPU/PCIe USB controller.


#### Description of my Setup
Hardware:
- CPU: Intel Core i5-9600K
- GPUs: MSI Nvidia GTX 650 (For Linux 🐧) and an Aorus RTX 2060 Super (For Windows 📋)

Software:
- OS: Manjaro 21.0 XFCE
- VM OS: Windows 10 20H2
- For the VM: Qemu 5, with virt-manager


### For Intel CPUs



### For AMD CPUs



### For PCIe USB controllers
