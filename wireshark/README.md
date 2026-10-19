# Workshop Activity 4: Inspecting Packets

This activity demonstrates how to retrieve hidden values from internet packets.

## Launch VM

1. Go to this [URL](https://labex.io)

2. Make an account

3. Start a Linux lab

4. Open a terminal tab in the VM.

## In the terminal

1. Update the system:

```bash
   sudo apt update
```

2. Install Wireshark:

```bash
   sudo apt install wireshark -y
```

3. Launch Wireshark:

```bash
   wireshark
```

## In Wireshark

1. Click **File → Open** and locate `challenge.pcap`.
2. Scroll through the packet flow. You'll see lots of different types of packets.
3. Keep a keen eye on the HTTP packets. How do you filter them? What might they contain?
4. There might be several Base64 values, but only one contains the flag.
