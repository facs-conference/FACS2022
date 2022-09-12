---
name: 'Formal Model in the loop for Secure Industrial Control Networks'
speakers:
  - Laurynas Ubys
  - Valeriu Nicolas Vancea
  - Tomas Kulik
  - Peter Gorm Larsen
  - Jalil Boudjadar
  - Diego F Aranha
categories:
  - Software Engineering
---

Current trends of digitalization are becoming significantly prevalent within the field of industrial control systems. While in recent history a typical industrial control system would have been isolated with rudimentary ways of extracting data, nowadays it is becoming expected that the control system could not only provide large amounts of data over the network but also receive firmware updates and patches. To this end it is important to secure the communication between the components of the system, as well as ensure that only approved components can communicate together. Secure communication and device authentication could be achieved by use of cryptographic keys and certificates. The system however must be able to securely manage the keys and certificates in order to ensure their authenticity and validity. In this paper we present a prototype of a pluggable key management device for industrial control systems with a key management protocol and integrated formal analysis of the running system - a model in the loop. This allows the system to continuously analyse the network traffic according to the protocol using VDM and hence assure compliance with several security properties. We use off-the-shelf hardware, custom key and device management protocol and VDM to ensure that the device satisfies requirements posed by our industrial partner.