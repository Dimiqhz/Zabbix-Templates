# My Zabbix Templates

This repository contains custom **Zabbix monitoring templates** for different systems and hardware.  
All templates are written in **YAML** format and can be imported into Zabbix 7.x directly.

---

## 📂 Templates

- [ESXi HP SmartArray](./esxi_smartarray/README.md)  
  Monitor HP SmartArray RAID controllers, CPU, memory, physical and logical disks on ESXi hosts.  
  Includes: dependent items, discovery rules, triggers, graphs, dashboards.


---

## 🚀 Usage

1. Open **Zabbix Web UI** → *Configuration → Templates*.  
2. Click **Import** and upload the corresponding `template.yaml`.  
3. Link the template to the target host.  
4. Optionally review triggers/macros and adjust to your environment.


---

## ⚠️ Disclaimer

These templates are provided "as is", without any guarantees, however, I have a desire to support the templates and complement their functionality, so you can suggest your ideas in the "issues" section.  
They were created for internal use and may require adjustments depending on your hardware, operating system, or Zabbix version.  

Feel free to make changes, suggest ideas, and help improve — contributions are welcome.🚀

---

**Author:** *Dimiqhz*  
**License:** MIT
