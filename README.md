# [Work in progress]

# Thought Network Pool Miner

[thoughtminingpool.com](www.thoughtminingpool.com) (Website in development)<br>
mining.thoughtminingpool.com (THT mining pool)

Crypto miner for the [Thought Network](https://github.com/thoughtnetwork).

Please see the releases page for download link. (coming very soon)

## Solo Mining

Currently only solo mining has been implemented and will be enabled by default. 

## Pool mining

In development.

## Supported Oprtating Systems

- Linux (Supported)
- Windows (_Coming Soon_)
- Mac (Not tested...) 

## Running

**DO NOT RUN MULTIPLE INSTANCES**

This miner has been written in such a way that we fully utilize the CPU. Running multiple instances **WILL** cause more harm than good. 

You do not need your thought wallet running to use this miner. All of the jobs will come from the mining pool, you will just need to specify your payout address. 

### Prerequisite 

1. Download the latest miner from the releases tab.
2. Extract the archive (there will be two files, Host and Instance)
3. chmod +x Miner
4. chmod +x instance
5. Follow OS specific instructions below

### Linux 

You will need to have the following packages installed. 

1) Need to test this

To Run the miner from the command line please use the following arguments. You can see a list of arguments by typing --h.

```text
usage: Miner
 -x <arg>                   Address to deliver mining rewards to
 -u <arg>                   Mining pool URL
 -p <arg>    (optional)     Mining pool port (default: 12617)
 -t <arg>    (optional)     Number of miner threads to use (default: number of cores)
 -d <arg>    (optional)     Donation percentage
 ```

Example command is below. 

```-x <mineraddress> -u mining.thoughtminingpool.com -p 12617 -t 8 -d 0```

### Windows 

_Coming Soon_

### Mac

_Coming Soon_


### Release Version

| Verison name | Version Number | Release notes |
| --- | ----------- | --------------- |
| Greyback | v1.0.0 | [Link](https://github.com/JamesEllisDev/ThoughtAi-Pool-Miner/releases/tag/v1.0.0) |
