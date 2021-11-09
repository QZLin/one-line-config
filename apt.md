# View Source
`cat /etc/apt/sources.list`

# Backup Source
`sudo cp /etc/apt/sources.list /etc/apt/sources.list.bak`

# Change Source
## ubuntu
`sudo sed -i 's/archive.ubuntu.com/mirrors.ustc.edu.cn/g' /etc/apt/sources.list`
## ubuntu arm/risc-v
`sudo sed -i 's/ports.ubuntu.com/mirrors.ustc.edu.cn/g' /etc/apt/sources.list`
