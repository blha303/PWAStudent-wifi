netctl
======

For distributions like Arch and others based on systemd

    Connection='wireless'
    Interface=wlp2s0 # or your wireless interface name
    Security='wpa-configsection'
    Description='tafe'
    IP='dhcp'
    TimeoutWPA=30
    WPAConfigSection=(
        'ssid="PWAStudent"'
        'key_mgmt=WPA-EAP'
        'eap=PEAP'
        'proto=WPA2'
        'phase2="auth=PAP"'
        'identity=STUDENTNUMBER'
        'password="PASSWORD"'
    )
