---
title: "how to set up your first R2S equipment"
tags:
- soft router
- r2s
- OpenWrt
- 2022
- 四月
---


# How to set up your first R2S system

## Plug in the power cable let it play

When you open your package, you will see an R2S mini machine and a set of power cables with the charger. Remember that **the charger must be the 5V2A~3A if you buy it yourself.**

Then you could plug the SD card into your R2S machine, connect the power cable, and you will **see the `sys light` begins to flash. That means the R2S machine is working now.**

![sys light begins to flash](notes/images/Pasted%20image%2020220416132530.png)

##  Let your computer connect to your R2S

Use an internet data cable to connect your laptop with your R2S, and check if your computer had received the IP address.

![connect your R2S with your laptop](notes/images/Pasted%20image%2020220416132606.png)



If everything goes well, you can type the IP gate address in your internet broswer(e.g. Chrome or IE Explorer) then it will open a website for you, like this.

![the webpage of R2S website](notes/images/Pasted%20image%2020220416132331.png)

### The default user name & password

- The Default IP address: `192.168.2.1`
- The Default User Name: `root`
- The Default Password: `password`

## How to set up your OpenWrt system

### Set up the internet interface

Open `Network` -- `Interface` **then you must decide your home's network is dialing by your router or by your R2S**.


### Dialing by your original router.

If your home's internet is dailed by your original router, you should press the `WAN`--`Revise` button.

![revising your WAN interface ](notes/images/Pasted%20image%2020220416133310.png)





