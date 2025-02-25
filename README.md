**Add repository in ubuntu**

    sudo add-apt-repository ppa:vbernat/haproxy-2.6 -y

**Install HAproxy**

        sudo apt update
        sudo apt install -y haproxy=2.6.\*

**Check HAproxy**

        haproxy -v

        systemctl status haproxy

        systemctl enable haproxy

**Configure HAProxy**

        sudo nano /etc/haproxy/haproxy.cfg
