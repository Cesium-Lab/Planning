# Services
List of services to be run (eventually) on the network

- **Mine**
  - *KitchenInventory*
    - [Repo](https://github.com/Cesium-Lab/KitchenInventory/)
    - Backend
      - Runs a server with SQL to track inventory
      - Devices can connect over port 42000
    - Frontend
      - Runs on devices to track and view inventory
      - Several versions depending on the type of device
  - *Lights*
    - Frontend
      - Public interface for the lights on IOT subnet?
    - Backend
      - Direct interface with ESP32s for light controlling based on music
  - *Printing*
    - Wrapper for octopi instances on the network
  - *CSR (Cesium Support Rack)*
    - Services on the microcontroller-facing box
      - PyCommander (42000)
      - Telem Server (42001)
        - Search SQL telemetry
      - FizzVizz (42002)
        - Grafana maybe

- **Commercial**
  - *Glance*
    - Dashboard
    - [Repo link](https://github.com/glanceapp/glance)
  - *Proxmox*
  - *Pihole*
    - Ad-blocking
    - [Website Link](https://pi-hole.net/)
  - *Nextcloud*
    - Files
    - [Website](https://nextcloud.com/)
  - *Plex*
    - Home Assistant
    - [Website](https://www.plex.tv/)
  - *Frigate*
    - NVR Cameras
    - [Website](https://frigate.video/)
  
