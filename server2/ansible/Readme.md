1) İnventory dosyası düzenlenir.

2) roles/consul/vars/main.yml dosyasındaki internal_ip ve node_exporter variableleri düzenlenir.

3) roles/prometheus/vars/main.yml dosyasındaki consul değeri düzenlenir. Gerekirse alert aktif edilerek onada değer atanır.

4) Grafana yükelnedikten sonra /server2 nin altındaki furkan-dashboardı hostname:3000 den ilgili dashboard ı import et
