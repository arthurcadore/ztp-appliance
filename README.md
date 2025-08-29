# Zero Touch Provisioning Appliance

Este projeto fornece uma **appliance de Zero Touch Provisioning (ZTP)** baseada em **Docker Compose**, que combina **servidores DHCP e TFTP** para automatizar o provisionamento de dispositivos em rede.  

---

## Visão Geral

O ZTP Appliance inclui dois serviços principais:

- **DHCP Server**  
  Responsável por atribuir endereços IP aos dispositivos clientes e indicar a localização do servidor TFTP.  

- **TFTP Server**  
  Fornece os arquivos de configuração e imagens necessárias para inicialização/provisionamento dos clientes.  

Essa combinação é usada em ambientes de rede para **boot remoto, configuração automática e inicialização sem intervenção manual**.