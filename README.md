## Install XMRig on Raspberry Pi

# Method 1: Install direct from the source


    sudo apt update && sudo apy upgrade -y
    sudo apt full-upgrade -y
    sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
    git clone https://github.com/xmrig/xmrig.git
    cd xmrig
    mkdir build
    cd build
    cmake ..
    make
    cd
    ./xmrig/build/xmrig -o gulf.moneroocean.stream:80 -u 4657q4dnsjLWtzeW4XN3wG9swFumWAZB9i1pegTLMxVAQy5E5AE8uif42kkHWcWc9vDcLUmzeCf3pV7mmrJQQqqe84dtASi -p Raspberry-Pi
  
  
For the last command you can customise it to your on preference by changing the,

<ul>
  <li>Pool name: -o</li>
  <li>Miner address: -u</li>
  <li>Miner name: -p</li>
</ul>

# Method 2 (Quick install)

If you are going to use Moneroocean As your Mining pool, Then you can use this to quickly install scripts on ANY Linux computer


    curl -s -L https://raw.githubusercontent.com/MoneroOcean/xmrig_setup/master/setup_moneroocean_miner.sh | bash -s 4657q4dnsjLWtzeW4XN3wG9swFumWAZB9i1pegTLMxVAQy5E5AE8uif42kkHWcWc9vDcLUmzeCf3pV7mmrJQQqqe84dtASi
    

At the end of this Command you can Change this XMR Address to yours.

Also if you want to see your progress, you can Visit [Moneroocean.stream](https://moneroocean.stream/)


#  Donate
    
    
This code is **100% free** to use, and we would greatly appreciate any donations to help support our work. If you'd like to donate, you can use the following cryptocurrency addresses:


    ETH:  0xB6C2F675eeA97d8D165D79D2098A92c06d3aB629

    XMR:  4657q4dnsjLWtzeW4XN3wG9swFumWAZB9i1pegTLMxVAQy5E5AE8uif42kkHWcWc9vDcLUmzeCf3pV7mmrJQQqqe84dtASi

    SOL:  B2fu1hVJtHWoZL3K4KNQB2gKeZtomVZA7kotX5ZvUFkp


Thank you for choosing our Xmrig install on Raspberry Pi Commands. We hope you find it useful and profitable

