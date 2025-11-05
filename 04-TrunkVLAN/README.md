# CPT-VLAN-Trunk-Yapılandırması

Bu projede, **Cisco Packet Tracer** kullanılarak **VLAN Trunk** yapısının uygulandığı bir ağ topolojisi oluşturulmuştur. Bu topoloji, iki switch üzerinden VLAN’lar arasında veri iletimini sağlamakta ve her VLAN kendi alt ağı içerisinde haberleşmektedir.

## Proje Detayları

### Kullanılan Cihazlar:
- **4 PC**
- **2 Switch**

### VLAN Yapılandırması:
- **VLAN 10**:  
  - IP Adresleri: **192.168.1.10**, **192.168.1.11**  
- **VLAN 20**:  
  - IP Adresleri: **192.168.1.20**, **192.168.1.21**

### Trunk Yapılandırması:
- İki switch arasında **Trunk bağlantısı** yapılandırılmıştır.  
- Her iki switch üzerinde VLAN 10 ve VLAN 20 tanımlanmıştır.  
- Trunk portları, her iki VLAN’dan gelen trafiği taşıyacak şekilde ayarlanmıştır.

## `.pkt` Dosyası:
Bu projeye ait `.pkt` dosyasını indirip **Cisco Packet Tracer** ile açarak VLAN yapılandırmasını ve Trunk bağlantısını inceleyebilirsiniz.

---

# CPT-VLAN-Trunk-Configuration

In this project, a **VLAN Trunk configuration** has been implemented using **Cisco Packet Tracer**. This topology enables communication between VLANs through two interconnected switches, with each VLAN operating within its own subnet.

## Project Details

### Devices Used:
- **4 PCs**
- **2 Switches**

### VLAN Configuration:
- **VLAN 10**:  
  - IP Addresses: **192.168.1.10**, **192.168.1.11**  
- **VLAN 20**:  
  - IP Addresses: **192.168.1.20**, **192.168.1.21**

### Trunk Configuration:
- A **Trunk link** has been configured between the two switches.  
- Both switches have VLAN 10 and VLAN 20 defined.  
- The trunk ports are set to carry traffic for both VLANs.

## `.pkt` File:
You can download the `.pkt` file and open it with **Cisco Packet Tracer** to explore the VLAN setup and Trunk configuration.
