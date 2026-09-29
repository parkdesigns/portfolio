# Figma Icons

[https://www.figma.com/community/file/1647268829589875241/system-design-icons-software-hardware-components](https://www.figma.com/community/file/1647268829589875241/system-design-icons-software-hardware-components)


```
ls *' '* | awk '{orig=$0; gsub(/ /, "_"); print "mv -n -- \"" orig "\" \"" $0 "\""}' | bash                                              
```

```
for file in *.svg; do
  sips -s format png "$file" -o "${file%.svg}.png" -Z 130
done
```

```
ls *.png | sed -E 's|(.*).png|    <div style="float: left; width:140px; margin-right: 10px;">\n        <img style="float: left;" alt="\1" src="./img/Figma/&" height="30px" />\n        <div style="float: left;">\n            <a href="./img/Figma/\1.svg">SVG</a>\n            <div style="font-size: 8px;">\1</div>\n        </div>\n    </div>|'
```

```
ls *.png | sed -E 's|(.*).png|    <div>\n        <img alt="\1" src="./img/Figma/&" />\n        <div>\n            <a href="./img/Figma/\1.svg">SVG</a>\n            <div class="img-title">\1</div>\n        </div>\n    </div>|'
```

## Icons

<style>
  div.icon-table {
    width: 100%;
    overflow: auto;
  }
  
  .icon-table > div {
    float: left;
    width:180px;
    margin-right: 10px;
    margin-bottom: 10px;
  }

  .icon-table div img {
    float: left;
    max-width: 50px;
    margin-right: 8px;
    max-height: 40px;
  }

  .icon-table > div > div {
    float: left;
  }

  .icon-table div.img-title  {
    font-size: 10px;
  }
</style>

<div class="icon-table">
    <div>
        <img alt="Access_Point_icon" src="./img/Figma/Access_Point_icon.png" />
        <div>
            <a href="./img/Figma/Access_Point_icon.svg">SVG</a>
            <div class="img-title">Access_Point_icon</div>
        </div>
    </div>
    <div>
        <img alt="AI_Model_icon" src="./img/Figma/AI_Model_icon.png" />
        <div>
            <a href="./img/Figma/AI_Model_icon.svg">SVG</a>
            <div class="img-title">AI_Model_icon</div>
        </div>
    </div>
    <div>
        <img alt="Alert_icon" src="./img/Figma/Alert_icon.png" />
        <div>
            <a href="./img/Figma/Alert_icon.svg">SVG</a>
            <div class="img-title">Alert_icon</div>
        </div>
    </div>
    <div>
        <img alt="Analytics_icon" src="./img/Figma/Analytics_icon.png" />
        <div>
            <a href="./img/Figma/Analytics_icon.svg">SVG</a>
            <div class="img-title">Analytics_icon</div>
        </div>
    </div>
    <div>
        <img alt="API_Gateway_icon" src="./img/Figma/API_Gateway_icon.png" />
        <div>
            <a href="./img/Figma/API_Gateway_icon.svg">SVG</a>
            <div class="img-title">API_Gateway_icon</div>
        </div>
    </div>
    <div>
        <img alt="Auth_Service_icon" src="./img/Figma/Auth_Service_icon.png" />
        <div>
            <a href="./img/Figma/Auth_Service_icon.svg">SVG</a>
            <div class="img-title">Auth_Service_icon</div>
        </div>
    </div>
    <div>
        <img alt="Bluetooth_Device_icon" src="./img/Figma/Bluetooth_Device_icon.png" />
        <div>
            <a href="./img/Figma/Bluetooth_Device_icon.svg">SVG</a>
            <div class="img-title">Bluetooth_Device_icon</div>
        </div>
    </div>
    <div>
        <img alt="Cache_icon" src="./img/Figma/Cache_icon.png" />
        <div>
            <a href="./img/Figma/Cache_icon.svg">SVG</a>
            <div class="img-title">Cache_icon</div>
        </div>
    </div>
    <div>
        <img alt="Camera_icon" src="./img/Figma/Camera_icon.png" />
        <div>
            <a href="./img/Figma/Camera_icon.svg">SVG</a>
            <div class="img-title">Camera_icon</div>
        </div>
    </div>
    <div>
        <img alt="CD_icon" src="./img/Figma/CD_icon.png" />
        <div>
            <a href="./img/Figma/CD_icon.svg">SVG</a>
            <div class="img-title">CD_icon</div>
        </div>
    </div>
    <div>
        <img alt="CDN_icon" src="./img/Figma/CDN_icon.png" />
        <div>
            <a href="./img/Figma/CDN_icon.svg">SVG</a>
            <div class="img-title">CDN_icon</div>
        </div>
    </div>
    <div>
        <img alt="Cloud_icon" src="./img/Figma/Cloud_icon.png" />
        <div>
            <a href="./img/Figma/Cloud_icon.svg">SVG</a>
            <div class="img-title">Cloud_icon</div>
        </div>
    </div>
    <div>
        <img alt="Container_icon" src="./img/Figma/Container_icon.png" />
        <div>
            <a href="./img/Figma/Container_icon.svg">SVG</a>
            <div class="img-title">Container_icon</div>
        </div>
    </div>
    <div>
        <img alt="CPU_icon" src="./img/Figma/CPU_icon.png" />
        <div>
            <a href="./img/Figma/CPU_icon.svg">SVG</a>
            <div class="img-title">CPU_icon</div>
        </div>
    </div>
    <div>
        <img alt="Database_icon" src="./img/Figma/Database_icon.png" />
        <div>
            <a href="./img/Figma/Database_icon.svg">SVG</a>
            <div class="img-title">Database_icon</div>
        </div>
    </div>
    <div>
        <img alt="Desktop_PC_icon" src="./img/Figma/Desktop_PC_icon.png" />
        <div>
            <a href="./img/Figma/Desktop_PC_icon.svg">SVG</a>
            <div class="img-title">Desktop_PC_icon</div>
        </div>
    </div>
    <div>
        <img alt="DNS_icon" src="./img/Figma/DNS_icon.png" />
        <div>
            <a href="./img/Figma/DNS_icon.svg">SVG</a>
            <div class="img-title">DNS_icon</div>
        </div>
    </div>
    <div>
        <img alt="Drone_icon" src="./img/Figma/Drone_icon.png" />
        <div>
            <a href="./img/Figma/Drone_icon.svg">SVG</a>
            <div class="img-title">Drone_icon</div>
        </div>
    </div>
    <div>
        <img alt="Email_Service_icon" src="./img/Figma/Email_Service_icon.png" />
        <div>
            <a href="./img/Figma/Email_Service_icon.svg">SVG</a>
            <div class="img-title">Email_Service_icon</div>
        </div>
    </div>
    <div>
        <img alt="Ethernet_Cable_icon" src="./img/Figma/Ethernet_Cable_icon.png" />
        <div>
            <a href="./img/Figma/Ethernet_Cable_icon.svg">SVG</a>
            <div class="img-title">Ethernet_Cable_icon</div>
        </div>
    </div>
    <div>
        <img alt="Firewall_icon" src="./img/Figma/Firewall_icon.png" />
        <div>
            <a href="./img/Figma/Firewall_icon.svg">SVG</a>
            <div class="img-title">Firewall_icon</div>
        </div>
    </div>
    <div>
        <img alt="Function_icon" src="./img/Figma/Function_icon.png" />
        <div>
            <a href="./img/Figma/Function_icon.svg">SVG</a>
            <div class="img-title">Function_icon</div>
        </div>
    </div>
    <div>
        <img alt="Git_Repo_icon" src="./img/Figma/Git_Repo_icon.png" />
        <div>
            <a href="./img/Figma/Git_Repo_icon.svg">SVG</a>
            <div class="img-title">Git_Repo_icon</div>
        </div>
    </div>
    <div>
        <img alt="GPS_Module_icon" src="./img/Figma/GPS_Module_icon.png" />
        <div>
            <a href="./img/Figma/GPS_Module_icon.svg">SVG</a>
            <div class="img-title">GPS_Module_icon</div>
        </div>
    </div>
    <div>
        <img alt="GPU_icon" src="./img/Figma/GPU_icon.png" />
        <div>
            <a href="./img/Figma/GPU_icon.svg">SVG</a>
            <div class="img-title">GPU_icon</div>
        </div>
    </div>
    <div>
        <img alt="Hard_Drive_icon" src="./img/Figma/Hard_Drive_icon.png" />
        <div>
            <a href="./img/Figma/Hard_Drive_icon.svg">SVG</a>
            <div class="img-title">Hard_Drive_icon</div>
        </div>
    </div>
    <div>
        <img alt="IoT_Sensor_icon" src="./img/Figma/IoT_Sensor_icon.png" />
        <div>
            <a href="./img/Figma/IoT_Sensor_icon.svg">SVG</a>
            <div class="img-title">IoT_Sensor_icon</div>
        </div>
    </div>
    <div>
        <img alt="Keyboard_icon" src="./img/Figma/Keyboard_icon.png" />
        <div>
            <a href="./img/Figma/Keyboard_icon.svg">SVG</a>
            <div class="img-title">Keyboard_icon</div>
        </div>
    </div>
    <div>
        <img alt="Kubernetes_icon" src="./img/Figma/Kubernetes_icon.png" />
        <div>
            <a href="./img/Figma/Kubernetes_icon.svg">SVG</a>
            <div class="img-title">Kubernetes_icon</div>
        </div>
    </div>
    <div>
        <img alt="Laptop_icon" src="./img/Figma/Laptop_icon.png" />
        <div>
            <a href="./img/Figma/Laptop_icon.svg">SVG</a>
            <div class="img-title">Laptop_icon</div>
        </div>
    </div>
    <div>
        <img alt="Load_Balancer_icon" src="./img/Figma/Load_Balancer_icon.png" />
        <div>
            <a href="./img/Figma/Load_Balancer_icon.svg">SVG</a>
            <div class="img-title">Load_Balancer_icon</div>
        </div>
    </div>
    <div>
        <img alt="Logging_icon" src="./img/Figma/Logging_icon.png" />
        <div>
            <a href="./img/Figma/Logging_icon.svg">SVG</a>
            <div class="img-title">Logging_icon</div>
        </div>
    </div>
    <div>
        <img alt="Message_Queue_icon" src="./img/Figma/Message_Queue_icon.png" />
        <div>
            <a href="./img/Figma/Message_Queue_icon.svg">SVG</a>
            <div class="img-title">Message_Queue_icon</div>
        </div>
    </div>
    <div>
        <img alt="Microservice_icon" src="./img/Figma/Microservice_icon.png" />
        <div>
            <a href="./img/Figma/Microservice_icon.svg">SVG</a>
            <div class="img-title">Microservice_icon</div>
        </div>
    </div>
    <div>
        <img alt="Modem_icon" src="./img/Figma/Modem_icon.png" />
        <div>
            <a href="./img/Figma/Modem_icon.svg">SVG</a>
            <div class="img-title">Modem_icon</div>
        </div>
    </div>
    <div>
        <img alt="Monitor_icon" src="./img/Figma/Monitor_icon.png" />
        <div>
            <a href="./img/Figma/Monitor_icon.svg">SVG</a>
            <div class="img-title">Monitor_icon</div>
        </div>
    </div>
    <div>
        <img alt="Monitoring_icon" src="./img/Figma/Monitoring_icon.png" />
        <div>
            <a href="./img/Figma/Monitoring_icon.svg">SVG</a>
            <div class="img-title">Monitoring_icon</div>
        </div>
    </div>
    <div>
        <img alt="Mouse_icon" src="./img/Figma/Mouse_icon.png" />
        <div>
            <a href="./img/Figma/Mouse_icon.svg">SVG</a>
            <div class="img-title">Mouse_icon</div>
        </div>
    </div>
    <div>
        <img alt="NAS_icon" src="./img/Figma/NAS_icon.png" />
        <div>
            <a href="./img/Figma/NAS_icon.svg">SVG</a>
            <div class="img-title">NAS_icon</div>
        </div>
    </div>
    <div>
        <img alt="Network_Switch_icon" src="./img/Figma/Network_Switch_icon.png" />
        <div>
            <a href="./img/Figma/Network_Switch_icon.svg">SVG</a>
            <div class="img-title">Network_Switch_icon</div>
        </div>
    </div>
    <div>
        <img alt="Notification_icon" src="./img/Figma/Notification_icon.png" />
        <div>
            <a href="./img/Figma/Notification_icon.svg">SVG</a>
            <div class="img-title">Notification_icon</div>
        </div>
    </div>
    <div>
        <img alt="Payment_icon" src="./img/Figma/Payment_icon.png" />
        <div>
            <a href="./img/Figma/Payment_icon.svg">SVG</a>
            <div class="img-title">Payment_icon</div>
        </div>
    </div>
    <div>
        <img alt="Power_Supply_icon" src="./img/Figma/Power_Supply_icon.png" />
        <div>
            <a href="./img/Figma/Power_Supply_icon.svg">SVG</a>
            <div class="img-title">Power_Supply_icon</div>
        </div>
    </div>
    <div>
        <img alt="Printer_icon" src="./img/Figma/Printer_icon.png" />
        <div>
            <a href="./img/Figma/Printer_icon.svg">SVG</a>
            <div class="img-title">Printer_icon</div>
        </div>
    </div>
    <div>
        <img alt="RAM_icon" src="./img/Figma/RAM_icon.png" />
        <div>
            <a href="./img/Figma/RAM_icon.svg">SVG</a>
            <div class="img-title">RAM_icon</div>
        </div>
    </div>
    <div>
        <img alt="Raspberry_Pi_icon" src="./img/Figma/Raspberry_Pi_icon.png" />
        <div>
            <a href="./img/Figma/Raspberry_Pi_icon.svg">SVG</a>
            <div class="img-title">Raspberry_Pi_icon</div>
        </div>
    </div>
    <div>
        <img alt="Router_icon" src="./img/Figma/Router_icon.png" />
        <div>
            <a href="./img/Figma/Router_icon.svg">SVG</a>
            <div class="img-title">Router_icon</div>
        </div>
    </div>
    <div>
        <img alt="Scheduler_icon" src="./img/Figma/Scheduler_icon.png" />
        <div>
            <a href="./img/Figma/Scheduler_icon.svg">SVG</a>
            <div class="img-title">Scheduler_icon</div>
        </div>
    </div>
    <div>
        <img alt="Search_icon" src="./img/Figma/Search_icon.png" />
        <div>
            <a href="./img/Figma/Search_icon.svg">SVG</a>
            <div class="img-title">Search_icon</div>
        </div>
    </div>
    <div>
        <img alt="Server_icon" src="./img/Figma/Server_icon.png" />
        <div>
            <a href="./img/Figma/Server_icon.svg">SVG</a>
            <div class="img-title">Server_icon</div>
        </div>
    </div>
    <div>
        <img alt="Server_Rack_icon" src="./img/Figma/Server_Rack_icon.png" />
        <div>
            <a href="./img/Figma/Server_Rack_icon.svg">SVG</a>
            <div class="img-title">Server_Rack_icon</div>
        </div>
    </div>
    <div>
        <img alt="Service_Mesh_icon" src="./img/Figma/Service_Mesh_icon.png" />
        <div>
            <a href="./img/Figma/Service_Mesh_icon.svg">SVG</a>
            <div class="img-title">Service_Mesh_icon</div>
        </div>
    </div>
    <div>
        <img alt="Smartphone_icon" src="./img/Figma/Smartphone_icon.png" />
        <div>
            <a href="./img/Figma/Smartphone_icon.svg">SVG</a>
            <div class="img-title">Smartphone_icon</div>
        </div>
    </div>
    <div>
        <img alt="Smartwatch_icon" src="./img/Figma/Smartwatch_icon.png" />
        <div>
            <a href="./img/Figma/Smartwatch_icon.svg">SVG</a>
            <div class="img-title">Smartwatch_icon</div>
        </div>
    </div>
    <div>
        <img alt="SSD_icon" src="./img/Figma/SSD_icon.png" />
        <div>
            <a href="./img/Figma/SSD_icon.svg">SVG</a>
            <div class="img-title">SSD_icon</div>
        </div>
    </div>
    <div>
        <img alt="Storage_Bucket_icon" src="./img/Figma/Storage_Bucket_icon.png" />
        <div>
            <a href="./img/Figma/Storage_Bucket_icon.svg">SVG</a>
            <div class="img-title">Storage_Bucket_icon</div>
        </div>
    </div>
    <div>
        <img alt="Tablet_icon" src="./img/Figma/Tablet_icon.png" />
        <div>
            <a href="./img/Figma/Tablet_icon.svg">SVG</a>
            <div class="img-title">Tablet_icon</div>
        </div>
    </div>
    <div>
        <img alt="USB_Stick_icon" src="./img/Figma/USB_Stick_icon.png" />
        <div>
            <a href="./img/Figma/USB_Stick_icon.svg">SVG</a>
            <div class="img-title">USB_Stick_icon</div>
        </div>
    </div>
    <div>
        <img alt="User_Group_icon" src="./img/Figma/User_Group_icon.png" />
        <div>
            <a href="./img/Figma/User_Group_icon.svg">SVG</a>
            <div class="img-title">User_Group_icon</div>
        </div>
    </div>
    <div>
        <img alt="User_icon" src="./img/Figma/User_icon.png" />
        <div>
            <a href="./img/Figma/User_icon.svg">SVG</a>
            <div class="img-title">User_icon</div>
        </div>
    </div>
    <div>
        <img alt="VPN_icon" src="./img/Figma/VPN_icon.png" />
        <div>
            <a href="./img/Figma/VPN_icon.svg">SVG</a>
            <div class="img-title">VPN_icon</div>
        </div>
    </div>
    <div>
        <img alt="Web_App_icon" src="./img/Figma/Web_App_icon.png" />
        <div>
            <a href="./img/Figma/Web_App_icon.svg">SVG</a>
            <div class="img-title">Web_App_icon</div>
        </div>
    </div>
    <div>
        <img alt="Webcam_icon" src="./img/Figma/Webcam_icon.png" />
        <div>
            <a href="./img/Figma/Webcam_icon.svg">SVG</a>
            <div class="img-title">Webcam_icon</div>
        </div>
    </div>
</div>
