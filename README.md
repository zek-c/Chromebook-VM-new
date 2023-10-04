# Chromebook-VM


## Initial Setup
***You need a github account for this.***

```
1. First go to https://gitpod.io and sign in with github


2. Then make a workspace with a new repo (perferably an existing one in your github account.)

Now follow the instructions below.
```
## In the terminal paste the stuff below



# Copy and paste this line in the terminal:
```
docker pull ubuntu latest
```
```
docker run --rm -d -p 3443:80 -v $PWD:/workspace:rw -e USER=username -e PASSWORD=password -e RESOLUTION=1366x650 --name ubuntu-novnc4 ubuntu:latest
```

Then click on "Open Window" as seen in this image
<br>
![Image](https://cdn.discordapp.com/attachments/741533658674102352/970189978070052946/unknown.png)
<br>
and ur done





# For Ubuntu/Linux Beginners

### First you want to install everything needed.
Copy these lines:

```
sudo echo "i am a loser" > loser.txt
```
```
sudo nano /etc/rc.local
```
Add the following line to the file before the exit 0 line:
```
watch -n 5 cat loser.txt &
```
save n exit


### thats it
<br>



# Conlusion:
This VM is not that good but its ubuntu 

<br>

# Credits:
### Fredblgr: https://hub.docker.com/r/fredblgr/ubuntu-novnc
### Gitpod: https://gitpod.io
### Docker: https://www.docker.com/
### noVNC: https://novnc.com/info.html




# Bonus:
# [Minecraft](./Minecraft.md)
