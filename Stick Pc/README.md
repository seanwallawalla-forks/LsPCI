Most popular PCI devices in Stick Pcs
=====================================

See more info in the [README](https://github.com/linuxhw/LsPCI).

Contents
--------

1. [ PCI Devices in Stick Pcs ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Signal processing controller ](#signal-processing-controller-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | iosf_mb... | 678542F4FE |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | lpc_ich    | 678542F4FE |
| 8086:31e8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | 71480CBCC1 |
| 8086:0f00 | 1027:2014 | Intel      | Atom Processor Z36xxx/Z37... | 1     | iosf_mb... | D19C52B3FD |
| 8086:0f00 | 17aa:3646 | Intel      | Atom Processor Z36xxx/Z37... | 1     | iosf_mb... | 28B902C9B7 |
| 8086:0f1c | 17aa:3646 | Intel      | Atom Processor Z36xxx/Z37... | 1     | lpc_ich    | 28B902C9B7 |
| 8086:0f1c | 8086:0f1c | Intel      | Atom Processor Z36xxx/Z37... | 1     | lpc_ich    | D19C52B3FD |
| 8086:22c8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | pcieport   | 50585544F9 |
| 8086:31d6 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 1     | pcieport   | C9D263F2FA |
| 8086:31d7 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 1     | pcieport   | C9D263F2FA |
| 8086:31d8 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 1     | pcieport   | C9D263F2FA |
| 8086:31d9 | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 1     | pcieport   | C9D263F2FA |
| 8086:31da | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 1     | pcieport   | C9D263F2FA |
| 8086:31db | 8086:7270 | Intel      | Gemini Lake PCI Express R... | 1     | pcieport   | C9D263F2FA |
| 8086:31f0 |           | Intel      | Gemini Lake Host Bridge      | 1     |            | C9D263F2FA |
| 8086:31f0 | 8086:7270 | Intel      | Gemini Lake Host Bridge      | 1     |            | 71480CBCC1 |
| 8086:5ad6 |           | Intel      | Celeron N3350/Pentium N42... | 1     | pcieport   | 554C7240CC |
| 8086:5ad7 |           | Intel      | Celeron N3350/Pentium N42... | 1     | pcieport   | 554C7240CC |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | lpc_ich    | 554C7240CC |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 554C7240CC |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | mei_me     | 71480CBCC1 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | mei_me     | 554C7240CC |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | mei_txe    | 678542F4FE |
| 8086:0f18 | 17aa:3646 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | 28B902C9B7 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 1     | mei_txe    | D19C52B3FD |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b0 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | i915       | 678542F4FE |
| 8086:0f31 | 1027:2014 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | D19C52B3FD |
| 8086:0f31 | 17aa:3646 | Intel      | Atom Processor Z36xxx/Z37... | 1     | i915       | 28B902C9B7 |
| 8086:3185 | 1e50:8003 | Intel      | GeminiLake [UHD Graphics ... | 1     | i915       | 71480CBCC1 |
| 8086:3185 | f000:02f3 | Intel      | GeminiLake [UHD Graphics ... | 1     | i915       | C9D263F2FA |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 1     | i915       | 554C7240CC |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | r8169      | 554C7240CC |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 2     | iwlwifi    | 50585544F9 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 1     | iwlwifi    | C9D263F2FA |
| 8086:31dc | 8086:02a4 | Intel      | Gemini Lake PCH CNVi WiFi    | 1     | iwlwifi    | 71480CBCC1 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 71480CBCC1 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 2     | sdhci_pci  | 71480CBCC1 |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 554C7240CC |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | sdhci_pci  | 554C7240CC |

### Signal processing controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22dc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | process... | 678542F4FE |
| 8086:318c | 8086:318c | Intel      | Celeron/Pentium Silver Pr... | 1     | process... | 71480CBCC1 |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | proc_th... | C9D263F2FA |
| 8086:31ac | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31ae | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31b0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31b2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | intel_l... | 71480CBCC1 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 1     | process... | 554C7240CC |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | intel_l... | 554C7240CC |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | i2c_i801   | 71480CBCC1 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | i2c_i801   | 554C7240CC |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3198 | 02f3:f000 | Intel      | Celeron/Pentium Silver Pr... | 1     | snd_hda... | C9D263F2FA |
| 8086:3198 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 1     | snd_hda... | 71480CBCC1 |
| 8086:5a98 | 10ec:10fc | Intel      | Celeron N3350/Pentium N42... | 1     | snd_hda... | 554C7240CC |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | ahci       | 71480CBCC1 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     | xhci_pci   | 678542F4FE |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 2     | xhci_hcd   | 71480CBCC1 |
| 8086:0f35 | 17aa:3646 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_hcd   | 28B902C9B7 |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci_pci   | D19C52B3FD |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | xhci_hcd   | 554C7240CC |

