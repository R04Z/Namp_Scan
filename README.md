
    mkdir scan_net_temp

    nmap -A -T4 -oX scan_net_temp/scan_results.xml <target>
    xsltproc scan_net_temp/scan_results.xml -o scan_net_temp/scan_results.html










