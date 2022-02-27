# Grafana-Loki

# Download
curl -O -L https://github.com/grafana/loki/releases/download/v2.4.2/loki-linux-amd64.zip
# extract the binary
unzip loki-linux-amd64.zip
# make sure it is executable
chmod a+x loki-linux-amd64


sudo apt-get install -y adduser libfontconfig1
wget https://dl.grafana.com/oss/release/grafana_8.4.0_amd64.deb
sudo dpkg -i grafana_8.4.0_amd64.deb
