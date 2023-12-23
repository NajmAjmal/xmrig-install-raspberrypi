## Install XMRig on Raspberry Pi

> For other devices, Install XMRig [here](https://github.com/NajmAjmal/xmrig-install)

# Method 1: Install directly from the source


    sudo apt update && sudo apt full-upgrade -y
    sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
    git clone https://github.com/xmrig/xmrig.git
    cd xmrig
    mkdir build
    cd build
    cmake ..
    make
    cd
    ./xmrig/build/xmrig -o gulf.moneroocean.stream:80 -u 4657q4dnsjLWtzeW4XN3wG9swFumWAZB9i1pegTLMxVAQy5E5AE8uif42kkHWcWc9vDcLUmzeCf3pV7mmrJQQqqe84dtASi -p Raspberry-Pi
  
  
For the last command you can customize it to your on preference by changing the: 

  - Pool name: `-o`
  - Miner address: `-u`
  - Miner name: `-p`

# Method 2 (Quick install)

If you are going to use moneroocean As your Mining pool, then you can use this to quickly install scripts on ANY Debian Linux computer, although you cannot mine right away, you must run the `xmrig` command


    sudo wget -qO- https://cdn.najm.uk/install/xmrig | bash
    
Make sure to run the command like this to start mining (assuming you are in the `xmrig/build` directory): 

    ./xmrig -o <pool> -u <wallet_address> -p <miner_name>
    
View your mining progress at [Moneroocean.stream](https://moneroocean.stream/)


#  Donate
    
    
This code is **100% free** to use, and we would greatly appreciate any donations to help support our work. If you'd like to donate, you can use the following cryptocurrency addresses:


    BTC:  33qQZT1F5mWPvqM2bjbxQ3AsSYMXHpJsr6
    
    ETH:  0x641E1449c2f7883F245069f284fC880174b02094
    
    SOL:  AeYJTfLnok1nkncnvXFoKXmH8zrvtB7heNL9Q2sKNaFr
    
    XMR:  4657q4dnsjLWtzeW4XN3wG9swFumWAZB9i1pegTLMxVAQy5E5AE8uif42kkHWcWc9vDcLUmzeCf3pV7mmrJQQqqe84dtASi


Thank you for choosing our XMRig Install on Raspberry Pi. We hope you find it useful and profitable

