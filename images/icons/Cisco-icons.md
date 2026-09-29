# Cisco Icons

[https://www.cisco.com/c/en/us/about/brand-center/network-topology-icons.html](https://www.cisco.com/c/en/us/about/brand-center/network-topology-icons.html)


## Cisco Network Topology Icons

```
brew install ghostscript pstoedit
```

```
for file in *.eps; do
  pstoedit -f svg "$file" "${file%.eps}.svg"
done
```

```
for file in *.svg; do
  sips -s format png "$file" -o "${file%.svg}.png" -Z 130
done
```

```
ls -1 | sed -E 's|(.*).png|<img alt="\1" src="./img/Cisco/Network-Topology/&" height="30px" />  \1 \[SVG\]\(./img/Cisco/Network-Topology/\1.svg\)<br />|'
```

```
ls *.png | sed -E 's|(.*).png|    <div>\n        <img alt="\1" src="./img/Cisco/Network-Topology/&" />\n        <div>\n            <a href="./img/Cisco/Network-Topology/\1.svg">SVG</a>\n            <div class="img-title">\1</div>\n        </div>\n    </div>|'
```

<style>
  .icon-table > div {
    float: left;
    width:210px;
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
    font-size: 8px;
  }
</style>

## Network Topology

<div class="icon-table">
    <div>
        <img alt="100baset_hub" src="./img/Cisco/Network-Topology/100baset_hub.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/100baset_hub.svg">SVG</a>
            <div class="img-title">100baset_hub</div>
        </div>
    </div>
    <div>
        <img alt="10700" src="./img/Cisco/Network-Topology/10700.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/10700.svg">SVG</a>
            <div class="img-title">10700</div>
        </div>
    </div>
    <div>
        <img alt="10GE_FCoE" src="./img/Cisco/Network-Topology/10GE_FCoE.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/10GE_FCoE.svg">SVG</a>
            <div class="img-title">10GE_FCoE</div>
        </div>
    </div>
    <div>
        <img alt="15200" src="./img/Cisco/Network-Topology/15200.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/15200.svg">SVG</a>
            <div class="img-title">15200</div>
        </div>
    </div>
    <div>
        <img alt="3174_(desktop)" src="./img/Cisco/Network-Topology/3174_(desktop).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/3174_(desktop).svg">SVG</a>
            <div class="img-title">3174_(desktop)</div>
        </div>
    </div>
    <div>
        <img alt="3200_mobile_access_router" src="./img/Cisco/Network-Topology/3200_mobile_access_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/3200_mobile_access_router.svg">SVG</a>
            <div class="img-title">3200_mobile_access_router</div>
        </div>
    </div>
    <div>
        <img alt="3x74_(floor)" src="./img/Cisco/Network-Topology/3x74_(floor).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/3x74_(floor).svg">SVG</a>
            <div class="img-title">3x74_(floor)</div>
        </div>
    </div>
    <div>
        <img alt="6700_series" src="./img/Cisco/Network-Topology/6700_series.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/6700_series.svg">SVG</a>
            <div class="img-title">6700_series</div>
        </div>
    </div>
    <div>
        <img alt="7500ars_(7513)" src="./img/Cisco/Network-Topology/7500ars_(7513).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/7500ars_(7513).svg">SVG</a>
            <div class="img-title">7500ars_(7513)</div>
        </div>
    </div>
    <div>
        <img alt="access_gateway" src="./img/Cisco/Network-Topology/access_gateway.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/access_gateway.svg">SVG</a>
            <div class="img-title">access_gateway</div>
        </div>
    </div>
    <div>
        <img alt="accesspoint" src="./img/Cisco/Network-Topology/accesspoint.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/accesspoint.svg">SVG</a>
            <div class="img-title">accesspoint</div>
        </div>
    </div>
    <div>
        <img alt="ace" src="./img/Cisco/Network-Topology/ace.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ace.svg">SVG</a>
            <div class="img-title">ace</div>
        </div>
    </div>
    <div>
        <img alt="ACS" src="./img/Cisco/Network-Topology/ACS.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ACS.svg">SVG</a>
            <div class="img-title">ACS</div>
        </div>
    </div>
    <div>
        <img alt="adm" src="./img/Cisco/Network-Topology/adm.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/adm.svg">SVG</a>
            <div class="img-title">adm</div>
        </div>
    </div>
    <div>
        <img alt="androgenous_person" src="./img/Cisco/Network-Topology/androgenous_person.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/androgenous_person.svg">SVG</a>
            <div class="img-title">androgenous_person</div>
        </div>
    </div>
    <div>
        <img alt="antenna" src="./img/Cisco/Network-Topology/antenna.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/antenna.svg">SVG</a>
            <div class="img-title">antenna</div>
        </div>
    </div>
    <div>
        <img alt="asic_processor" src="./img/Cisco/Network-Topology/asic_processor.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/asic_processor.svg">SVG</a>
            <div class="img-title">asic_processor</div>
        </div>
    </div>
    <div>
        <img alt="ASR_1000_Series" src="./img/Cisco/Network-Topology/ASR_1000_Series.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ASR_1000_Series.svg">SVG</a>
            <div class="img-title">ASR_1000_Series</div>
        </div>
    </div>
    <div>
        <img alt="ata" src="./img/Cisco/Network-Topology/ata.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ata.svg">SVG</a>
            <div class="img-title">ata</div>
        </div>
    </div>
    <div>
        <img alt="atm_3800" src="./img/Cisco/Network-Topology/atm_3800.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/atm_3800.svg">SVG</a>
            <div class="img-title">atm_3800</div>
        </div>
    </div>
    <div>
        <img alt="atm_fast_gigabit_etherswitch" src="./img/Cisco/Network-Topology/atm_fast_gigabit_etherswitch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/atm_fast_gigabit_etherswitch.svg">SVG</a>
            <div class="img-title">atm_fast_gigabit_etherswitch</div>
        </div>
    </div>
    <div>
        <img alt="atm_router" src="./img/Cisco/Network-Topology/atm_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/atm_router.svg">SVG</a>
            <div class="img-title">atm_router</div>
        </div>
    </div>
    <div>
        <img alt="atm_switch" src="./img/Cisco/Network-Topology/atm_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/atm_switch.svg">SVG</a>
            <div class="img-title">atm_switch</div>
        </div>
    </div>
    <div>
        <img alt="atm_tag_switch_router" src="./img/Cisco/Network-Topology/atm_tag_switch_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/atm_tag_switch_router.svg">SVG</a>
            <div class="img-title">atm_tag_switch_router</div>
        </div>
    </div>
    <div>
        <img alt="avs" src="./img/Cisco/Network-Topology/avs.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/avs.svg">SVG</a>
            <div class="img-title">avs</div>
        </div>
    </div>
    <div>
        <img alt="AXP" src="./img/Cisco/Network-Topology/AXP.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/AXP.svg">SVG</a>
            <div class="img-title">AXP</div>
        </div>
    </div>
    <div>
        <img alt="bbfw_media" src="./img/Cisco/Network-Topology/bbfw_media.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/bbfw_media.svg">SVG</a>
            <div class="img-title">bbfw_media</div>
        </div>
    </div>
    <div>
        <img alt="bbfw" src="./img/Cisco/Network-Topology/bbfw.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/bbfw.svg">SVG</a>
            <div class="img-title">bbfw</div>
        </div>
    </div>
    <div>
        <img alt="bbsm" src="./img/Cisco/Network-Topology/bbsm.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/bbsm.svg">SVG</a>
            <div class="img-title">bbsm</div>
        </div>
    </div>
    <div>
        <img alt="branch_office" src="./img/Cisco/Network-Topology/branch_office.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/branch_office.svg">SVG</a>
            <div class="img-title">branch_office</div>
        </div>
    </div>
    <div>
        <img alt="breakout_box" src="./img/Cisco/Network-Topology/breakout_box.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/breakout_box.svg">SVG</a>
            <div class="img-title">breakout_box</div>
        </div>
    </div>
    <div>
        <img alt="bridge" src="./img/Cisco/Network-Topology/bridge.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/bridge.svg">SVG</a>
            <div class="img-title">bridge</div>
        </div>
    </div>
    <div>
        <img alt="broadband_router" src="./img/Cisco/Network-Topology/broadband_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/broadband_router.svg">SVG</a>
            <div class="img-title">broadband_router</div>
        </div>
    </div>
    <div>
        <img alt="bts_10200" src="./img/Cisco/Network-Topology/bts_10200.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/bts_10200.svg">SVG</a>
            <div class="img-title">bts_10200</div>
        </div>
    </div>
    <div>
        <img alt="cable_modem" src="./img/Cisco/Network-Topology/cable_modem.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cable_modem.svg">SVG</a>
            <div class="img-title">cable_modem</div>
        </div>
    </div>
    <div>
        <img alt="callmanager" src="./img/Cisco/Network-Topology/callmanager.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/callmanager.svg">SVG</a>
            <div class="img-title">callmanager</div>
        </div>
    </div>
    <div>
        <img alt="car_(1)" src="./img/Cisco/Network-Topology/car_(1).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/car_(1).svg">SVG</a>
            <div class="img-title">car_(1)</div>
        </div>
    </div>
    <div>
        <img alt="car" src="./img/Cisco/Network-Topology/car.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/car.svg">SVG</a>
            <div class="img-title">car</div>
        </div>
    </div>
    <div>
        <img alt="carrier_routing_system" src="./img/Cisco/Network-Topology/carrier_routing_system.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/carrier_routing_system.svg">SVG</a>
            <div class="img-title">carrier_routing_system</div>
        </div>
    </div>
    <div>
        <img alt="cddi-fddi" src="./img/Cisco/Network-Topology/cddi-fddi.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cddi-fddi.svg">SVG</a>
            <div class="img-title">cddi-fddi</div>
        </div>
    </div>
    <div>
        <img alt="cdm" src="./img/Cisco/Network-Topology/cdm.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cdm.svg">SVG</a>
            <div class="img-title">cdm</div>
        </div>
    </div>
    <div>
        <img alt="cellular_phone" src="./img/Cisco/Network-Topology/cellular_phone.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cellular_phone.svg">SVG</a>
            <div class="img-title">cellular_phone</div>
        </div>
    </div>
    <div>
        <img alt="centri_firewall" src="./img/Cisco/Network-Topology/centri_firewall.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/centri_firewall.svg">SVG</a>
            <div class="img-title">centri_firewall</div>
        </div>
    </div>
    <div>
        <img alt="cisco_1000" src="./img/Cisco/Network-Topology/cisco_1000.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cisco_1000.svg">SVG</a>
            <div class="img-title">cisco_1000</div>
        </div>
    </div>
    <div>
        <img alt="cisco_asa_5500" src="./img/Cisco/Network-Topology/cisco_asa_5500.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cisco_asa_5500.svg">SVG</a>
            <div class="img-title">cisco_asa_5500</div>
        </div>
    </div>
    <div>
        <img alt="cisco_ca" src="./img/Cisco/Network-Topology/cisco_ca.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cisco_ca.svg">SVG</a>
            <div class="img-title">cisco_ca</div>
        </div>
    </div>
    <div>
        <img alt="cisco_file_engine" src="./img/Cisco/Network-Topology/cisco_file_engine.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cisco_file_engine.svg">SVG</a>
            <div class="img-title">cisco_file_engine</div>
        </div>
    </div>
    <div>
        <img alt="cisco_hub" src="./img/Cisco/Network-Topology/cisco_hub.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cisco_hub.svg">SVG</a>
            <div class="img-title">cisco_hub</div>
        </div>
    </div>
    <div>
        <img alt="cisco_unified_presence_server" src="./img/Cisco/Network-Topology/cisco_unified_presence_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cisco_unified_presence_server.svg">SVG</a>
            <div class="img-title">cisco_unified_presence_server</div>
        </div>
    </div>
    <div>
        <img alt="cisco_unityexpress" src="./img/Cisco/Network-Topology/cisco_unityexpress.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cisco_unityexpress.svg">SVG</a>
            <div class="img-title">cisco_unityexpress</div>
        </div>
    </div>
    <div>
        <img alt="ciscosecurity" src="./img/Cisco/Network-Topology/ciscosecurity.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ciscosecurity.svg">SVG</a>
            <div class="img-title">ciscosecurity</div>
        </div>
    </div>
    <div>
        <img alt="ciscoworks" src="./img/Cisco/Network-Topology/ciscoworks.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ciscoworks.svg">SVG</a>
            <div class="img-title">ciscoworks</div>
        </div>
    </div>
    <div>
        <img alt="class_4_5_switch" src="./img/Cisco/Network-Topology/class_4_5_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/class_4_5_switch.svg">SVG</a>
            <div class="img-title">class_4_5_switch</div>
        </div>
    </div>
    <div>
        <img alt="cloud" src="./img/Cisco/Network-Topology/cloud.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cloud.svg">SVG</a>
            <div class="img-title">cloud</div>
        </div>
    </div>
    <div>
        <img alt="communications_server" src="./img/Cisco/Network-Topology/communications_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/communications_server.svg">SVG</a>
            <div class="img-title">communications_server</div>
        </div>
    </div>
    <div>
        <img alt="contact_center" src="./img/Cisco/Network-Topology/contact_center.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/contact_center.svg">SVG</a>
            <div class="img-title">contact_center</div>
        </div>
    </div>
    <div>
        <img alt="content_engine_(cache_director)" src="./img/Cisco/Network-Topology/content_engine_(cache_director).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/content_engine_(cache_director).svg">SVG</a>
            <div class="img-title">content_engine_(cache_director)</div>
        </div>
    </div>
    <div>
        <img alt="content_service_router" src="./img/Cisco/Network-Topology/content_service_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/content_service_router.svg">SVG</a>
            <div class="img-title">content_service_router</div>
        </div>
    </div>
    <div>
        <img alt="content_service_switch_1100" src="./img/Cisco/Network-Topology/content_service_switch_1100.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/content_service_switch_1100.svg">SVG</a>
            <div class="img-title">content_service_switch_1100</div>
        </div>
    </div>
    <div>
        <img alt="content_switch_module" src="./img/Cisco/Network-Topology/content_switch_module.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/content_switch_module.svg">SVG</a>
            <div class="img-title">content_switch_module</div>
        </div>
    </div>
    <div>
        <img alt="content_switch" src="./img/Cisco/Network-Topology/content_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/content_switch.svg">SVG</a>
            <div class="img-title">content_switch</div>
        </div>
    </div>
    <div>
        <img alt="content_transformation_engine_(cte)" src="./img/Cisco/Network-Topology/content_transformation_engine_(cte).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/content_transformation_engine_(cte).svg">SVG</a>
            <div class="img-title">content_transformation_engine_(cte)</div>
        </div>
    </div>
    <div>
        <img alt="cs-mars" src="./img/Cisco/Network-Topology/cs-mars.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/cs-mars.svg">SVG</a>
            <div class="img-title">cs-mars</div>
        </div>
    </div>
    <div>
        <img alt="csm-s" src="./img/Cisco/Network-Topology/csm-s.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/csm-s.svg">SVG</a>
            <div class="img-title">csm-s</div>
        </div>
    </div>
    <div>
        <img alt="csu_dsu" src="./img/Cisco/Network-Topology/csu_dsu.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/csu_dsu.svg">SVG</a>
            <div class="img-title">csu_dsu</div>
        </div>
    </div>
    <div>
        <img alt="CUBE" src="./img/Cisco/Network-Topology/CUBE.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/CUBE.svg">SVG</a>
            <div class="img-title">CUBE</div>
        </div>
    </div>
    <div>
        <img alt="detector" src="./img/Cisco/Network-Topology/detector.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/detector.svg">SVG</a>
            <div class="img-title">detector</div>
        </div>
    </div>
    <div>
        <img alt="director-class_fibre_channel_director" src="./img/Cisco/Network-Topology/director-class_fibre_channel_director.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/director-class_fibre_channel_director.svg">SVG</a>
            <div class="img-title">director-class_fibre_channel_director</div>
        </div>
    </div>
    <div>
        <img alt="directory_server" src="./img/Cisco/Network-Topology/directory_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/directory_server.svg">SVG</a>
            <div class="img-title">directory_server</div>
        </div>
    </div>
    <div>
        <img alt="diskette" src="./img/Cisco/Network-Topology/diskette.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/diskette.svg">SVG</a>
            <div class="img-title">diskette</div>
        </div>
    </div>
    <div>
        <img alt="distributed_director" src="./img/Cisco/Network-Topology/distributed_director.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/distributed_director.svg">SVG</a>
            <div class="img-title">distributed_director</div>
        </div>
    </div>
    <div>
        <img alt="dot-dot" src="./img/Cisco/Network-Topology/dot-dot.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/dot-dot.svg">SVG</a>
            <div class="img-title">dot-dot</div>
        </div>
    </div>
    <div>
        <img alt="dpt" src="./img/Cisco/Network-Topology/dpt.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/dpt.svg">SVG</a>
            <div class="img-title">dpt</div>
        </div>
    </div>
    <div>
        <img alt="dslam" src="./img/Cisco/Network-Topology/dslam.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/dslam.svg">SVG</a>
            <div class="img-title">dslam</div>
        </div>
    </div>
    <div>
        <img alt="dual_mode_ap" src="./img/Cisco/Network-Topology/dual_mode_ap.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/dual_mode_ap.svg">SVG</a>
            <div class="img-title">dual_mode_ap</div>
        </div>
    </div>
    <div>
        <img alt="dwdm_filter" src="./img/Cisco/Network-Topology/dwdm_filter.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/dwdm_filter.svg">SVG</a>
            <div class="img-title">dwdm_filter</div>
        </div>
    </div>
    <div>
        <img alt="end_office" src="./img/Cisco/Network-Topology/end_office.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/end_office.svg">SVG</a>
            <div class="img-title">end_office</div>
        </div>
    </div>
    <div>
        <img alt="fax" src="./img/Cisco/Network-Topology/fax.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/fax.svg">SVG</a>
            <div class="img-title">fax</div>
        </div>
    </div>
    <div>
        <img alt="fc_storage" src="./img/Cisco/Network-Topology/fc_storage.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/fc_storage.svg">SVG</a>
            <div class="img-title">fc_storage</div>
        </div>
    </div>
    <div>
        <img alt="fddi_ring" src="./img/Cisco/Network-Topology/fddi_ring.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/fddi_ring.svg">SVG</a>
            <div class="img-title">fddi_ring</div>
        </div>
    </div>
    <div>
        <img alt="fibre_channel_disk_subsystem" src="./img/Cisco/Network-Topology/fibre_channel_disk_subsystem.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/fibre_channel_disk_subsystem.svg">SVG</a>
            <div class="img-title">fibre_channel_disk_subsystem</div>
        </div>
    </div>
    <div>
        <img alt="fibre_channel_fabric_switch" src="./img/Cisco/Network-Topology/fibre_channel_fabric_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/fibre_channel_fabric_switch.svg">SVG</a>
            <div class="img-title">fibre_channel_fabric_switch</div>
        </div>
    </div>
    <div>
        <img alt="file_cabinet" src="./img/Cisco/Network-Topology/file_cabinet.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/file_cabinet.svg">SVG</a>
            <div class="img-title">file_cabinet</div>
        </div>
    </div>
    <div>
        <img alt="file_server" src="./img/Cisco/Network-Topology/file_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/file_server.svg">SVG</a>
            <div class="img-title">file_server</div>
        </div>
    </div>
    <div>
        <img alt="fileserver" src="./img/Cisco/Network-Topology/fileserver.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/fileserver.svg">SVG</a>
            <div class="img-title">fileserver</div>
        </div>
    </div>
    <div>
        <img alt="firewall_service_module_(fwsm)" src="./img/Cisco/Network-Topology/firewall_service_module_(fwsm).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/firewall_service_module_(fwsm).svg">SVG</a>
            <div class="img-title">firewall_service_module_(fwsm)</div>
        </div>
    </div>
    <div>
        <img alt="firewall" src="./img/Cisco/Network-Topology/firewall.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/firewall.svg">SVG</a>
            <div class="img-title">firewall</div>
        </div>
    </div>
    <div>
        <img alt="front_end_processor" src="./img/Cisco/Network-Topology/front_end_processor.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/front_end_processor.svg">SVG</a>
            <div class="img-title">front_end_processor</div>
        </div>
    </div>
    <div>
        <img alt="gatekeeper" src="./img/Cisco/Network-Topology/gatekeeper.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/gatekeeper.svg">SVG</a>
            <div class="img-title">gatekeeper</div>
        </div>
    </div>
    <div>
        <img alt="general_applicance" src="./img/Cisco/Network-Topology/general_applicance.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/general_applicance.svg">SVG</a>
            <div class="img-title">general_applicance</div>
        </div>
    </div>
    <div>
        <img alt="generic_building" src="./img/Cisco/Network-Topology/generic_building.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/generic_building.svg">SVG</a>
            <div class="img-title">generic_building</div>
        </div>
    </div>
    <div>
        <img alt="generic_gateway" src="./img/Cisco/Network-Topology/generic_gateway.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/generic_gateway.svg">SVG</a>
            <div class="img-title">generic_gateway</div>
        </div>
    </div>
    <div>
        <img alt="generic_processor" src="./img/Cisco/Network-Topology/generic_processor.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/generic_processor.svg">SVG</a>
            <div class="img-title">generic_processor</div>
        </div>
    </div>
    <div>
        <img alt="generic_softswitch" src="./img/Cisco/Network-Topology/generic_softswitch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/generic_softswitch.svg">SVG</a>
            <div class="img-title">generic_softswitch</div>
        </div>
    </div>
    <div>
        <img alt="gigabit_switch_atm_tag_router" src="./img/Cisco/Network-Topology/gigabit_switch_atm_tag_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/gigabit_switch_atm_tag_router.svg">SVG</a>
            <div class="img-title">gigabit_switch_atm_tag_router</div>
        </div>
    </div>
    <div>
        <img alt="government_building" src="./img/Cisco/Network-Topology/government_building.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/government_building.svg">SVG</a>
            <div class="img-title">government_building</div>
        </div>
    </div>
    <div>
        <img alt="Ground_terminal" src="./img/Cisco/Network-Topology/Ground_terminal.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Ground_terminal.svg">SVG</a>
            <div class="img-title">Ground_terminal</div>
        </div>
    </div>
    <div>
        <img alt="guard" src="./img/Cisco/Network-Topology/guard.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/guard.svg">SVG</a>
            <div class="img-title">guard</div>
        </div>
    </div>
    <div>
        <img alt="h.323" src="./img/Cisco/Network-Topology/h.323.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/h.323.svg">SVG</a>
            <div class="img-title">h.323</div>
        </div>
    </div>
    <div>
        <img alt="handheld" src="./img/Cisco/Network-Topology/handheld.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/handheld.svg">SVG</a>
            <div class="img-title">handheld</div>
        </div>
    </div>
    <div>
        <img alt="hootphone" src="./img/Cisco/Network-Topology/hootphone.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/hootphone.svg">SVG</a>
            <div class="img-title">hootphone</div>
        </div>
    </div>
    <div>
        <img alt="host" src="./img/Cisco/Network-Topology/host.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/host.svg">SVG</a>
            <div class="img-title">host</div>
        </div>
    </div>
    <div>
        <img alt="hp_mini" src="./img/Cisco/Network-Topology/hp_mini.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/hp_mini.svg">SVG</a>
            <div class="img-title">hp_mini</div>
        </div>
    </div>
    <div>
        <img alt="hub" src="./img/Cisco/Network-Topology/hub.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/hub.svg">SVG</a>
            <div class="img-title">hub</div>
        </div>
    </div>
    <div>
        <img alt="iad_router" src="./img/Cisco/Network-Topology/iad_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/iad_router.svg">SVG</a>
            <div class="img-title">iad_router</div>
        </div>
    </div>
    <div>
        <img alt="ibm_mainframe" src="./img/Cisco/Network-Topology/ibm_mainframe.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ibm_mainframe.svg">SVG</a>
            <div class="img-title">ibm_mainframe</div>
        </div>
    </div>
    <div>
        <img alt="ibm_mini_as400" src="./img/Cisco/Network-Topology/ibm_mini_as400.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ibm_mini_as400.svg">SVG</a>
            <div class="img-title">ibm_mini_as400</div>
        </div>
    </div>
    <div>
        <img alt="ibm_tower" src="./img/Cisco/Network-Topology/ibm_tower.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ibm_tower.svg">SVG</a>
            <div class="img-title">ibm_tower</div>
        </div>
    </div>
    <div>
        <img alt="icm" src="./img/Cisco/Network-Topology/icm.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/icm.svg">SVG</a>
            <div class="img-title">icm</div>
        </div>
    </div>
    <div>
        <img alt="ics" src="./img/Cisco/Network-Topology/ics.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ics.svg">SVG</a>
            <div class="img-title">ics</div>
        </div>
    </div>
    <div>
        <img alt="intelliswitch_stack" src="./img/Cisco/Network-Topology/intelliswitch_stack.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/intelliswitch_stack.svg">SVG</a>
            <div class="img-title">intelliswitch_stack</div>
        </div>
    </div>
    <div>
        <img alt="internet_streamer" src="./img/Cisco/Network-Topology/internet_streamer.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/internet_streamer.svg">SVG</a>
            <div class="img-title">internet_streamer</div>
        </div>
    </div>
    <div>
        <img alt="ios_firewall" src="./img/Cisco/Network-Topology/ios_firewall.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ios_firewall.svg">SVG</a>
            <div class="img-title">ios_firewall</div>
        </div>
    </div>
    <div>
        <img alt="ios_slb" src="./img/Cisco/Network-Topology/ios_slb.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ios_slb.svg">SVG</a>
            <div class="img-title">ios_slb</div>
        </div>
    </div>
    <div>
        <img alt="ip_communicator" src="./img/Cisco/Network-Topology/ip_communicator.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ip_communicator.svg">SVG</a>
            <div class="img-title">ip_communicator</div>
        </div>
    </div>
    <div>
        <img alt="ip_dsl" src="./img/Cisco/Network-Topology/ip_dsl.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ip_dsl.svg">SVG</a>
            <div class="img-title">ip_dsl</div>
        </div>
    </div>
    <div>
        <img alt="ip_phone" src="./img/Cisco/Network-Topology/ip_phone.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ip_phone.svg">SVG</a>
            <div class="img-title">ip_phone</div>
        </div>
    </div>
    <div>
        <img alt="ip_telephony_router" src="./img/Cisco/Network-Topology/ip_telephony_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ip_telephony_router.svg">SVG</a>
            <div class="img-title">ip_telephony_router</div>
        </div>
    </div>
    <div>
        <img alt="ip" src="./img/Cisco/Network-Topology/ip.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ip.svg">SVG</a>
            <div class="img-title">ip</div>
        </div>
    </div>
    <div>
        <img alt="iptc" src="./img/Cisco/Network-Topology/iptc.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/iptc.svg">SVG</a>
            <div class="img-title">iptc</div>
        </div>
    </div>
    <div>
        <img alt="iptv_content_manager" src="./img/Cisco/Network-Topology/iptv_content_manager.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/iptv_content_manager.svg">SVG</a>
            <div class="img-title">iptv_content_manager</div>
        </div>
    </div>
    <div>
        <img alt="iptv_server" src="./img/Cisco/Network-Topology/iptv_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/iptv_server.svg">SVG</a>
            <div class="img-title">iptv_server</div>
        </div>
    </div>
    <div>
        <img alt="iscsi_router" src="./img/Cisco/Network-Topology/iscsi_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/iscsi_router.svg">SVG</a>
            <div class="img-title">iscsi_router</div>
        </div>
    </div>
    <div>
        <img alt="isdn_switch" src="./img/Cisco/Network-Topology/isdn_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/isdn_switch.svg">SVG</a>
            <div class="img-title">isdn_switch</div>
        </div>
    </div>
    <div>
        <img alt="itp" src="./img/Cisco/Network-Topology/itp.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/itp.svg">SVG</a>
            <div class="img-title">itp</div>
        </div>
    </div>
    <div>
        <img alt="jbod" src="./img/Cisco/Network-Topology/jbod.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/jbod.svg">SVG</a>
            <div class="img-title">jbod</div>
        </div>
    </div>
    <div>
        <img alt="key" src="./img/Cisco/Network-Topology/key.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/key.svg">SVG</a>
            <div class="img-title">key</div>
        </div>
    </div>
    <div>
        <img alt="keys" src="./img/Cisco/Network-Topology/keys.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/keys.svg">SVG</a>
            <div class="img-title">keys</div>
        </div>
    </div>
    <div>
        <img alt="lan_to_lan" src="./img/Cisco/Network-Topology/lan_to_lan.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/lan_to_lan.svg">SVG</a>
            <div class="img-title">lan_to_lan</div>
        </div>
    </div>
    <div>
        <img alt="laptop" src="./img/Cisco/Network-Topology/laptop.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/laptop.svg">SVG</a>
            <div class="img-title">laptop</div>
        </div>
    </div>
    <div>
        <img alt="layer_2_remote_switch" src="./img/Cisco/Network-Topology/layer_2_remote_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/layer_2_remote_switch.svg">SVG</a>
            <div class="img-title">layer_2_remote_switch</div>
        </div>
    </div>
    <div>
        <img alt="layer_3_switch" src="./img/Cisco/Network-Topology/layer_3_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/layer_3_switch.svg">SVG</a>
            <div class="img-title">layer_3_switch</div>
        </div>
    </div>
    <div>
        <img alt="lightweight_ap" src="./img/Cisco/Network-Topology/lightweight_ap.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/lightweight_ap.svg">SVG</a>
            <div class="img-title">lightweight_ap</div>
        </div>
    </div>
    <div>
        <img alt="localdirector" src="./img/Cisco/Network-Topology/localdirector.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/localdirector.svg">SVG</a>
            <div class="img-title">localdirector</div>
        </div>
    </div>
    <div>
        <img alt="lock" src="./img/Cisco/Network-Topology/lock.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/lock.svg">SVG</a>
            <div class="img-title">lock</div>
        </div>
    </div>
    <div>
        <img alt="longreach_cpe" src="./img/Cisco/Network-Topology/longreach_cpe.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/longreach_cpe.svg">SVG</a>
            <div class="img-title">longreach_cpe</div>
        </div>
    </div>
    <div>
        <img alt="mac_woman" src="./img/Cisco/Network-Topology/mac_woman.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mac_woman.svg">SVG</a>
            <div class="img-title">mac_woman</div>
        </div>
    </div>
    <div>
        <img alt="macintosh" src="./img/Cisco/Network-Topology/macintosh.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/macintosh.svg">SVG</a>
            <div class="img-title">macintosh</div>
        </div>
    </div>
    <div>
        <img alt="man_woman" src="./img/Cisco/Network-Topology/man_woman.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/man_woman.svg">SVG</a>
            <div class="img-title">man_woman</div>
        </div>
    </div>
    <div>
        <img alt="mas_gateway" src="./img/Cisco/Network-Topology/mas_gateway.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mas_gateway.svg">SVG</a>
            <div class="img-title">mas_gateway</div>
        </div>
    </div>
    <div>
        <img alt="mau" src="./img/Cisco/Network-Topology/mau.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mau.svg">SVG</a>
            <div class="img-title">mau</div>
        </div>
    </div>
    <div>
        <img alt="mcu" src="./img/Cisco/Network-Topology/mcu.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mcu.svg">SVG</a>
            <div class="img-title">mcu</div>
        </div>
    </div>
    <div>
        <img alt="mdu" src="./img/Cisco/Network-Topology/mdu.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mdu.svg">SVG</a>
            <div class="img-title">mdu</div>
        </div>
    </div>
    <div>
        <img alt="me_1100" src="./img/Cisco/Network-Topology/me_1100.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/me_1100.svg">SVG</a>
            <div class="img-title">me_1100</div>
        </div>
    </div>
    <div>
        <img alt="Mediator" src="./img/Cisco/Network-Topology/Mediator.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Mediator.svg">SVG</a>
            <div class="img-title">Mediator</div>
        </div>
    </div>
    <div>
        <img alt="meetingplace" src="./img/Cisco/Network-Topology/meetingplace.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/meetingplace.svg">SVG</a>
            <div class="img-title">meetingplace</div>
        </div>
    </div>
    <div>
        <img alt="mesh_ap" src="./img/Cisco/Network-Topology/mesh_ap.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mesh_ap.svg">SVG</a>
            <div class="img-title">mesh_ap</div>
        </div>
    </div>
    <div>
        <img alt="metro_1500" src="./img/Cisco/Network-Topology/metro_1500.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/metro_1500.svg">SVG</a>
            <div class="img-title">metro_1500</div>
        </div>
    </div>
    <div>
        <img alt="mgx_8000_multiservice_switch" src="./img/Cisco/Network-Topology/mgx_8000_multiservice_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mgx_8000_multiservice_switch.svg">SVG</a>
            <div class="img-title">mgx_8000_multiservice_switch</div>
        </div>
    </div>
    <div>
        <img alt="microphone" src="./img/Cisco/Network-Topology/microphone.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/microphone.svg">SVG</a>
            <div class="img-title">microphone</div>
        </div>
    </div>
    <div>
        <img alt="microwebserver" src="./img/Cisco/Network-Topology/microwebserver.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/microwebserver.svg">SVG</a>
            <div class="img-title">microwebserver</div>
        </div>
    </div>
    <div>
        <img alt="mini_vax" src="./img/Cisco/Network-Topology/mini_vax.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mini_vax.svg">SVG</a>
            <div class="img-title">mini_vax</div>
        </div>
    </div>
    <div>
        <img alt="mobile_access_ip_phone" src="./img/Cisco/Network-Topology/mobile_access_ip_phone.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mobile_access_ip_phone.svg">SVG</a>
            <div class="img-title">mobile_access_ip_phone</div>
        </div>
    </div>
    <div>
        <img alt="mobile_access_router" src="./img/Cisco/Network-Topology/mobile_access_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mobile_access_router.svg">SVG</a>
            <div class="img-title">mobile_access_router</div>
        </div>
    </div>
    <div>
        <img alt="mobile_streamer" src="./img/Cisco/Network-Topology/mobile_streamer.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mobile_streamer.svg">SVG</a>
            <div class="img-title">mobile_streamer</div>
        </div>
    </div>
    <div>
        <img alt="modem" src="./img/Cisco/Network-Topology/modem.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/modem.svg">SVG</a>
            <div class="img-title">modem</div>
        </div>
    </div>
    <div>
        <img alt="moh_server" src="./img/Cisco/Network-Topology/moh_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/moh_server.svg">SVG</a>
            <div class="img-title">moh_server</div>
        </div>
    </div>
    <div>
        <img alt="MSE" src="./img/Cisco/Network-Topology/MSE.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/MSE.svg">SVG</a>
            <div class="img-title">MSE</div>
        </div>
    </div>
    <div>
        <img alt="mulitswitch_device" src="./img/Cisco/Network-Topology/mulitswitch_device.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mulitswitch_device.svg">SVG</a>
            <div class="img-title">mulitswitch_device</div>
        </div>
    </div>
    <div>
        <img alt="multi-fabric_server_switch" src="./img/Cisco/Network-Topology/multi-fabric_server_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/multi-fabric_server_switch.svg">SVG</a>
            <div class="img-title">multi-fabric_server_switch</div>
        </div>
    </div>
    <div>
        <img alt="multilayer_remote_switch" src="./img/Cisco/Network-Topology/multilayer_remote_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/multilayer_remote_switch.svg">SVG</a>
            <div class="img-title">multilayer_remote_switch</div>
        </div>
    </div>
    <div>
        <img alt="mux" src="./img/Cisco/Network-Topology/mux.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/mux.svg">SVG</a>
            <div class="img-title">mux</div>
        </div>
    </div>
    <div>
        <img alt="nac_appliance" src="./img/Cisco/Network-Topology/nac_appliance.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/nac_appliance.svg">SVG</a>
            <div class="img-title">nac_appliance</div>
        </div>
    </div>
    <div>
        <img alt="NCE_router" src="./img/Cisco/Network-Topology/NCE_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/NCE_router.svg">SVG</a>
            <div class="img-title">NCE_router</div>
        </div>
    </div>
    <div>
        <img alt="NCE" src="./img/Cisco/Network-Topology/NCE.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/NCE.svg">SVG</a>
            <div class="img-title">NCE</div>
        </div>
    </div>
    <div>
        <img alt="netflow_router" src="./img/Cisco/Network-Topology/netflow_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/netflow_router.svg">SVG</a>
            <div class="img-title">netflow_router</div>
        </div>
    </div>
    <div>
        <img alt="netranger" src="./img/Cisco/Network-Topology/netranger.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/netranger.svg">SVG</a>
            <div class="img-title">netranger</div>
        </div>
    </div>
    <div>
        <img alt="netsonar" src="./img/Cisco/Network-Topology/netsonar.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/netsonar.svg">SVG</a>
            <div class="img-title">netsonar</div>
        </div>
    </div>
    <div>
        <img alt="network_management" src="./img/Cisco/Network-Topology/network_management.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/network_management.svg">SVG</a>
            <div class="img-title">network_management</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_1000" src="./img/Cisco/Network-Topology/Nexus_1000.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Nexus_1000.svg">SVG</a>
            <div class="img-title">Nexus_1000</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_2000" src="./img/Cisco/Network-Topology/Nexus_2000.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Nexus_2000.svg">SVG</a>
            <div class="img-title">Nexus_2000</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_5000" src="./img/Cisco/Network-Topology/Nexus_5000.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Nexus_5000.svg">SVG</a>
            <div class="img-title">Nexus_5000</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_7000" src="./img/Cisco/Network-Topology/Nexus_7000.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Nexus_7000.svg">SVG</a>
            <div class="img-title">Nexus_7000</div>
        </div>
    </div>
    <div>
        <img alt="octel" src="./img/Cisco/Network-Topology/octel.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/octel.svg">SVG</a>
            <div class="img-title">octel</div>
        </div>
    </div>
    <div>
        <img alt="ons15500" src="./img/Cisco/Network-Topology/ons15500.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ons15500.svg">SVG</a>
            <div class="img-title">ons15500</div>
        </div>
    </div>
    <div>
        <img alt="optical_amplifier" src="./img/Cisco/Network-Topology/optical_amplifier.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/optical_amplifier.svg">SVG</a>
            <div class="img-title">optical_amplifier</div>
        </div>
    </div>
    <div>
        <img alt="optical_services_router" src="./img/Cisco/Network-Topology/optical_services_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/optical_services_router.svg">SVG</a>
            <div class="img-title">optical_services_router</div>
        </div>
    </div>
    <div>
        <img alt="optical_transport" src="./img/Cisco/Network-Topology/optical_transport.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/optical_transport.svg">SVG</a>
            <div class="img-title">optical_transport</div>
        </div>
    </div>
    <div>
        <img alt="pad_x.28" src="./img/Cisco/Network-Topology/pad_x.28.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pad_x.28.svg">SVG</a>
            <div class="img-title">pad_x.28</div>
        </div>
    </div>
    <div>
        <img alt="pad" src="./img/Cisco/Network-Topology/pad.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pad.svg">SVG</a>
            <div class="img-title">pad</div>
        </div>
    </div>
    <div>
        <img alt="page_icon" src="./img/Cisco/Network-Topology/page_icon.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/page_icon.svg">SVG</a>
            <div class="img-title">page_icon</div>
        </div>
    </div>
    <div>
        <img alt="pbx_switch" src="./img/Cisco/Network-Topology/pbx_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pbx_switch.svg">SVG</a>
            <div class="img-title">pbx_switch</div>
        </div>
    </div>
    <div>
        <img alt="pbx" src="./img/Cisco/Network-Topology/pbx.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pbx.svg">SVG</a>
            <div class="img-title">pbx</div>
        </div>
    </div>
    <div>
        <img alt="pc_adapter_card" src="./img/Cisco/Network-Topology/pc_adapter_card.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pc_adapter_card.svg">SVG</a>
            <div class="img-title">pc_adapter_card</div>
        </div>
    </div>
    <div>
        <img alt="pc_man" src="./img/Cisco/Network-Topology/pc_man.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pc_man.svg">SVG</a>
            <div class="img-title">pc_man</div>
        </div>
    </div>
    <div>
        <img alt="pc_routercard" src="./img/Cisco/Network-Topology/pc_routercard.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pc_routercard.svg">SVG</a>
            <div class="img-title">pc_routercard</div>
        </div>
    </div>
    <div>
        <img alt="pc_software" src="./img/Cisco/Network-Topology/pc_software.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pc_software.svg">SVG</a>
            <div class="img-title">pc_software</div>
        </div>
    </div>
    <div>
        <img alt="pc_video" src="./img/Cisco/Network-Topology/pc_video.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pc_video.svg">SVG</a>
            <div class="img-title">pc_video</div>
        </div>
    </div>
    <div>
        <img alt="pc" src="./img/Cisco/Network-Topology/pc.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pc.svg">SVG</a>
            <div class="img-title">pc</div>
        </div>
    </div>
    <div>
        <img alt="pda" src="./img/Cisco/Network-Topology/pda.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pda.svg">SVG</a>
            <div class="img-title">pda</div>
        </div>
    </div>
    <div>
        <img alt="phone_fax" src="./img/Cisco/Network-Topology/phone_fax.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/phone_fax.svg">SVG</a>
            <div class="img-title">phone_fax</div>
        </div>
    </div>
    <div>
        <img alt="phone" src="./img/Cisco/Network-Topology/phone.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/phone.svg">SVG</a>
            <div class="img-title">phone</div>
        </div>
    </div>
    <div>
        <img alt="pix_firewall" src="./img/Cisco/Network-Topology/pix_firewall.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pix_firewall.svg">SVG</a>
            <div class="img-title">pix_firewall</div>
        </div>
    </div>
    <div>
        <img alt="pmc" src="./img/Cisco/Network-Topology/pmc.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pmc.svg">SVG</a>
            <div class="img-title">pmc</div>
        </div>
    </div>
    <div>
        <img alt="printer" src="./img/Cisco/Network-Topology/printer.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/printer.svg">SVG</a>
            <div class="img-title">printer</div>
        </div>
    </div>
    <div>
        <img alt="programmable_switch" src="./img/Cisco/Network-Topology/programmable_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/programmable_switch.svg">SVG</a>
            <div class="img-title">programmable_switch</div>
        </div>
    </div>
    <div>
        <img alt="protocol_translator" src="./img/Cisco/Network-Topology/protocol_translator.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/protocol_translator.svg">SVG</a>
            <div class="img-title">protocol_translator</div>
        </div>
    </div>
    <div>
        <img alt="pxf" src="./img/Cisco/Network-Topology/pxf.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/pxf.svg">SVG</a>
            <div class="img-title">pxf</div>
        </div>
    </div>
    <div>
        <img alt="ratemux" src="./img/Cisco/Network-Topology/ratemux.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ratemux.svg">SVG</a>
            <div class="img-title">ratemux</div>
        </div>
    </div>
    <div>
        <img alt="relational_database" src="./img/Cisco/Network-Topology/relational_database.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/relational_database.svg">SVG</a>
            <div class="img-title">relational_database</div>
        </div>
    </div>
    <div>
        <img alt="repeater" src="./img/Cisco/Network-Topology/repeater.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/repeater.svg">SVG</a>
            <div class="img-title">repeater</div>
        </div>
    </div>
    <div>
        <img alt="RF_modem" src="./img/Cisco/Network-Topology/RF_modem.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/RF_modem.svg">SVG</a>
            <div class="img-title">RF_modem</div>
        </div>
    </div>
    <div>
        <img alt="route_switch_processor" src="./img/Cisco/Network-Topology/route_switch_processor.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/route_switch_processor.svg">SVG</a>
            <div class="img-title">route_switch_processor</div>
        </div>
    </div>
    <div>
        <img alt="router_firewall" src="./img/Cisco/Network-Topology/router_firewall.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/router_firewall.svg">SVG</a>
            <div class="img-title">router_firewall</div>
        </div>
    </div>
    <div>
        <img alt="router_with_silicon_switch" src="./img/Cisco/Network-Topology/router_with_silicon_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/router_with_silicon_switch.svg">SVG</a>
            <div class="img-title">router_with_silicon_switch</div>
        </div>
    </div>
    <div>
        <img alt="router" src="./img/Cisco/Network-Topology/router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/router.svg">SVG</a>
            <div class="img-title">router</div>
        </div>
    </div>
    <div>
        <img alt="routerin_building" src="./img/Cisco/Network-Topology/routerin_building.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/routerin_building.svg">SVG</a>
            <div class="img-title">routerin_building</div>
        </div>
    </div>
    <div>
        <img alt="rpsrps" src="./img/Cisco/Network-Topology/rpsrps.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/rpsrps.svg">SVG</a>
            <div class="img-title">rpsrps</div>
        </div>
    </div>
    <div>
        <img alt="running_man" src="./img/Cisco/Network-Topology/running_man.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/running_man.svg">SVG</a>
            <div class="img-title">running_man</div>
        </div>
    </div>
    <div>
        <img alt="safeharbor_icon" src="./img/Cisco/Network-Topology/safeharbor_icon.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/safeharbor_icon.svg">SVG</a>
            <div class="img-title">safeharbor_icon</div>
        </div>
    </div>
    <div>
        <img alt="sattelite_dish" src="./img/Cisco/Network-Topology/sattelite_dish.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/sattelite_dish.svg">SVG</a>
            <div class="img-title">sattelite_dish</div>
        </div>
    </div>
    <div>
        <img alt="sattelite" src="./img/Cisco/Network-Topology/sattelite.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/sattelite.svg">SVG</a>
            <div class="img-title">sattelite</div>
        </div>
    </div>
    <div>
        <img alt="scanner" src="./img/Cisco/Network-Topology/scanner.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/scanner.svg">SVG</a>
            <div class="img-title">scanner</div>
        </div>
    </div>
    <div>
        <img alt="server_switch" src="./img/Cisco/Network-Topology/server_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/server_switch.svg">SVG</a>
            <div class="img-title">server_switch</div>
        </div>
    </div>
    <div>
        <img alt="server_with_router" src="./img/Cisco/Network-Topology/server_with_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/server_with_router.svg">SVG</a>
            <div class="img-title">server_with_router</div>
        </div>
    </div>
    <div>
        <img alt="service_control" src="./img/Cisco/Network-Topology/service_control.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/service_control.svg">SVG</a>
            <div class="img-title">service_control</div>
        </div>
    </div>
    <div>
        <img alt="Service_Module" src="./img/Cisco/Network-Topology/Service_Module.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Service_Module.svg">SVG</a>
            <div class="img-title">Service_Module</div>
        </div>
    </div>
    <div>
        <img alt="Service_router" src="./img/Cisco/Network-Topology/Service_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Service_router.svg">SVG</a>
            <div class="img-title">Service_router</div>
        </div>
    </div>
    <div>
        <img alt="Services" src="./img/Cisco/Network-Topology/Services.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Services.svg">SVG</a>
            <div class="img-title">Services</div>
        </div>
    </div>
    <div>
        <img alt="Set_top_box" src="./img/Cisco/Network-Topology/Set_top_box.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Set_top_box.svg">SVG</a>
            <div class="img-title">Set_top_box</div>
        </div>
    </div>
    <div>
        <img alt="simulitlayer_switch" src="./img/Cisco/Network-Topology/simulitlayer_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/simulitlayer_switch.svg">SVG</a>
            <div class="img-title">simulitlayer_switch</div>
        </div>
    </div>
    <div>
        <img alt="sip_proxy_werver" src="./img/Cisco/Network-Topology/sip_proxy_werver.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/sip_proxy_werver.svg">SVG</a>
            <div class="img-title">sip_proxy_werver</div>
        </div>
    </div>
    <div>
        <img alt="sitting_woman" src="./img/Cisco/Network-Topology/sitting_woman.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/sitting_woman.svg">SVG</a>
            <div class="img-title">sitting_woman</div>
        </div>
    </div>
    <div>
        <img alt="small_business" src="./img/Cisco/Network-Topology/small_business.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/small_business.svg">SVG</a>
            <div class="img-title">small_business</div>
        </div>
    </div>
    <div>
        <img alt="small_hub" src="./img/Cisco/Network-Topology/small_hub.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/small_hub.svg">SVG</a>
            <div class="img-title">small_hub</div>
        </div>
    </div>
    <div>
        <img alt="softphone" src="./img/Cisco/Network-Topology/softphone.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/softphone.svg">SVG</a>
            <div class="img-title">softphone</div>
        </div>
    </div>
    <div>
        <img alt="softswitch_pgw_mgc" src="./img/Cisco/Network-Topology/softswitch_pgw_mgc.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/softswitch_pgw_mgc.svg">SVG</a>
            <div class="img-title">softswitch_pgw_mgc</div>
        </div>
    </div>
    <div>
        <img alt="software_based_server" src="./img/Cisco/Network-Topology/software_based_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/software_based_server.svg">SVG</a>
            <div class="img-title">software_based_server</div>
        </div>
    </div>
    <div>
        <img alt="Space_router" src="./img/Cisco/Network-Topology/Space_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/Space_router.svg">SVG</a>
            <div class="img-title">Space_router</div>
        </div>
    </div>
    <div>
        <img alt="speaker" src="./img/Cisco/Network-Topology/speaker.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/speaker.svg">SVG</a>
            <div class="img-title">speaker</div>
        </div>
    </div>
    <div>
        <img alt="ssc" src="./img/Cisco/Network-Topology/ssc.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ssc.svg">SVG</a>
            <div class="img-title">ssc</div>
        </div>
    </div>
    <div>
        <img alt="ssl_terminator" src="./img/Cisco/Network-Topology/ssl_terminator.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ssl_terminator.svg">SVG</a>
            <div class="img-title">ssl_terminator</div>
        </div>
    </div>
    <div>
        <img alt="standard_host" src="./img/Cisco/Network-Topology/standard_host.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/standard_host.svg">SVG</a>
            <div class="img-title">standard_host</div>
        </div>
    </div>
    <div>
        <img alt="standing_man" src="./img/Cisco/Network-Topology/standing_man.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/standing_man.svg">SVG</a>
            <div class="img-title">standing_man</div>
        </div>
    </div>
    <div>
        <img alt="standing_woman" src="./img/Cisco/Network-Topology/standing_woman.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/standing_woman.svg">SVG</a>
            <div class="img-title">standing_woman</div>
        </div>
    </div>
    <div>
        <img alt="stb" src="./img/Cisco/Network-Topology/stb.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/stb.svg">SVG</a>
            <div class="img-title">stb</div>
        </div>
    </div>
    <div>
        <img alt="storage_router" src="./img/Cisco/Network-Topology/storage_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/storage_router.svg">SVG</a>
            <div class="img-title">storage_router</div>
        </div>
    </div>
    <div>
        <img alt="storage_server" src="./img/Cisco/Network-Topology/storage_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/storage_server.svg">SVG</a>
            <div class="img-title">storage_server</div>
        </div>
    </div>
    <div>
        <img alt="stp" src="./img/Cisco/Network-Topology/stp.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/stp.svg">SVG</a>
            <div class="img-title">stp</div>
        </div>
    </div>
    <div>
        <img alt="streamer" src="./img/Cisco/Network-Topology/streamer.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/streamer.svg">SVG</a>
            <div class="img-title">streamer</div>
        </div>
    </div>
    <div>
        <img alt="sun_workstation" src="./img/Cisco/Network-Topology/sun_workstation.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/sun_workstation.svg">SVG</a>
            <div class="img-title">sun_workstation</div>
        </div>
    </div>
    <div>
        <img alt="supercomputer" src="./img/Cisco/Network-Topology/supercomputer.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/supercomputer.svg">SVG</a>
            <div class="img-title">supercomputer</div>
        </div>
    </div>
    <div>
        <img alt="svx" src="./img/Cisco/Network-Topology/svx.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/svx.svg">SVG</a>
            <div class="img-title">svx</div>
        </div>
    </div>
    <div>
        <img alt="system_controller" src="./img/Cisco/Network-Topology/system_controller.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/system_controller.svg">SVG</a>
            <div class="img-title">system_controller</div>
        </div>
    </div>
    <div>
        <img alt="tablet" src="./img/Cisco/Network-Topology/tablet.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/tablet.svg">SVG</a>
            <div class="img-title">tablet</div>
        </div>
    </div>
    <div>
        <img alt="tape_array" src="./img/Cisco/Network-Topology/tape_array.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/tape_array.svg">SVG</a>
            <div class="img-title">tape_array</div>
        </div>
    </div>
    <div>
        <img alt="tdm_router" src="./img/Cisco/Network-Topology/tdm_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/tdm_router.svg">SVG</a>
            <div class="img-title">tdm_router</div>
        </div>
    </div>
    <div>
        <img alt="telecommuter_house_pc" src="./img/Cisco/Network-Topology/telecommuter_house_pc.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/telecommuter_house_pc.svg">SVG</a>
            <div class="img-title">telecommuter_house_pc</div>
        </div>
    </div>
    <div>
        <img alt="telecommuter_house" src="./img/Cisco/Network-Topology/telecommuter_house.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/telecommuter_house.svg">SVG</a>
            <div class="img-title">telecommuter_house</div>
        </div>
    </div>
    <div>
        <img alt="telecommuter_icon" src="./img/Cisco/Network-Topology/telecommuter_icon.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/telecommuter_icon.svg">SVG</a>
            <div class="img-title">telecommuter_icon</div>
        </div>
    </div>
    <div>
        <img alt="terminal" src="./img/Cisco/Network-Topology/terminal.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/terminal.svg">SVG</a>
            <div class="img-title">terminal</div>
        </div>
    </div>
    <div>
        <img alt="token" src="./img/Cisco/Network-Topology/token.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/token.svg">SVG</a>
            <div class="img-title">token</div>
        </div>
    </div>
    <div>
        <img alt="TP_MCU" src="./img/Cisco/Network-Topology/TP_MCU.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/TP_MCU.svg">SVG</a>
            <div class="img-title">TP_MCU</div>
        </div>
    </div>
    <div>
        <img alt="transpath" src="./img/Cisco/Network-Topology/transpath.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/transpath.svg">SVG</a>
            <div class="img-title">transpath</div>
        </div>
    </div>
    <div>
        <img alt="truck" src="./img/Cisco/Network-Topology/truck.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/truck.svg">SVG</a>
            <div class="img-title">truck</div>
        </div>
    </div>
    <div>
        <img alt="turret" src="./img/Cisco/Network-Topology/turret.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/turret.svg">SVG</a>
            <div class="img-title">turret</div>
        </div>
    </div>
    <div>
        <img alt="tv" src="./img/Cisco/Network-Topology/tv.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/tv.svg">SVG</a>
            <div class="img-title">tv</div>
        </div>
    </div>
    <div>
        <img alt="ubr910" src="./img/Cisco/Network-Topology/ubr910.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ubr910.svg">SVG</a>
            <div class="img-title">ubr910</div>
        </div>
    </div>
    <div>
        <img alt="umg_series" src="./img/Cisco/Network-Topology/umg_series.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/umg_series.svg">SVG</a>
            <div class="img-title">umg_series</div>
        </div>
    </div>
    <div>
        <img alt="unity_server" src="./img/Cisco/Network-Topology/unity_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/unity_server.svg">SVG</a>
            <div class="img-title">unity_server</div>
        </div>
    </div>
    <div>
        <img alt="universal_gateway" src="./img/Cisco/Network-Topology/universal_gateway.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/universal_gateway.svg">SVG</a>
            <div class="img-title">universal_gateway</div>
        </div>
    </div>
    <div>
        <img alt="university" src="./img/Cisco/Network-Topology/university.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/university.svg">SVG</a>
            <div class="img-title">university</div>
        </div>
    </div>
    <div>
        <img alt="upc" src="./img/Cisco/Network-Topology/upc.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/upc.svg">SVG</a>
            <div class="img-title">upc</div>
        </div>
    </div>
    <div>
        <img alt="ups" src="./img/Cisco/Network-Topology/ups.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/ups.svg">SVG</a>
            <div class="img-title">ups</div>
        </div>
    </div>
    <div>
        <img alt="vault" src="./img/Cisco/Network-Topology/vault.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/vault.svg">SVG</a>
            <div class="img-title">vault</div>
        </div>
    </div>
    <div>
        <img alt="video_camera" src="./img/Cisco/Network-Topology/video_camera.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/video_camera.svg">SVG</a>
            <div class="img-title">video_camera</div>
        </div>
    </div>
    <div>
        <img alt="vip" src="./img/Cisco/Network-Topology/vip.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/vip.svg">SVG</a>
            <div class="img-title">vip</div>
        </div>
    </div>
    <div>
        <img alt="virtual_layer_switch" src="./img/Cisco/Network-Topology/virtual_layer_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/virtual_layer_switch.svg">SVG</a>
            <div class="img-title">virtual_layer_switch</div>
        </div>
    </div>
    <div>
        <img alt="virtual_switch_controller_(vsc3000)" src="./img/Cisco/Network-Topology/virtual_switch_controller_(vsc3000).png" />
        <div>
            <a href="./img/Cisco/Network-Topology/virtual_switch_controller_(vsc3000).svg">SVG</a>
            <div class="img-title">virtual_switch_controller_(vsc3000)</div>
        </div>
    </div>
    <div>
        <img alt="voice_atm_switch" src="./img/Cisco/Network-Topology/voice_atm_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/voice_atm_switch.svg">SVG</a>
            <div class="img-title">voice_atm_switch</div>
        </div>
    </div>
    <div>
        <img alt="voice_commserver" src="./img/Cisco/Network-Topology/voice_commserver.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/voice_commserver.svg">SVG</a>
            <div class="img-title">voice_commserver</div>
        </div>
    </div>
    <div>
        <img alt="voice_router" src="./img/Cisco/Network-Topology/voice_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/voice_router.svg">SVG</a>
            <div class="img-title">voice_router</div>
        </div>
    </div>
    <div>
        <img alt="voice_switch" src="./img/Cisco/Network-Topology/voice_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/voice_switch.svg">SVG</a>
            <div class="img-title">voice_switch</div>
        </div>
    </div>
    <div>
        <img alt="vpn_concentrator" src="./img/Cisco/Network-Topology/vpn_concentrator.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/vpn_concentrator.svg">SVG</a>
            <div class="img-title">vpn_concentrator</div>
        </div>
    </div>
    <div>
        <img alt="vpn_gateway" src="./img/Cisco/Network-Topology/vpn_gateway.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/vpn_gateway.svg">SVG</a>
            <div class="img-title">vpn_gateway</div>
        </div>
    </div>
    <div>
        <img alt="VSD" src="./img/Cisco/Network-Topology/VSD.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/VSD.svg">SVG</a>
            <div class="img-title">VSD</div>
        </div>
    </div>
    <div>
        <img alt="VSS" src="./img/Cisco/Network-Topology/VSS.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/VSS.svg">SVG</a>
            <div class="img-title">VSS</div>
        </div>
    </div>
    <div>
        <img alt="wae" src="./img/Cisco/Network-Topology/wae.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wae.svg">SVG</a>
            <div class="img-title">wae</div>
        </div>
    </div>
    <div>
        <img alt="wavelength_router" src="./img/Cisco/Network-Topology/wavelength_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wavelength_router.svg">SVG</a>
            <div class="img-title">wavelength_router</div>
        </div>
    </div>
    <div>
        <img alt="web_browser" src="./img/Cisco/Network-Topology/web_browser.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/web_browser.svg">SVG</a>
            <div class="img-title">web_browser</div>
        </div>
    </div>
    <div>
        <img alt="web_cluster" src="./img/Cisco/Network-Topology/web_cluster.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/web_cluster.svg">SVG</a>
            <div class="img-title">web_cluster</div>
        </div>
    </div>
    <div>
        <img alt="wi-fi_tag" src="./img/Cisco/Network-Topology/wi-fi_tag.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wi-fi_tag.svg">SVG</a>
            <div class="img-title">wi-fi_tag</div>
        </div>
    </div>
    <div>
        <img alt="wireless_bridge" src="./img/Cisco/Network-Topology/wireless_bridge.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wireless_bridge.svg">SVG</a>
            <div class="img-title">wireless_bridge</div>
        </div>
    </div>
    <div>
        <img alt="wireless_location_appliance" src="./img/Cisco/Network-Topology/wireless_location_appliance.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wireless_location_appliance.svg">SVG</a>
            <div class="img-title">wireless_location_appliance</div>
        </div>
    </div>
    <div>
        <img alt="wireless_router" src="./img/Cisco/Network-Topology/wireless_router.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wireless_router.svg">SVG</a>
            <div class="img-title">wireless_router</div>
        </div>
    </div>
    <div>
        <img alt="wireless_transport" src="./img/Cisco/Network-Topology/wireless_transport.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wireless_transport.svg">SVG</a>
            <div class="img-title">wireless_transport</div>
        </div>
    </div>
    <div>
        <img alt="wireless" src="./img/Cisco/Network-Topology/wireless.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wireless.svg">SVG</a>
            <div class="img-title">wireless</div>
        </div>
    </div>
    <div>
        <img alt="wism" src="./img/Cisco/Network-Topology/wism.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wism.svg">SVG</a>
            <div class="img-title">wism</div>
        </div>
    </div>
    <div>
        <img alt="wlan_controller" src="./img/Cisco/Network-Topology/wlan_controller.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/wlan_controller.svg">SVG</a>
            <div class="img-title">wlan_controller</div>
        </div>
    </div>
    <div>
        <img alt="workgroup_director" src="./img/Cisco/Network-Topology/workgroup_director.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/workgroup_director.svg">SVG</a>
            <div class="img-title">workgroup_director</div>
        </div>
    </div>
    <div>
        <img alt="workgroup_switch" src="./img/Cisco/Network-Topology/workgroup_switch.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/workgroup_switch.svg">SVG</a>
            <div class="img-title">workgroup_switch</div>
        </div>
    </div>
    <div>
        <img alt="workstation" src="./img/Cisco/Network-Topology/workstation.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/workstation.svg">SVG</a>
            <div class="img-title">workstation</div>
        </div>
    </div>
    <div>
        <img alt="www_server" src="./img/Cisco/Network-Topology/www_server.png" />
        <div>
            <a href="./img/Cisco/Network-Topology/www_server.svg">SVG</a>
            <div class="img-title">www_server</div>
        </div>
    </div>
</div>

<br />

## Cisco SAFE Icon Library
[https://www.cisco.com/c/en/us/solutions/collateral/enterprise/design-zone-security/safe-icon-library.html](https://www.cisco.com/c/en/us/solutions/collateral/enterprise/design-zone-security/safe-icon-library.html)

>`SAFE` - Secure Architecture For Everyone 

* Design Icons
* Capability Icons
* Threat Icons
* Architecture Icons


```
ls *' '* | awk '{orig=$0; gsub(/ /, "_"); print "mv -n -- \"" orig "\" \"" $0 "\""}' | bash
```

```
ls -1 | awk '{orig=$0; gsub(/Gray/, "Attack_Surface"); print "mv -n -- \"" orig "\" \"" $0 "\""}' | bash
``` 

```
ls -1 | sed -E 's|([A-Za-z_]+_[0-9]+_)(.*).png|!\[\2\]\(./img/Cisco/SAFE/&\) \2 \[SVG\]\(\1\2.svg\)<br />|'
```

```
ls -1 | sed -E 's|([A-Za-z]+_[0-9]+_)(.*).png|<img alt="\2" src="./img/Cisco/SAFE/&" height="30px" />  \2 \[SVG\]\(\1\2.svg\)<br />|'
```

```
ls *.png | sed -E 's|([A-Za-z]+_[0-9]+_)(.*).png|    <div>\n        <img alt="\2" src="./img/Cisco/SAFE/&" />\n        <div>\n            <a href="./img/Cisco/SAFE/\1\2.svg">SVG</a>\n            <div class="img-title">\2</div>\n        </div>\n    </div>|'
```

### Design

<div class="icon-table">
    <div>
        <img alt="Access_Point" src="./img/Cisco/SAFE/Design_38_Access_Point.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Access_Point.svg">SVG</a>
            <div class="img-title">Access_Point</div>
        </div>
    </div>
    <div>
        <img alt="Access_Switch" src="./img/Cisco/SAFE/Design_38_Access_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Access_Switch.svg">SVG</a>
            <div class="img-title">Access_Switch</div>
        </div>
    </div>
    <div>
        <img alt="ACI_Controller" src="./img/Cisco/SAFE/Design_38_ACI_Controller.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_ACI_Controller.svg">SVG</a>
            <div class="img-title">ACI_Controller</div>
        </div>
    </div>
    <div>
        <img alt="Actuator" src="./img/Cisco/SAFE/Design_38_Actuator.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Actuator.svg">SVG</a>
            <div class="img-title">Actuator</div>
        </div>
    </div>
    <div>
        <img alt="Adaptive_Security_Appliance" src="./img/Cisco/SAFE/Design_38_Adaptive_Security_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Adaptive_Security_Appliance.svg">SVG</a>
            <div class="img-title">Adaptive_Security_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Automated_System" src="./img/Cisco/SAFE/Design_38_Automated_System.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Automated_System.svg">SVG</a>
            <div class="img-title">Automated_System</div>
        </div>
    </div>
    <div>
        <img alt="Blade_Server" src="./img/Cisco/SAFE/Design_38_Blade_Server.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Blade_Server.svg">SVG</a>
            <div class="img-title">Blade_Server</div>
        </div>
    </div>
    <div>
        <img alt="Catalyst_Data_Center_Switch" src="./img/Cisco/SAFE/Design_38_Catalyst_Data_Center_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Catalyst_Data_Center_Switch.svg">SVG</a>
            <div class="img-title">Catalyst_Data_Center_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Cisco_Unbrella" src="./img/Cisco/SAFE/Design_38_Cisco_Unbrella.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Cisco_Unbrella.svg">SVG</a>
            <div class="img-title">Cisco_Unbrella</div>
        </div>
    </div>
    <div>
        <img alt="CloudLock" src="./img/Cisco/SAFE/Design_38_CloudLock.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_CloudLock.svg">SVG</a>
            <div class="img-title">CloudLock</div>
        </div>
    </div>
    <div>
        <img alt="Core_Switch" src="./img/Cisco/SAFE/Design_38_Core_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Core_Switch.svg">SVG</a>
            <div class="img-title">Core_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Corporate_Device" src="./img/Cisco/SAFE/Design_38_Corporate_Device.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Corporate_Device.svg">SVG</a>
            <div class="img-title">Corporate_Device</div>
        </div>
    </div>
    <div>
        <img alt="Corporate_Wireless_Device" src="./img/Cisco/SAFE/Design_38_Corporate_Wireless_Device.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Corporate_Wireless_Device.svg">SVG</a>
            <div class="img-title">Corporate_Wireless_Device</div>
        </div>
    </div>
    <div>
        <img alt="DDOS_Protection" src="./img/Cisco/SAFE/Design_38_DDOS_Protection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_DDOS_Protection.svg">SVG</a>
            <div class="img-title">DDOS_Protection</div>
        </div>
    </div>
    <div>
        <img alt="Distribution_Switch" src="./img/Cisco/SAFE/Design_38_Distribution_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Distribution_Switch.svg">SVG</a>
            <div class="img-title">Distribution_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Email_Security" src="./img/Cisco/SAFE/Design_38_Email_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Email_Security.svg">SVG</a>
            <div class="img-title">Email_Security</div>
        </div>
    </div>
    <div>
        <img alt="Endpoint_Concentrator" src="./img/Cisco/SAFE/Design_38_Endpoint_Concentrator.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Endpoint_Concentrator.svg">SVG</a>
            <div class="img-title">Endpoint_Concentrator</div>
        </div>
    </div>
    <div>
        <img alt="Fabric_Switch" src="./img/Cisco/SAFE/Design_38_Fabric_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Fabric_Switch.svg">SVG</a>
            <div class="img-title">Fabric_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Firepower_Appliance" src="./img/Cisco/SAFE/Design_38_Firepower_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Firepower_Appliance.svg">SVG</a>
            <div class="img-title">Firepower_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Firepower_Management_Center" src="./img/Cisco/SAFE/Design_38_Firepower_Management_Center.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Firepower_Management_Center.svg">SVG</a>
            <div class="img-title">Firepower_Management_Center</div>
        </div>
    </div>
    <div>
        <img alt="Firewall" src="./img/Cisco/SAFE/Design_38_Firewall.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Firewall.svg">SVG</a>
            <div class="img-title">Firewall</div>
        </div>
    </div>
    <div>
        <img alt="Flow_Connector" src="./img/Cisco/SAFE/Design_38_Flow_Connector.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Flow_Connector.svg">SVG</a>
            <div class="img-title">Flow_Connector</div>
        </div>
    </div>
    <div>
        <img alt="Flow_Sensor" src="./img/Cisco/SAFE/Design_38_Flow_Sensor.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Flow_Sensor.svg">SVG</a>
            <div class="img-title">Flow_Sensor</div>
        </div>
    </div>
    <div>
        <img alt="Identity_Directory" src="./img/Cisco/SAFE/Design_38_Identity_Directory.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Identity_Directory.svg">SVG</a>
            <div class="img-title">Identity_Directory</div>
        </div>
    </div>
    <div>
        <img alt="Intrusion_Prevention_System_(IPS)" src="./img/Cisco/SAFE/Design_38_Intrusion_Prevention_System_(IPS).png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Intrusion_Prevention_System_(IPS).svg">SVG</a>
            <div class="img-title">Intrusion_Prevention_System_(IPS)</div>
        </div>
    </div>
    <div>
        <img alt="L2_Switch" src="./img/Cisco/SAFE/Design_38_L2_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_L2_Switch.svg">SVG</a>
            <div class="img-title">L2_Switch</div>
        </div>
    </div>
    <div>
        <img alt="L3_Switch" src="./img/Cisco/SAFE/Design_38_L3_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_L3_Switch.svg">SVG</a>
            <div class="img-title">L3_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Leaf_Switch" src="./img/Cisco/SAFE/Design_38_Leaf_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Leaf_Switch.svg">SVG</a>
            <div class="img-title">Leaf_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Load_Balancer" src="./img/Cisco/SAFE/Design_38_Load_Balancer.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Load_Balancer.svg">SVG</a>
            <div class="img-title">Load_Balancer</div>
        </div>
    </div>
    <div>
        <img alt="Log_Collector" src="./img/Cisco/SAFE/Design_38_Log_Collector.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Log_Collector.svg">SVG</a>
            <div class="img-title">Log_Collector</div>
        </div>
    </div>
    <div>
        <img alt="Management_Console" src="./img/Cisco/SAFE/Design_38_Management_Console.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Management_Console.svg">SVG</a>
            <div class="img-title">Management_Console</div>
        </div>
    </div>
    <div>
        <img alt="Mobile_Device_Management" src="./img/Cisco/SAFE/Design_38_Mobile_Device_Management.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Mobile_Device_Management.svg">SVG</a>
            <div class="img-title">Mobile_Device_Management</div>
        </div>
    </div>
    <div>
        <img alt="Mobile" src="./img/Cisco/SAFE/Design_38_Mobile.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Mobile.svg">SVG</a>
            <div class="img-title">Mobile</div>
        </div>
    </div>
    <div>
        <img alt="Monitoring" src="./img/Cisco/SAFE/Design_38_Monitoring.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Monitoring.svg">SVG</a>
            <div class="img-title">Monitoring</div>
        </div>
    </div>
    <div>
        <img alt="MS_Active_Directory" src="./img/Cisco/SAFE/Design_38_MS_Active_Directory.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_MS_Active_Directory.svg">SVG</a>
            <div class="img-title">MS_Active_Directory</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_1kv" src="./img/Cisco/SAFE/Design_38_Nexus_1kv.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Nexus_1kv.svg">SVG</a>
            <div class="img-title">Nexus_1kv</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_Data_Center_Switch" src="./img/Cisco/SAFE/Design_38_Nexus_Data_Center_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Nexus_Data_Center_Switch.svg">SVG</a>
            <div class="img-title">Nexus_Data_Center_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_Fabric_Switch" src="./img/Cisco/SAFE/Design_38_Nexus_Fabric_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Nexus_Fabric_Switch.svg">SVG</a>
            <div class="img-title">Nexus_Fabric_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_Switch" src="./img/Cisco/SAFE/Design_38_Nexus_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Nexus_Switch.svg">SVG</a>
            <div class="img-title">Nexus_Switch</div>
        </div>
    </div>
    <div>
        <img alt="NTP" src="./img/Cisco/SAFE/Design_38_NTP.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_NTP.svg">SVG</a>
            <div class="img-title">NTP</div>
        </div>
    </div>
    <div>
        <img alt="Phone" src="./img/Cisco/SAFE/Design_38_Phone.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Phone.svg">SVG</a>
            <div class="img-title">Phone</div>
        </div>
    </div>
    <div>
        <img alt="Policy" src="./img/Cisco/SAFE/Design_38_Policy.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Policy.svg">SVG</a>
            <div class="img-title">Policy</div>
        </div>
    </div>
    <div>
        <img alt="Posture_Assessment" src="./img/Cisco/SAFE/Design_38_Posture_Assessment.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Posture_Assessment.svg">SVG</a>
            <div class="img-title">Posture_Assessment</div>
        </div>
    </div>
    <div>
        <img alt="Radware_Appliance" src="./img/Cisco/SAFE/Design_38_Radware_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Radware_Appliance.svg">SVG</a>
            <div class="img-title">Radware_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Router" src="./img/Cisco/SAFE/Design_38_Router.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Router.svg">SVG</a>
            <div class="img-title">Router</div>
        </div>
    </div>
    <div>
        <img alt="SD_WAN" src="./img/Cisco/SAFE/Design_38_SD_WAN.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_SD_WAN.svg">SVG</a>
            <div class="img-title">SD_WAN</div>
        </div>
    </div>
    <div>
        <img alt="Secure_DNS" src="./img/Cisco/SAFE/Design_38_Secure_DNS.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Secure_DNS.svg">SVG</a>
            <div class="img-title">Secure_DNS</div>
        </div>
    </div>
    <div>
        <img alt="Secure_Server" src="./img/Cisco/SAFE/Design_38_Secure_Server.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Secure_Server.svg">SVG</a>
            <div class="img-title">Secure_Server</div>
        </div>
    </div>
    <div>
        <img alt="Secure_X" src="./img/Cisco/SAFE/Design_38_Secure_X.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Secure_X.svg">SVG</a>
            <div class="img-title">Secure_X</div>
        </div>
    </div>
    <div>
        <img alt="Sensor" src="./img/Cisco/SAFE/Design_38_Sensor.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Sensor.svg">SVG</a>
            <div class="img-title">Sensor</div>
        </div>
    </div>
    <div>
        <img alt="Server" src="./img/Cisco/SAFE/Design_38_Server.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Server.svg">SVG</a>
            <div class="img-title">Server</div>
        </div>
    </div>
    <div>
        <img alt="SIEM" src="./img/Cisco/SAFE/Design_38_SIEM.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_SIEM.svg">SVG</a>
            <div class="img-title">SIEM</div>
        </div>
    </div>
    <div>
        <img alt="Spine_Switch" src="./img/Cisco/SAFE/Design_38_Spine_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Spine_Switch.svg">SVG</a>
            <div class="img-title">Spine_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Stacked_Switch" src="./img/Cisco/SAFE/Design_38_Stacked_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Stacked_Switch.svg">SVG</a>
            <div class="img-title">Stacked_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Storage" src="./img/Cisco/SAFE/Design_38_Storage.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Storage.svg">SVG</a>
            <div class="img-title">Storage</div>
        </div>
    </div>
    <div>
        <img alt="Switch_Stack" src="./img/Cisco/SAFE/Design_38_Switch_Stack.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Switch_Stack.svg">SVG</a>
            <div class="img-title">Switch_Stack</div>
        </div>
    </div>
    <div>
        <img alt="Tetration_Appliance" src="./img/Cisco/SAFE/Design_38_Tetration_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Tetration_Appliance.svg">SVG</a>
            <div class="img-title">Tetration_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Threat_Grid" src="./img/Cisco/SAFE/Design_38_Threat_Grid.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Threat_Grid.svg">SVG</a>
            <div class="img-title">Threat_Grid</div>
        </div>
    </div>
    <div>
        <img alt="TLS_Appliance" src="./img/Cisco/SAFE/Design_38_TLS_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_TLS_Appliance.svg">SVG</a>
            <div class="img-title">TLS_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="UDP_Director" src="./img/Cisco/SAFE/Design_38_UDP_Director.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_UDP_Director.svg">SVG</a>
            <div class="img-title">UDP_Director</div>
        </div>
    </div>
    <div>
        <img alt="Vehicle_Commercial" src="./img/Cisco/SAFE/Design_38_Vehicle_Commercial.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Vehicle_Commercial.svg">SVG</a>
            <div class="img-title">Vehicle_Commercial</div>
        </div>
    </div>
    <div>
        <img alt="Vehicle_Consumer" src="./img/Cisco/SAFE/Design_38_Vehicle_Consumer.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Vehicle_Consumer.svg">SVG</a>
            <div class="img-title">Vehicle_Consumer</div>
        </div>
    </div>
    <div>
        <img alt="Vehicle_Flight" src="./img/Cisco/SAFE/Design_38_Vehicle_Flight.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Vehicle_Flight.svg">SVG</a>
            <div class="img-title">Vehicle_Flight</div>
        </div>
    </div>
    <div>
        <img alt="Video_Endpoint" src="./img/Cisco/SAFE/Design_38_Video_Endpoint.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Video_Endpoint.svg">SVG</a>
            <div class="img-title">Video_Endpoint</div>
        </div>
    </div>
    <div>
        <img alt="VPN_Concentrator" src="./img/Cisco/SAFE/Design_38_VPN_Concentrator.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_VPN_Concentrator.svg">SVG</a>
            <div class="img-title">VPN_Concentrator</div>
        </div>
    </div>
    <div>
        <img alt="Vulnerability_Management" src="./img/Cisco/SAFE/Design_38_Vulnerability_Management.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Vulnerability_Management.svg">SVG</a>
            <div class="img-title">Vulnerability_Management</div>
        </div>
    </div>
    <div>
        <img alt="Web_App_Firewall" src="./img/Cisco/SAFE/Design_38_Web_App_Firewall.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Web_App_Firewall.svg">SVG</a>
            <div class="img-title">Web_App_Firewall</div>
        </div>
    </div>
    <div>
        <img alt="Web_Filterning" src="./img/Cisco/SAFE/Design_38_Web_Filterning.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Web_Filterning.svg">SVG</a>
            <div class="img-title">Web_Filterning</div>
        </div>
    </div>
    <div>
        <img alt="Web_Security" src="./img/Cisco/SAFE/Design_38_Web_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Web_Security.svg">SVG</a>
            <div class="img-title">Web_Security</div>
        </div>
    </div>
    <div>
        <img alt="Wide_Area_App_Engine" src="./img/Cisco/SAFE/Design_38_Wide_Area_App_Engine.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Wide_Area_App_Engine.svg">SVG</a>
            <div class="img-title">Wide_Area_App_Engine</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Controller" src="./img/Cisco/SAFE/Design_38_Wireless_Controller.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Wireless_Controller.svg">SVG</a>
            <div class="img-title">Wireless_Controller</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_LAN_Controller" src="./img/Cisco/SAFE/Design_38_Wireless_LAN_Controller.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Wireless_LAN_Controller.svg">SVG</a>
            <div class="img-title">Wireless_LAN_Controller</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Switch" src="./img/Cisco/SAFE/Design_38_Wireless_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Design_38_Wireless_Switch.svg">SVG</a>
            <div class="img-title">Wireless_Switch</div>
        </div>
    </div>
</div>


### Capability

<div class="icon-table">
    <div>
        <img alt="Analysis_Correlation" src="./img/Cisco/SAFE/Capability_43_Analysis_Correlation.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Analysis_Correlation.svg">SVG</a>
            <div class="img-title">Analysis_Correlation</div>
        </div>
    </div>
    <div>
        <img alt="Anomaly_Detection" src="./img/Cisco/SAFE/Capability_43_Anomaly_Detection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Anomaly_Detection.svg">SVG</a>
            <div class="img-title">Anomaly_Detection</div>
        </div>
    </div>
    <div>
        <img alt="AntiMalware" src="./img/Cisco/SAFE/Capability_43_AntiMalware.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_AntiMalware.svg">SVG</a>
            <div class="img-title">AntiMalware</div>
        </div>
    </div>
    <div>
        <img alt="AntiSpam" src="./img/Cisco/SAFE/Capability_43_AntiSpam.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_AntiSpam.svg">SVG</a>
            <div class="img-title">AntiSpam</div>
        </div>
    </div>
    <div>
        <img alt="AntiVirus" src="./img/Cisco/SAFE/Capability_43_AntiVirus.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_AntiVirus.svg">SVG</a>
            <div class="img-title">AntiVirus</div>
        </div>
    </div>
    <div>
        <img alt="API_Interface" src="./img/Cisco/SAFE/Capability_43_API_Interface.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_API_Interface.svg">SVG</a>
            <div class="img-title">API_Interface</div>
        </div>
    </div>
    <div>
        <img alt="App_Visibility_Control" src="./img/Cisco/SAFE/Capability_43_App_Visibility_Control.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_App_Visibility_Control.svg">SVG</a>
            <div class="img-title">App_Visibility_Control</div>
        </div>
    </div>
    <div>
        <img alt="Block" src="./img/Cisco/SAFE/Capability_43_Block.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Block.svg">SVG</a>
            <div class="img-title">Block</div>
        </div>
    </div>
    <div>
        <img alt="Cage" src="./img/Cisco/SAFE/Capability_43_Cage.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Cage.svg">SVG</a>
            <div class="img-title">Cage</div>
        </div>
    </div>
    <div>
        <img alt="Central_Management" src="./img/Cisco/SAFE/Capability_43_Central_Management.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Central_Management.svg">SVG</a>
            <div class="img-title">Central_Management</div>
        </div>
    </div>
    <div>
        <img alt="Certificate_Authority" src="./img/Cisco/SAFE/Capability_43_Certificate_Authority.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Certificate_Authority.svg">SVG</a>
            <div class="img-title">Certificate_Authority</div>
        </div>
    </div>
    <div>
        <img alt="Certificate_Services" src="./img/Cisco/SAFE/Capability_43_Certificate_Services.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Certificate_Services.svg">SVG</a>
            <div class="img-title">Certificate_Services</div>
        </div>
    </div>
    <div>
        <img alt="ClientBased_Security" src="./img/Cisco/SAFE/Capability_43_ClientBased_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_ClientBased_Security.svg">SVG</a>
            <div class="img-title">ClientBased_Security</div>
        </div>
    </div>
    <div>
        <img alt="Cloud_Access_Security_Broker_CASB" src="./img/Cisco/SAFE/Capability_43_Cloud_Access_Security_Broker_CASB.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Cloud_Access_Security_Broker_CASB.svg">SVG</a>
            <div class="img-title">Cloud_Access_Security_Broker_CASB</div>
        </div>
    </div>
    <div>
        <img alt="Cloud_Security" src="./img/Cisco/SAFE/Capability_43_Cloud_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Cloud_Security.svg">SVG</a>
            <div class="img-title">Cloud_Security</div>
        </div>
    </div>
    <div>
        <img alt="Conduit" src="./img/Cisco/SAFE/Capability_43_Conduit.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Conduit.svg">SVG</a>
            <div class="img-title">Conduit</div>
        </div>
    </div>
    <div>
        <img alt="Conference_Bridge" src="./img/Cisco/SAFE/Capability_43_Conference_Bridge.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Conference_Bridge.svg">SVG</a>
            <div class="img-title">Conference_Bridge</div>
        </div>
    </div>
    <div>
        <img alt="Data_Integrity" src="./img/Cisco/SAFE/Capability_43_Data_Integrity.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Data_Integrity.svg">SVG</a>
            <div class="img-title">Data_Integrity</div>
        </div>
    </div>
    <div>
        <img alt="Data_Loss_Prevention" src="./img/Cisco/SAFE/Capability_43_Data_Loss_Prevention.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Data_Loss_Prevention.svg">SVG</a>
            <div class="img-title">Data_Loss_Prevention</div>
        </div>
    </div>
    <div>
        <img alt="Database" src="./img/Cisco/SAFE/Capability_43_Database.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Database.svg">SVG</a>
            <div class="img-title">Database</div>
        </div>
    </div>
    <div>
        <img alt="Device_Encryption" src="./img/Cisco/SAFE/Capability_43_Device_Encryption.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Device_Encryption.svg">SVG</a>
            <div class="img-title">Device_Encryption</div>
        </div>
    </div>
    <div>
        <img alt="Device_Profiling" src="./img/Cisco/SAFE/Capability_43_Device_Profiling.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Device_Profiling.svg">SVG</a>
            <div class="img-title">Device_Profiling</div>
        </div>
    </div>
    <div>
        <img alt="Device_Trajectory" src="./img/Cisco/SAFE/Capability_43_Device_Trajectory.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Device_Trajectory.svg">SVG</a>
            <div class="img-title">Device_Trajectory</div>
        </div>
    </div>
    <div>
        <img alt="Disk_Encryption" src="./img/Cisco/SAFE/Capability_43_Disk_Encryption.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Disk_Encryption.svg">SVG</a>
            <div class="img-title">Disk_Encryption</div>
        </div>
    </div>
    <div>
        <img alt="Distributed_Denial_of_Service_Protection" src="./img/Cisco/SAFE/Capability_43_Distributed_Denial_of_Service_Protection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Distributed_Denial_of_Service_Protection.svg">SVG</a>
            <div class="img-title">Distributed_Denial_of_Service_Protection</div>
        </div>
    </div>
    <div>
        <img alt="DNS_Security" src="./img/Cisco/SAFE/Capability_43_DNS_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_DNS_Security.svg">SVG</a>
            <div class="img-title">DNS_Security</div>
        </div>
    </div>
    <div>
        <img alt="Email_Encryption" src="./img/Cisco/SAFE/Capability_43_Email_Encryption.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Email_Encryption.svg">SVG</a>
            <div class="img-title">Email_Encryption</div>
        </div>
    </div>
    <div>
        <img alt="Email_Security" src="./img/Cisco/SAFE/Capability_43_Email_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Email_Security.svg">SVG</a>
            <div class="img-title">Email_Security</div>
        </div>
    </div>
    <div>
        <img alt="Fabric_Switching" src="./img/Cisco/SAFE/Capability_43_Fabric_Switching.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Fabric_Switching.svg">SVG</a>
            <div class="img-title">Fabric_Switching</div>
        </div>
    </div>
    <div>
        <img alt="Federation" src="./img/Cisco/SAFE/Capability_43_Federation.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Federation.svg">SVG</a>
            <div class="img-title">Federation</div>
        </div>
    </div>
    <div>
        <img alt="Fence" src="./img/Cisco/SAFE/Capability_43_Fence.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Fence.svg">SVG</a>
            <div class="img-title">Fence</div>
        </div>
    </div>
    <div>
        <img alt="File_Trajectory" src="./img/Cisco/SAFE/Capability_43_File_Trajectory.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_File_Trajectory.svg">SVG</a>
            <div class="img-title">File_Trajectory</div>
        </div>
    </div>
    <div>
        <img alt="Firewall_Virtual" src="./img/Cisco/SAFE/Capability_43_Firewall_Virtual.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Firewall_Virtual.svg">SVG</a>
            <div class="img-title">Firewall_Virtual</div>
        </div>
    </div>
    <div>
        <img alt="Firewall" src="./img/Cisco/SAFE/Capability_43_Firewall.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Firewall.svg">SVG</a>
            <div class="img-title">Firewall</div>
        </div>
    </div>
    <div>
        <img alt="Flow_Analytics" src="./img/Cisco/SAFE/Capability_43_Flow_Analytics.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Flow_Analytics.svg">SVG</a>
            <div class="img-title">Flow_Analytics</div>
        </div>
    </div>
    <div>
        <img alt="FSO" src="./img/Cisco/SAFE/Capability_43_FSO.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_FSO.svg">SVG</a>
            <div class="img-title">FSO</div>
        </div>
    </div>
    <div>
        <img alt="Guard" src="./img/Cisco/SAFE/Capability_43_Guard.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Guard.svg">SVG</a>
            <div class="img-title">Guard</div>
        </div>
    </div>
    <div>
        <img alt="Host_Context" src="./img/Cisco/SAFE/Capability_43_Host_Context.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Host_Context.svg">SVG</a>
            <div class="img-title">Host_Context</div>
        </div>
    </div>
    <div>
        <img alt="HVAC" src="./img/Cisco/SAFE/Capability_43_HVAC.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_HVAC.svg">SVG</a>
            <div class="img-title">HVAC</div>
        </div>
    </div>
    <div>
        <img alt="Identity" src="./img/Cisco/SAFE/Capability_43_Identity.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Identity.svg">SVG</a>
            <div class="img-title">Identity</div>
        </div>
    </div>
    <div>
        <img alt="Intrusion_Detection" src="./img/Cisco/SAFE/Capability_43_Intrusion_Detection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Intrusion_Detection.svg">SVG</a>
            <div class="img-title">Intrusion_Detection</div>
        </div>
    </div>
    <div>
        <img alt="Intrusion_Prevention" src="./img/Cisco/SAFE/Capability_43_Intrusion_Prevention.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Intrusion_Prevention.svg">SVG</a>
            <div class="img-title">Intrusion_Prevention</div>
        </div>
    </div>
    <div>
        <img alt="L2_Switching_Virtual" src="./img/Cisco/SAFE/Capability_43_L2_Switching_Virtual.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_L2_Switching_Virtual.svg">SVG</a>
            <div class="img-title">L2_Switching_Virtual</div>
        </div>
    </div>
    <div>
        <img alt="L2_Switching" src="./img/Cisco/SAFE/Capability_43_L2_Switching.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_L2_Switching.svg">SVG</a>
            <div class="img-title">L2_Switching</div>
        </div>
    </div>
    <div>
        <img alt="L2-L3_Network_Virtual" src="./img/Cisco/SAFE/Capability_43_L2-L3_Network_Virtual.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_L2-L3_Network_Virtual.svg">SVG</a>
            <div class="img-title">L2-L3_Network_Virtual</div>
        </div>
    </div>
    <div>
        <img alt="L2-L3_Network" src="./img/Cisco/SAFE/Capability_43_L2-L3_Network.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_L2-L3_Network.svg">SVG</a>
            <div class="img-title">L2-L3_Network</div>
        </div>
    </div>
    <div>
        <img alt="L3_Switching" src="./img/Cisco/SAFE/Capability_43_L3_Switching.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_L3_Switching.svg">SVG</a>
            <div class="img-title">L3_Switching</div>
        </div>
    </div>
    <div>
        <img alt="Load_Balancer" src="./img/Cisco/SAFE/Capability_43_Load_Balancer.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Load_Balancer.svg">SVG</a>
            <div class="img-title">Load_Balancer</div>
        </div>
    </div>
    <div>
        <img alt="Logging_Reporting" src="./img/Cisco/SAFE/Capability_43_Logging_Reporting.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Logging_Reporting.svg">SVG</a>
            <div class="img-title">Logging_Reporting</div>
        </div>
    </div>
    <div>
        <img alt="Malware_Sandbox" src="./img/Cisco/SAFE/Capability_43_Malware_Sandbox.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Malware_Sandbox.svg">SVG</a>
            <div class="img-title">Malware_Sandbox</div>
        </div>
    </div>
    <div>
        <img alt="Microsegmentation" src="./img/Cisco/SAFE/Capability_43_Microsegmentation.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Microsegmentation.svg">SVG</a>
            <div class="img-title">Microsegmentation</div>
        </div>
    </div>
    <div>
        <img alt="Mobile_Device_Management" src="./img/Cisco/SAFE/Capability_43_Mobile_Device_Management.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Mobile_Device_Management.svg">SVG</a>
            <div class="img-title">Mobile_Device_Management</div>
        </div>
    </div>
    <div>
        <img alt="Monitoring" src="./img/Cisco/SAFE/Capability_43_Monitoring.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Monitoring.svg">SVG</a>
            <div class="img-title">Monitoring</div>
        </div>
    </div>
    <div>
        <img alt="Multi-Factor_Authentication" src="./img/Cisco/SAFE/Capability_43_Multi-Factor_Authentication.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Multi-Factor_Authentication.svg">SVG</a>
            <div class="img-title">Multi-Factor_Authentication</div>
        </div>
    </div>
    <div>
        <img alt="Name_Resolution" src="./img/Cisco/SAFE/Capability_43_Name_Resolution.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Name_Resolution.svg">SVG</a>
            <div class="img-title">Name_Resolution</div>
        </div>
    </div>
    <div>
        <img alt="Network_Anti_Malware" src="./img/Cisco/SAFE/Capability_43_Network_Anti_Malware.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Network_Anti_Malware.svg">SVG</a>
            <div class="img-title">Network_Anti_Malware</div>
        </div>
    </div>
    <div>
        <img alt="Policy_Configuration" src="./img/Cisco/SAFE/Capability_43_Policy_Configuration.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Policy_Configuration.svg">SVG</a>
            <div class="img-title">Policy_Configuration</div>
        </div>
    </div>
    <div>
        <img alt="Posture_Assessment" src="./img/Cisco/SAFE/Capability_43_Posture_Assessment.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Posture_Assessment.svg">SVG</a>
            <div class="img-title">Posture_Assessment</div>
        </div>
    </div>
    <div>
        <img alt="PPE" src="./img/Cisco/SAFE/Capability_43_PPE.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_PPE.svg">SVG</a>
            <div class="img-title">PPE</div>
        </div>
    </div>
    <div>
        <img alt="Quarantine" src="./img/Cisco/SAFE/Capability_43_Quarantine.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Quarantine.svg">SVG</a>
            <div class="img-title">Quarantine</div>
        </div>
    </div>
    <div>
        <img alt="Remediate" src="./img/Cisco/SAFE/Capability_43_Remediate.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Remediate.svg">SVG</a>
            <div class="img-title">Remediate</div>
        </div>
    </div>
    <div>
        <img alt="Remote_Access" src="./img/Cisco/SAFE/Capability_43_Remote_Access.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Remote_Access.svg">SVG</a>
            <div class="img-title">Remote_Access</div>
        </div>
    </div>
    <div>
        <img alt="RoomAccess" src="./img/Cisco/SAFE/Capability_43_RoomAccess.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_RoomAccess.svg">SVG</a>
            <div class="img-title">RoomAccess</div>
        </div>
    </div>
    <div>
        <img alt="Routing" src="./img/Cisco/SAFE/Capability_43_Routing.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Routing.svg">SVG</a>
            <div class="img-title">Routing</div>
        </div>
    </div>
    <div>
        <img alt="Secure_API_Gateway" src="./img/Cisco/SAFE/Capability_43_Secure_API_Gateway.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Secure_API_Gateway.svg">SVG</a>
            <div class="img-title">Secure_API_Gateway</div>
        </div>
    </div>
    <div>
        <img alt="Secure_File_Share" src="./img/Cisco/SAFE/Capability_43_Secure_File_Share.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Secure_File_Share.svg">SVG</a>
            <div class="img-title">Secure_File_Share</div>
        </div>
    </div>
    <div>
        <img alt="Secure_X" src="./img/Cisco/SAFE/Capability_43_Secure_X.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Secure_X.svg">SVG</a>
            <div class="img-title">Secure_X</div>
        </div>
    </div>
    <div>
        <img alt="ServerBased_Security" src="./img/Cisco/SAFE/Capability_43_ServerBased_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_ServerBased_Security.svg">SVG</a>
            <div class="img-title">ServerBased_Security</div>
        </div>
    </div>
    <div>
        <img alt="SOAR_XDR" src="./img/Cisco/SAFE/Capability_43_SOAR_XDR.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_SOAR_XDR.svg">SVG</a>
            <div class="img-title">SOAR_XDR</div>
        </div>
    </div>
    <div>
        <img alt="Storage" src="./img/Cisco/SAFE/Capability_43_Storage.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Storage.svg">SVG</a>
            <div class="img-title">Storage</div>
        </div>
    </div>
    <div>
        <img alt="Switch" src="./img/Cisco/SAFE/Capability_43_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Switch.svg">SVG</a>
            <div class="img-title">Switch</div>
        </div>
    </div>
    <div>
        <img alt="Tagging" src="./img/Cisco/SAFE/Capability_43_Tagging.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Tagging.svg">SVG</a>
            <div class="img-title">Tagging</div>
        </div>
    </div>
    <div>
        <img alt="Threat_Intelligence" src="./img/Cisco/SAFE/Capability_43_Threat_Intelligence.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Threat_Intelligence.svg">SVG</a>
            <div class="img-title">Threat_Intelligence</div>
        </div>
    </div>
    <div>
        <img alt="Time_Synchronization" src="./img/Cisco/SAFE/Capability_43_Time_Synchronization.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Time_Synchronization.svg">SVG</a>
            <div class="img-title">Time_Synchronization</div>
        </div>
    </div>
    <div>
        <img alt="TLS_Offload" src="./img/Cisco/SAFE/Capability_43_TLS_Offload.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_TLS_Offload.svg">SVG</a>
            <div class="img-title">TLS_Offload</div>
        </div>
    </div>
    <div>
        <img alt="USB-Security" src="./img/Cisco/SAFE/Capability_43_USB-Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_USB-Security.svg">SVG</a>
            <div class="img-title">USB-Security</div>
        </div>
    </div>
    <div>
        <img alt="User" src="./img/Cisco/SAFE/Capability_43_User.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_User.svg">SVG</a>
            <div class="img-title">User</div>
        </div>
    </div>
    <div>
        <img alt="VDC_VPC_OTV_Microsegmentation" src="./img/Cisco/SAFE/Capability_43_VDC_VPC_OTV_Microsegmentation.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_VDC_VPC_OTV_Microsegmentation.svg">SVG</a>
            <div class="img-title">VDC_VPC_OTV_Microsegmentation</div>
        </div>
    </div>
    <div>
        <img alt="Video" src="./img/Cisco/SAFE/Capability_43_Video.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Video.svg">SVG</a>
            <div class="img-title">Video</div>
        </div>
    </div>
    <div>
        <img alt="VideoCamera" src="./img/Cisco/SAFE/Capability_43_VideoCamera.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_VideoCamera.svg">SVG</a>
            <div class="img-title">VideoCamera</div>
        </div>
    </div>
    <div>
        <img alt="Virtual_Private_Network" src="./img/Cisco/SAFE/Capability_43_Virtual_Private_Network.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Virtual_Private_Network.svg">SVG</a>
            <div class="img-title">Virtual_Private_Network</div>
        </div>
    </div>
    <div>
        <img alt="Virtualized_Capabilities" src="./img/Cisco/SAFE/Capability_43_Virtualized_Capabilities.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Virtualized_Capabilities.svg">SVG</a>
            <div class="img-title">Virtualized_Capabilities</div>
        </div>
    </div>
    <div>
        <img alt="Voice" src="./img/Cisco/SAFE/Capability_43_Voice.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Voice.svg">SVG</a>
            <div class="img-title">Voice</div>
        </div>
    </div>
    <div>
        <img alt="VPN_Concentrator" src="./img/Cisco/SAFE/Capability_43_VPN_Concentrator.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_VPN_Concentrator.svg">SVG</a>
            <div class="img-title">VPN_Concentrator</div>
        </div>
    </div>
    <div>
        <img alt="Vulnerability_Management" src="./img/Cisco/SAFE/Capability_43_Vulnerability_Management.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Vulnerability_Management.svg">SVG</a>
            <div class="img-title">Vulnerability_Management</div>
        </div>
    </div>
    <div>
        <img alt="Web_Application_Firewall" src="./img/Cisco/SAFE/Capability_43_Web_Application_Firewall.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Web_Application_Firewall.svg">SVG</a>
            <div class="img-title">Web_Application_Firewall</div>
        </div>
    </div>
    <div>
        <img alt="Web_Reputation_Filtering_DCS" src="./img/Cisco/SAFE/Capability_43_Web_Reputation_Filtering_DCS.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Web_Reputation_Filtering_DCS.svg">SVG</a>
            <div class="img-title">Web_Reputation_Filtering_DCS</div>
        </div>
    </div>
    <div>
        <img alt="Web_Security" src="./img/Cisco/SAFE/Capability_43_Web_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Web_Security.svg">SVG</a>
            <div class="img-title">Web_Security</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Connection" src="./img/Cisco/SAFE/Capability_43_Wireless_Connection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Wireless_Connection.svg">SVG</a>
            <div class="img-title">Wireless_Connection</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Intrusion_Detection_System" src="./img/Cisco/SAFE/Capability_43_Wireless_Intrusion_Detection_System.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Wireless_Intrusion_Detection_System.svg">SVG</a>
            <div class="img-title">Wireless_Intrusion_Detection_System</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Intrusion_Prevention_System" src="./img/Cisco/SAFE/Capability_43_Wireless_Intrusion_Prevention_System.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Wireless_Intrusion_Prevention_System.svg">SVG</a>
            <div class="img-title">Wireless_Intrusion_Prevention_System</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Rogue_Detection" src="./img/Cisco/SAFE/Capability_43_Wireless_Rogue_Detection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Capability_43_Wireless_Rogue_Detection.svg">SVG</a>
            <div class="img-title">Wireless_Rogue_Detection</div>
        </div>
    </div>
</div>


### Threat

<div class="icon-table">
    <div>
        <img alt="Advanced_Threat" src="./img/Cisco/SAFE/Threat_54_Advanced_Threat.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Advanced_Threat.svg">SVG</a>
            <div class="img-title">Advanced_Threat</div>
        </div>
    </div>
    <div>
        <img alt="Botnets_DDOS" src="./img/Cisco/SAFE/Threat_54_Botnets_DDOS.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Botnets_DDOS.svg">SVG</a>
            <div class="img-title">Botnets_DDOS</div>
        </div>
    </div>
    <div>
        <img alt="BYOD_Theat" src="./img/Cisco/SAFE/Threat_54_BYOD_Theat.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_BYOD_Theat.svg">SVG</a>
            <div class="img-title">BYOD_Theat</div>
        </div>
    </div>
    <div>
        <img alt="C2_Sites" src="./img/Cisco/SAFE/Threat_54_C2_Sites.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_C2_Sites.svg">SVG</a>
            <div class="img-title">C2_Sites</div>
        </div>
    </div>
    <div>
        <img alt="Empty_Threat" src="./img/Cisco/SAFE/Threat_54_Empty_Threat.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Empty_Threat.svg">SVG</a>
            <div class="img-title">Empty_Threat</div>
        </div>
    </div>
    <div>
        <img alt="Exfiltration" src="./img/Cisco/SAFE/Threat_54_Exfiltration.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Exfiltration.svg">SVG</a>
            <div class="img-title">Exfiltration</div>
        </div>
    </div>
    <div>
        <img alt="Exploit_Redirection" src="./img/Cisco/SAFE/Threat_54_Exploit_Redirection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Exploit_Redirection.svg">SVG</a>
            <div class="img-title">Exploit_Redirection</div>
        </div>
    </div>
    <div>
        <img alt="Malicious_Device" src="./img/Cisco/SAFE/Threat_54_Malicious_Device.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malicious_Device.svg">SVG</a>
            <div class="img-title">Malicious_Device</div>
        </div>
    </div>
    <div>
        <img alt="Malicious_Insider_1" src="./img/Cisco/SAFE/Threat_54_Malicious_Insider_1.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malicious_Insider_1.svg">SVG</a>
            <div class="img-title">Malicious_Insider_1</div>
        </div>
    </div>
    <div>
        <img alt="Malicious_Insider_2" src="./img/Cisco/SAFE/Threat_54_Malicious_Insider_2.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malicious_Insider_2.svg">SVG</a>
            <div class="img-title">Malicious_Insider_2</div>
        </div>
    </div>
    <div>
        <img alt="Malware" src="./img/Cisco/SAFE/Threat_54_Malware.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malware.svg">SVG</a>
            <div class="img-title">Malware</div>
        </div>
    </div>
    <div>
        <img alt="Man_In_The_Middle" src="./img/Cisco/SAFE/Threat_54_Man_In_The_Middle.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Man_In_The_Middle.svg">SVG</a>
            <div class="img-title">Man_In_The_Middle</div>
        </div>
    </div>
    <div>
        <img alt="Phish_Link" src="./img/Cisco/SAFE/Threat_54_Phish_Link.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Phish_Link.svg">SVG</a>
            <div class="img-title">Phish_Link</div>
        </div>
    </div>
    <div>
        <img alt="Phishing" src="./img/Cisco/SAFE/Threat_54_Phishing.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Phishing.svg">SVG</a>
            <div class="img-title">Phishing</div>
        </div>
    </div>
    <div>
        <img alt="Rogue" src="./img/Cisco/SAFE/Threat_54_Rogue.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Rogue.svg">SVG</a>
            <div class="img-title">Rogue</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_1" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_1.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_1.svg">SVG</a>
            <div class="img-title">Social_Engineering_1</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_2" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_2.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_2.svg">SVG</a>
            <div class="img-title">Social_Engineering_2</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_3" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_3.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_3.svg">SVG</a>
            <div class="img-title">Social_Engineering_3</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_4_" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_4_.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_4_.svg">SVG</a>
            <div class="img-title">Social_Engineering_4_</div>
        </div>
    </div>
    <div>
        <img alt="Spying" src="./img/Cisco/SAFE/Threat_54_Spying.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Spying.svg">SVG</a>
            <div class="img-title">Spying</div>
        </div>
    </div>
    <div>
        <img alt="Unwitting_Threat_Actor" src="./img/Cisco/SAFE/Threat_54_Unwitting_Threat_Actor.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Unwitting_Threat_Actor.svg">SVG</a>
            <div class="img-title">Unwitting_Threat_Actor</div>
        </div>
    </div>
    <div>
        <img alt="Virus" src="./img/Cisco/SAFE/Threat_54_Virus.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Virus.svg">SVG</a>
            <div class="img-title">Virus</div>
        </div>
    </div>
</div>

### Attach Surface

<div class="icon-table">
    <div>
        <img alt="Advanced_Threat" src="./img/Cisco/SAFE/Threat_54_Advanced_Threat.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Advanced_Threat.svg">SVG</a>
            <div class="img-title">Advanced_Threat</div>
        </div>
    </div>
    <div>
        <img alt="Botnets_DDOS" src="./img/Cisco/SAFE/Threat_54_Botnets_DDOS.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Botnets_DDOS.svg">SVG</a>
            <div class="img-title">Botnets_DDOS</div>
        </div>
    </div>
    <div>
        <img alt="BYOD_Theat" src="./img/Cisco/SAFE/Threat_54_BYOD_Theat.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_BYOD_Theat.svg">SVG</a>
            <div class="img-title">BYOD_Theat</div>
        </div>
    </div>
    <div>
        <img alt="C2_Sites" src="./img/Cisco/SAFE/Threat_54_C2_Sites.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_C2_Sites.svg">SVG</a>
            <div class="img-title">C2_Sites</div>
        </div>
    </div>
    <div>
        <img alt="Empty_Threat" src="./img/Cisco/SAFE/Threat_54_Empty_Threat.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Empty_Threat.svg">SVG</a>
            <div class="img-title">Empty_Threat</div>
        </div>
    </div>
    <div>
        <img alt="Exfiltration" src="./img/Cisco/SAFE/Threat_54_Exfiltration.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Exfiltration.svg">SVG</a>
            <div class="img-title">Exfiltration</div>
        </div>
    </div>
    <div>
        <img alt="Exploit_Redirection" src="./img/Cisco/SAFE/Threat_54_Exploit_Redirection.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Exploit_Redirection.svg">SVG</a>
            <div class="img-title">Exploit_Redirection</div>
        </div>
    </div>
    <div>
        <img alt="Malicious_Device" src="./img/Cisco/SAFE/Threat_54_Malicious_Device.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malicious_Device.svg">SVG</a>
            <div class="img-title">Malicious_Device</div>
        </div>
    </div>
    <div>
        <img alt="Malicious_Insider_1" src="./img/Cisco/SAFE/Threat_54_Malicious_Insider_1.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malicious_Insider_1.svg">SVG</a>
            <div class="img-title">Malicious_Insider_1</div>
        </div>
    </div>
    <div>
        <img alt="Malicious_Insider_2" src="./img/Cisco/SAFE/Threat_54_Malicious_Insider_2.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malicious_Insider_2.svg">SVG</a>
            <div class="img-title">Malicious_Insider_2</div>
        </div>
    </div>
    <div>
        <img alt="Malware" src="./img/Cisco/SAFE/Threat_54_Malware.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Malware.svg">SVG</a>
            <div class="img-title">Malware</div>
        </div>
    </div>
    <div>
        <img alt="Man_In_The_Middle" src="./img/Cisco/SAFE/Threat_54_Man_In_The_Middle.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Man_In_The_Middle.svg">SVG</a>
            <div class="img-title">Man_In_The_Middle</div>
        </div>
    </div>
    <div>
        <img alt="Phish_Link" src="./img/Cisco/SAFE/Threat_54_Phish_Link.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Phish_Link.svg">SVG</a>
            <div class="img-title">Phish_Link</div>
        </div>
    </div>
    <div>
        <img alt="Phishing" src="./img/Cisco/SAFE/Threat_54_Phishing.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Phishing.svg">SVG</a>
            <div class="img-title">Phishing</div>
        </div>
    </div>
    <div>
        <img alt="Rogue" src="./img/Cisco/SAFE/Threat_54_Rogue.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Rogue.svg">SVG</a>
            <div class="img-title">Rogue</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_1" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_1.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_1.svg">SVG</a>
            <div class="img-title">Social_Engineering_1</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_2" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_2.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_2.svg">SVG</a>
            <div class="img-title">Social_Engineering_2</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_3" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_3.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_3.svg">SVG</a>
            <div class="img-title">Social_Engineering_3</div>
        </div>
    </div>
    <div>
        <img alt="Social_Engineering_4_" src="./img/Cisco/SAFE/Threat_54_Social_Engineering_4_.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Social_Engineering_4_.svg">SVG</a>
            <div class="img-title">Social_Engineering_4_</div>
        </div>
    </div>
    <div>
        <img alt="Spying" src="./img/Cisco/SAFE/Threat_54_Spying.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Spying.svg">SVG</a>
            <div class="img-title">Spying</div>
        </div>
    </div>
    <div>
        <img alt="Unwitting_Threat_Actor" src="./img/Cisco/SAFE/Threat_54_Unwitting_Threat_Actor.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Unwitting_Threat_Actor.svg">SVG</a>
            <div class="img-title">Unwitting_Threat_Actor</div>
        </div>
    </div>
    <div>
        <img alt="Virus" src="./img/Cisco/SAFE/Threat_54_Virus.png" />
        <div>
            <a href="./img/Cisco/SAFE/Threat_54_Virus.svg">SVG</a>
            <div class="img-title">Virus</div>
        </div>
    </div>
</div>

### Architecture

<div class="icon-table">
    <div>
        <img alt="Access_Switch" src="./img/Cisco/SAFE/Arch_63_Access_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Access_Switch.svg">SVG</a>
            <div class="img-title">Access_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Actuator" src="./img/Cisco/SAFE/Arch_63_Actuator.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Actuator.svg">SVG</a>
            <div class="img-title">Actuator</div>
        </div>
    </div>
    <div>
        <img alt="Adaptive_Security_Appliance" src="./img/Cisco/SAFE/Arch_63_Adaptive_Security_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Adaptive_Security_Appliance.svg">SVG</a>
            <div class="img-title">Adaptive_Security_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Application_Workspace_BLANK" src="./img/Cisco/SAFE/Arch_63_Application_Workspace_BLANK.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Application_Workspace_BLANK.svg">SVG</a>
            <div class="img-title">Application_Workspace_BLANK</div>
        </div>
    </div>
    <div>
        <img alt="Application_Workspace" src="./img/Cisco/SAFE/Arch_63_Application_Workspace.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Application_Workspace.svg">SVG</a>
            <div class="img-title">Application_Workspace</div>
        </div>
    </div>
    <div>
        <img alt="Automated_System" src="./img/Cisco/SAFE/Arch_63_Automated_System.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Automated_System.svg">SVG</a>
            <div class="img-title">Automated_System</div>
        </div>
    </div>
    <div>
        <img alt="Blade_Server" src="./img/Cisco/SAFE/Arch_63_Blade_Server.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Blade_Server.svg">SVG</a>
            <div class="img-title">Blade_Server</div>
        </div>
    </div>
    <div>
        <img alt="Catalyst_Data_Center_Switch" src="./img/Cisco/SAFE/Arch_63_Catalyst_Data_Center_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Catalyst_Data_Center_Switch.svg">SVG</a>
            <div class="img-title">Catalyst_Data_Center_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Cell_Tower_Optn1" src="./img/Cisco/SAFE/Arch_63_Cell_Tower_Optn1.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Cell_Tower_Optn1.svg">SVG</a>
            <div class="img-title">Cell_Tower_Optn1</div>
        </div>
    </div>
    <div>
        <img alt="Cell_Tower_Optn2" src="./img/Cisco/SAFE/Arch_63_Cell_Tower_Optn2.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Cell_Tower_Optn2.svg">SVG</a>
            <div class="img-title">Cell_Tower_Optn2</div>
        </div>
    </div>
    <div>
        <img alt="Cisco_Appliance" src="./img/Cisco/SAFE/Arch_63_Cisco_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Cisco_Appliance.svg">SVG</a>
            <div class="img-title">Cisco_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Cloud_Security" src="./img/Cisco/SAFE/Arch_63_Cloud_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Cloud_Security.svg">SVG</a>
            <div class="img-title">Cloud_Security</div>
        </div>
    </div>
    <div>
        <img alt="Core_Switch" src="./img/Cisco/SAFE/Arch_63_Core_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Core_Switch.svg">SVG</a>
            <div class="img-title">Core_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Corporate_Device" src="./img/Cisco/SAFE/Arch_63_Corporate_Device.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Corporate_Device.svg">SVG</a>
            <div class="img-title">Corporate_Device</div>
        </div>
    </div>
    <div>
        <img alt="Corporate_Wireless_Device" src="./img/Cisco/SAFE/Arch_63_Corporate_Wireless_Device.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Corporate_Wireless_Device.svg">SVG</a>
            <div class="img-title">Corporate_Wireless_Device</div>
        </div>
    </div>
    <div>
        <img alt="DDOS_Protection_Appliance" src="./img/Cisco/SAFE/Arch_63_DDOS_Protection_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_DDOS_Protection_Appliance.svg">SVG</a>
            <div class="img-title">DDOS_Protection_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Distribution_Switch" src="./img/Cisco/SAFE/Arch_63_Distribution_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Distribution_Switch.svg">SVG</a>
            <div class="img-title">Distribution_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Email_Security" src="./img/Cisco/SAFE/Arch_63_Email_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Email_Security.svg">SVG</a>
            <div class="img-title">Email_Security</div>
        </div>
    </div>
    <div>
        <img alt="Endpoint_Concentrator" src="./img/Cisco/SAFE/Arch_63_Endpoint_Concentrator.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Endpoint_Concentrator.svg">SVG</a>
            <div class="img-title">Endpoint_Concentrator</div>
        </div>
    </div>
    <div>
        <img alt="Environmental_Controls" src="./img/Cisco/SAFE/Arch_63_Environmental_Controls.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Environmental_Controls.svg">SVG</a>
            <div class="img-title">Environmental_Controls</div>
        </div>
    </div>
    <div>
        <img alt="Fabric_Switch" src="./img/Cisco/SAFE/Arch_63_Fabric_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Fabric_Switch.svg">SVG</a>
            <div class="img-title">Fabric_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Firepower_Appliance_BLANK" src="./img/Cisco/SAFE/Arch_63_Firepower_Appliance_BLANK.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Firepower_Appliance_BLANK.svg">SVG</a>
            <div class="img-title">Firepower_Appliance_BLANK</div>
        </div>
    </div>
    <div>
        <img alt="Firepower_Appliance" src="./img/Cisco/SAFE/Arch_63_Firepower_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Firepower_Appliance.svg">SVG</a>
            <div class="img-title">Firepower_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Firepower_Management_Center_BLANK" src="./img/Cisco/SAFE/Arch_63_Firepower_Management_Center_BLANK.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Firepower_Management_Center_BLANK.svg">SVG</a>
            <div class="img-title">Firepower_Management_Center_BLANK</div>
        </div>
    </div>
    <div>
        <img alt="Firepower_Management_Center" src="./img/Cisco/SAFE/Arch_63_Firepower_Management_Center.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Firepower_Management_Center.svg">SVG</a>
            <div class="img-title">Firepower_Management_Center</div>
        </div>
    </div>
    <div>
        <img alt="Firewall" src="./img/Cisco/SAFE/Arch_63_Firewall.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Firewall.svg">SVG</a>
            <div class="img-title">Firewall</div>
        </div>
    </div>
    <div>
        <img alt="Flow_Connector" src="./img/Cisco/SAFE/Arch_63_Flow_Connector.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Flow_Connector.svg">SVG</a>
            <div class="img-title">Flow_Connector</div>
        </div>
    </div>
    <div>
        <img alt="Flow_Sensor" src="./img/Cisco/SAFE/Arch_63_Flow_Sensor.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Flow_Sensor.svg">SVG</a>
            <div class="img-title">Flow_Sensor</div>
        </div>
    </div>
    <div>
        <img alt="Generic_Appliance" src="./img/Cisco/SAFE/Arch_63_Generic_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Generic_Appliance.svg">SVG</a>
            <div class="img-title">Generic_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Identity_Directory" src="./img/Cisco/SAFE/Arch_63_Identity_Directory.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Identity_Directory.svg">SVG</a>
            <div class="img-title">Identity_Directory</div>
        </div>
    </div>
    <div>
        <img alt="Intrusion_Prevention" src="./img/Cisco/SAFE/Arch_63_Intrusion_Prevention.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Intrusion_Prevention.svg">SVG</a>
            <div class="img-title">Intrusion_Prevention</div>
        </div>
    </div>
    <div>
        <img alt="Leaf_Switch" src="./img/Cisco/SAFE/Arch_63_Leaf_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Leaf_Switch.svg">SVG</a>
            <div class="img-title">Leaf_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Load_Balancer" src="./img/Cisco/SAFE/Arch_63_Load_Balancer.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Load_Balancer.svg">SVG</a>
            <div class="img-title">Load_Balancer</div>
        </div>
    </div>
    <div>
        <img alt="Log_Collector" src="./img/Cisco/SAFE/Arch_63_Log_Collector.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Log_Collector.svg">SVG</a>
            <div class="img-title">Log_Collector</div>
        </div>
    </div>
    <div>
        <img alt="Management_Console" src="./img/Cisco/SAFE/Arch_63_Management_Console.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Management_Console.svg">SVG</a>
            <div class="img-title">Management_Console</div>
        </div>
    </div>
    <div>
        <img alt="MDM_Appliance" src="./img/Cisco/SAFE/Arch_63_MDM_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_MDM_Appliance.svg">SVG</a>
            <div class="img-title">MDM_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Mobile" src="./img/Cisco/SAFE/Arch_63_Mobile.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Mobile.svg">SVG</a>
            <div class="img-title">Mobile</div>
        </div>
    </div>
    <div>
        <img alt="Monitoring" src="./img/Cisco/SAFE/Arch_63_Monitoring.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Monitoring.svg">SVG</a>
            <div class="img-title">Monitoring</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_1kv" src="./img/Cisco/SAFE/Arch_63_Nexus_1kv.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Nexus_1kv.svg">SVG</a>
            <div class="img-title">Nexus_1kv</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_Data_Center_Switch" src="./img/Cisco/SAFE/Arch_63_Nexus_Data_Center_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Nexus_Data_Center_Switch.svg">SVG</a>
            <div class="img-title">Nexus_Data_Center_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_Fabric_Switch" src="./img/Cisco/SAFE/Arch_63_Nexus_Fabric_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Nexus_Fabric_Switch.svg">SVG</a>
            <div class="img-title">Nexus_Fabric_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Nexus_Switch" src="./img/Cisco/SAFE/Arch_63_Nexus_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Nexus_Switch.svg">SVG</a>
            <div class="img-title">Nexus_Switch</div>
        </div>
    </div>
    <div>
        <img alt="NTP" src="./img/Cisco/SAFE/Arch_63_NTP.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_NTP.svg">SVG</a>
            <div class="img-title">NTP</div>
        </div>
    </div>
    <div>
        <img alt="Phone" src="./img/Cisco/SAFE/Arch_63_Phone.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Phone.svg">SVG</a>
            <div class="img-title">Phone</div>
        </div>
    </div>
    <div>
        <img alt="Policy" src="./img/Cisco/SAFE/Arch_63_Policy.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Policy.svg">SVG</a>
            <div class="img-title">Policy</div>
        </div>
    </div>
    <div>
        <img alt="Posture_Assessment" src="./img/Cisco/SAFE/Arch_63_Posture_Assessment.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Posture_Assessment.svg">SVG</a>
            <div class="img-title">Posture_Assessment</div>
        </div>
    </div>
    <div>
        <img alt="Radware_Appliance" src="./img/Cisco/SAFE/Arch_63_Radware_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Radware_Appliance.svg">SVG</a>
            <div class="img-title">Radware_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="Router" src="./img/Cisco/SAFE/Arch_63_Router.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Router.svg">SVG</a>
            <div class="img-title">Router</div>
        </div>
    </div>
    <div>
        <img alt="Sandbox_Appliance" src="./img/Cisco/SAFE/Arch_63_Sandbox_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Sandbox_Appliance.svg">SVG</a>
            <div class="img-title">Sandbox_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="SD_Controller" src="./img/Cisco/SAFE/Arch_63_SD_Controller.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_SD_Controller.svg">SVG</a>
            <div class="img-title">SD_Controller</div>
        </div>
    </div>
    <div>
        <img alt="SD_WAN" src="./img/Cisco/SAFE/Arch_63_SD_WAN.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_SD_WAN.svg">SVG</a>
            <div class="img-title">SD_WAN</div>
        </div>
    </div>
    <div>
        <img alt="Secure_DNS" src="./img/Cisco/SAFE/Arch_63_Secure_DNS.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Secure_DNS.svg">SVG</a>
            <div class="img-title">Secure_DNS</div>
        </div>
    </div>
    <div>
        <img alt="Secure_Server" src="./img/Cisco/SAFE/Arch_63_Secure_Server.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Secure_Server.svg">SVG</a>
            <div class="img-title">Secure_Server</div>
        </div>
    </div>
    <div>
        <img alt="Secure_X" src="./img/Cisco/SAFE/Arch_63_Secure_X.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Secure_X.svg">SVG</a>
            <div class="img-title">Secure_X</div>
        </div>
    </div>
    <div>
        <img alt="Sensor" src="./img/Cisco/SAFE/Arch_63_Sensor.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Sensor.svg">SVG</a>
            <div class="img-title">Sensor</div>
        </div>
    </div>
    <div>
        <img alt="Server" src="./img/Cisco/SAFE/Arch_63_Server.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Server.svg">SVG</a>
            <div class="img-title">Server</div>
        </div>
    </div>
    <div>
        <img alt="SIEM" src="./img/Cisco/SAFE/Arch_63_SIEM.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_SIEM.svg">SVG</a>
            <div class="img-title">SIEM</div>
        </div>
    </div>
    <div>
        <img alt="Spine_Switch" src="./img/Cisco/SAFE/Arch_63_Spine_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Spine_Switch.svg">SVG</a>
            <div class="img-title">Spine_Switch</div>
        </div>
    </div>
    <div>
        <img alt="Storage" src="./img/Cisco/SAFE/Arch_63_Storage.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Storage.svg">SVG</a>
            <div class="img-title">Storage</div>
        </div>
    </div>
    <div>
        <img alt="Switch" src="./img/Cisco/SAFE/Arch_63_Switch.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Switch.svg">SVG</a>
            <div class="img-title">Switch</div>
        </div>
    </div>
    <div>
        <img alt="Tetration" src="./img/Cisco/SAFE/Arch_63_Tetration.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Tetration.svg">SVG</a>
            <div class="img-title">Tetration</div>
        </div>
    </div>
    <div>
        <img alt="TLS_Appliance" src="./img/Cisco/SAFE/Arch_63_TLS_Appliance.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_TLS_Appliance.svg">SVG</a>
            <div class="img-title">TLS_Appliance</div>
        </div>
    </div>
    <div>
        <img alt="UDP_Director" src="./img/Cisco/SAFE/Arch_63_UDP_Director.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_UDP_Director.svg">SVG</a>
            <div class="img-title">UDP_Director</div>
        </div>
    </div>
    <div>
        <img alt="Vehicle_Commercial" src="./img/Cisco/SAFE/Arch_63_Vehicle_Commercial.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Vehicle_Commercial.svg">SVG</a>
            <div class="img-title">Vehicle_Commercial</div>
        </div>
    </div>
    <div>
        <img alt="Vehicle_Consumer" src="./img/Cisco/SAFE/Arch_63_Vehicle_Consumer.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Vehicle_Consumer.svg">SVG</a>
            <div class="img-title">Vehicle_Consumer</div>
        </div>
    </div>
    <div>
        <img alt="Vehicle_Flight" src="./img/Cisco/SAFE/Arch_63_Vehicle_Flight.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Vehicle_Flight.svg">SVG</a>
            <div class="img-title">Vehicle_Flight</div>
        </div>
    </div>
    <div>
        <img alt="Video_Endpoint" src="./img/Cisco/SAFE/Arch_63_Video_Endpoint.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Video_Endpoint.svg">SVG</a>
            <div class="img-title">Video_Endpoint</div>
        </div>
    </div>
    <div>
        <img alt="VPN_Concentrator" src="./img/Cisco/SAFE/Arch_63_VPN_Concentrator.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_VPN_Concentrator.svg">SVG</a>
            <div class="img-title">VPN_Concentrator</div>
        </div>
    </div>
    <div>
        <img alt="Vulnerability_Management" src="./img/Cisco/SAFE/Arch_63_Vulnerability_Management.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Vulnerability_Management.svg">SVG</a>
            <div class="img-title">Vulnerability_Management</div>
        </div>
    </div>
    <div>
        <img alt="Web_App_Firewall" src="./img/Cisco/SAFE/Arch_63_Web_App_Firewall.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Web_App_Firewall.svg">SVG</a>
            <div class="img-title">Web_App_Firewall</div>
        </div>
    </div>
    <div>
        <img alt="Web_Filtering" src="./img/Cisco/SAFE/Arch_63_Web_Filtering.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Web_Filtering.svg">SVG</a>
            <div class="img-title">Web_Filtering</div>
        </div>
    </div>
    <div>
        <img alt="Web_Security" src="./img/Cisco/SAFE/Arch_63_Web_Security.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Web_Security.svg">SVG</a>
            <div class="img-title">Web_Security</div>
        </div>
    </div>
    <div>
        <img alt="Wide_Area_Application_Engine" src="./img/Cisco/SAFE/Arch_63_Wide_Area_Application_Engine.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Wide_Area_Application_Engine.svg">SVG</a>
            <div class="img-title">Wide_Area_Application_Engine</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Access_Point" src="./img/Cisco/SAFE/Arch_63_Wireless_Access_Point.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Wireless_Access_Point.svg">SVG</a>
            <div class="img-title">Wireless_Access_Point</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_Controller" src="./img/Cisco/SAFE/Arch_63_Wireless_Controller.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Wireless_Controller.svg">SVG</a>
            <div class="img-title">Wireless_Controller</div>
        </div>
    </div>
    <div>
        <img alt="Wireless_LAN_Controller" src="./img/Cisco/SAFE/Arch_63_Wireless_LAN_Controller.png" />
        <div>
            <a href="./img/Cisco/SAFE/Arch_63_Wireless_LAN_Controller.svg">SVG</a>
            <div class="img-title">Wireless_LAN_Controller</div>
        </div>
    </div>
</div>