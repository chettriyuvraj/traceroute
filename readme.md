# Traceroute

This is a re-implementation of the linux traceroute command, which traces the path of a packet all the way from source to destination. 

Some notes: 
- Sends ICMP packet only (instead of UDP packets which are default in Linux traceroute).
- You must enter the _IPv4 address_ not the URL.
- This is the [Original Repository Folder)[https://github.com/bradfield-csi-5/chettriyuvraj/tree/main/BradfieldCSI/Networks/Prework-5-Traceroute], in case you want to follow the commit history.

I also wrote a [small piece](https://medium.com/@chettriyuvraj/software-and-the-mirage-of-the-best-idea-29a130e27dbc) about traceroute and software in general.

## Usage

Execute the following set of commands: 

- First grab the IP address of the URL you want to trace using the dig utility. Eg _dig google.com_ 
- sudo go run main.go _IPv4 Address_

## Output:

If all goes well, you should see this ugly-ly formatted packet trail

<img width="743" alt="image" src="https://github.com/chettriyuvraj/traceroute/assets/32122172/d09f0b26-d1a9-41a0-be86-b1a4c5581f7d">
