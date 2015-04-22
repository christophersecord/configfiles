# create OSX user

![OSX user creation dialog](create_user.png)

# create share

![OSX file share dialog](create_share.png)

# install mount.cifs

    apt-get install cifs-utils 

# edit fstab

    //192.168.56.1/database /mnt/database cifs user=serviceaccount,password=<password>,nounix,sec=ntlmssp,noperm,rw,noserverino 0 0