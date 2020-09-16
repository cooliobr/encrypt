# encrypt<br>
Encrypt for HLS<br>
apt install libtesseract3 libzvbi0<br>
mkdir /opt/iptv/encrypt/<br>
cd /opt/iptv/encrypt/<br>
scp -P1977 root@192.168.234.10:/opt/iptv/encrypt/ffmpeg .<br>
scp -P1977 root@192.168.234.10:/opt/iptv/encrypt/periodic_rekey.sh .<br>
cd /opt/iptv/dev/<br>
scp -P1977 root@192.168.234.10:/opt/iptv/dev/cron.sh .<br>
scp -P1977 root@192.168.234.10:/opt/iptv/dev/streaming_adaptive.sh .<br>
scp -P1977 root@192.168.234.10:/opt/iptv/dev/streaming_adaptive_enc.sh .<br>
