# Check temperature
### CPU
**sensors** will show CPU, GPU temperature
```
sudo apt install lm-sensors
sudo sensors-detect
sensors
```
### Check the temperature of the disk
**smartmontools** will show the temperature of the disk
```
sudo apt install smartmontools
sudo smartctl -A /dev/sda | grep -i temperature
```
Expected
```
HDD	30–45°C
SSD	30–50°C
```

### Time
```
date
sudo timedatectl set-timezone Asia/Ho_Chi_Minh
timedatectl
```
