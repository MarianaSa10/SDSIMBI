# DICOM Protocol com TLS

Esta pasta contém todos os ficheiros, comandos e capturas utilizados na **implementação do protocolo DICOM com TLS/mTLS**, no âmbito do projeto da unidade curricular **Sistemas Distribuídos e Segurança Informática (SDSIMBI)**.

Inclui:
- Comandos usados para os testes C-STORE, C-FIND e C-GET sob ligação TLS/mTLS.  
- Certificados e ficheiros de configuração do Orthanc e dcm4che.  
- Captura de tráfego cifrado (`tls_trafego.pcap`) analisada no Wireshark.  

As Imagens DICOM utilizadas localizam-se na pasta `DICOM Protocol sem TLS`.

Esta implementação demonstra a mitigação das vulnerabilidades do DICOM (transmissão em texto claro e autenticação fraca) através da ativação de **TLS** e **mTLS**, garantindo confidencialidade, integridade e autenticação nas comunicações PACS.
