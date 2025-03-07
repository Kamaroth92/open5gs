---
layout: page
title: Documentation
subject: Documentation
permalink: /docs/
head_inline: "<style> ul { padding-bottom: 1em; } </style>"
---

- User's Guide
  - [Quickstart](guide/01-quickstart)
  - [Building Open5GS from Sources](guide/02-building-open5gs-from-sources)

- Tutorials
  - [Your First LTE](tutorial/01-your-first-lte)
  - [5G SA COTS UE](https://docs.srsran.com/projects/project/en/latest/tutorials/source/cotsUE/source/index.html) from [SRS](https://srs.io)
  - [Metrics with Prometheus](tutorial/04-metrics-prometheus)
  - [VoLTE Setup with Kamailio IMS and Open5GS](tutorial/02-VoLTE-setup)
  - [Dockerized VoLTE Setup](tutorial/03-VoLTE-dockerized)
  - [Roaming](tutorial/05-roaming)

- Inside Source Code
  - [UPF Code Explanation](https://medium.com/@aditya.koranga/open5gs-upf-code-explanation-with-flow-c-79c50f253dd1)
  - [SMF Code Explanation](https://medium.com/@aditya.koranga/open5gs-smf-code-explanation-with-flow-charts-a3b3cd38c991)

- Troubleshooting
  - [Simple Issues](troubleshoot/01-simple-issues)
  - [Now in Github Issues](troubleshoot/02-now-in-github-issues)

- Platform Specific Notes
  - [Debian/Ubuntu](platform/01-debian-ubuntu)
  - [CentOS](platform/02-centos)
  - [Fedora](platform/03-fedora)
  - [MacOSX(Apple Silicon)](platform/05-macosx-apple-silicon)
  - [MacOSX(Intel)](platform/06-macosx-intel)
  - [FreeBSD](platform/07-freebsd)
  - [Alpine](platform/08-alpine)

- Hardware Specific Notes
  - [eNodeBs/gNodeBs tested on Open5GS](hardware/01-genodebs)

- @infinitydon
  - [Open5GS on Amazon Elastic Kubernetes Service](https://aws.amazon.com/blogs/opensource/open-source-mobile-core-network-implementation-on-amazon-elastic-kubernetes-service/)
  - [Kubernetes Open5GS Deployment](https://dev.to/infinitydon/virtual-4g-simulation-using-kubernetes-and-gns3-3b7k?fbclid=IwAR1p99h13a-mCfejanbBQe0H0-jp5grXkn5mWf1WrTHf47UtegB2-UHGGZQ)
  - [5G Core SBI mTLS Using External Certificate PKI](https://futuredon.medium.com/5g-core-sbi-mtls-using-external-certificate-pki-4ffc02ac7728)
  - [5G Frame Routing](https://futuredon.medium.com/5g-frame-routing-6e34d8587123)
  - [5G SCTP LoadBalancer Using LoxiLB](https://futuredon.medium.com/5g-sctp-loadbalancer-using-loxilb-b525198a9103)([Video Link](https://youtu.be/k3ICc7MXcC8))

- @nickvsnetworking
  - [My first 5G Core : Open5GS and UERANSIM](http://nickvsnetworking.com/my-first-5g-core-open5gs-and-ueransim/)
  - [Sending SMS in Open5GS LTE Networks using the SGs Interface and OsmoMSC](https://nickvsnetworking.com/sending-sms-in-open5gs-lte-networks-using-the-sgs-interface-and-osmomsc-with-smsos/)
  - [OsmoMSC and Open5GS MME – SGs Interface for CSCF / InterRAT Handover](https://nickvsnetworking.com/osmomsc-and-open5gs-mme-sgs-interface-for-cscf-interran-handover/)
  - [Static IPs for UEs](http://nickvsnetworking.com/open5gs-epc-static-ip-addresses-for-ues-apns-subscribers/)
  - [Open5GS without NAT](https://nickvsnetworking.com/open5gs-without-nat/)
  - [Basics of EPC/LTE Online Charging (OCS)](https://nickvsnetworking.com/basics-of-epc-lte-online-charging-ocs/)
  - [Backing up and Restoring Open5GS](https://nickvsnetworking.com/backing-up-and-restoring-open5gs/)
  - Diameter Routing Agents - [Part 1](https://nickvsnetworking.com/diameter-routing-agents-why-you-need-them-and-how-to-build-them-part-1/), [Part 2](https://nickvsnetworking.com/diameter-routing-agents-why-you-need-them-and-how-to-build-them-part-2-routing/), [Part 3](https://nickvsnetworking.com/diameter-routing-agents-part-3-building-a-dra-with-freediameter/)

- @s5uishida
  - [Open5GS EPC & OpenAirInterface UE/RAN Sample configuration](https://github.com/s5uishida/open5gs_epc_oai_sample_config)
  - [Open5GS 5GC & UERANSIM UE/RAN Sample Configuration](https://github.com/s5uishida/open5gs_5gc_ueransim_sample_config)
  - [Open5GS & UERANSIM - Select nearby UPF according to the connected gNodeB](https://github.com/s5uishida/open5gs_5gc_ueransim_nearby_upf_sample_config)
  - [VoLTE and SMS Configuration for docker_open5gs](https://github.com/s5uishida/docker_open5gs_volte_sms_config)
  - [Select nearby UPF(PGW-U) according to the connected eNodeB](https://github.com/s5uishida/open5gs_epc_srsran_nearby_upf_sample_config)
  - [Select UPF based on S-NSSAI](https://github.com/s5uishida/open5gs_5gc_ueransim_snssai_upf_sample_config)
  - [SCP Indirect communication Model C](https://github.com/s5uishida/open5gs_5gc_ueransim_scp_model_c_sample_config)
  - [Monitoring Metrics with Prometheus](https://github.com/s5uishida/open5gs_5gc_ueransim_metrics_sample_config)
  - [Frame Routing](https://github.com/s5uishida/open5gs_5gc_ueransim_framed_routing_sample_config)
  - [VPP-UPF with DPDK](https://github.com/s5uishida/open5gs_5gc_ueransim_vpp_upf_dpdk_sample_config)
  - [UERANSIM with eUPF(eBPF/XDP UPF)](https://github.com/s5uishida/open5gs_5gc_ueransim_eupf_sample_config)
  - [srsRAN with eUPF(eBPF/XDP UPF)](https://github.com/s5uishida/open5gs_epc_srsran_eupf_sample_config)
 
- @gradiant helm charts
  - [Open5GS EPC and SRS LTE in kubernetes](https://gradiant.github.io/openverso-charts/open5gs-srslte.html)
  - [Open5GS NGC and UERANSIM in kubernetes](https://gradiant.github.io/openverso-charts/open5gs-ueransim-gnb.html)
  - [Open5GS NGC and OpenAirInterface GNB with ettus USRP in kubernetes](https://gradiant.github.io/openverso-charts/open5gs-oaignb.html)
  - [Open5GS EPC and SRS ENB with ettus USRP in kubernetes](https://gradiant.github.io/openverso-charts/open5gs-srsenb.html)
  - [Open5GS with Service Communication Proxy in kubernetes](https://gradiant.github.io/openverso-charts/open5gs-scp.html)
