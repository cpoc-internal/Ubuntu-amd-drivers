# Ubuntu-AMD-drivers

ROCM drivers installation, this repository will help to install amdgpu Drivers,

1.Clone the repository in your Ubuntu server
```
git clone https://github.com/cpoc-internal/Ubuntu-amd-drivers.git
```
2. ROOT mode excute the sh file to install the drivers
```
chmod +x /root/Ubuntu-amd-drivers/install-amd-drivers-2204.sh
sudo -u root /root/Ubuntu-amd-drivers/install-amd-drivers-2204.sh
```
2.1 NOn ROOT
```
git clone https://github.com/cpoc-internal/Ubuntu-amd-drivers.git
cd Ubuntu-amd-drivers
chmod +x install-amd-drivers-2204.sh
 ./install-amd-drivers-2204.sh
```

