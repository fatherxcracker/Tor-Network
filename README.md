# Tor Network – Rice & Crackers

## Team Members
- James Luciano – 6304894
- Deven Shah-Phan – 6317514
- Cyril Efren Fabro – 6243515

## Project Topic
**The Tor Network**

## Project Description
Our project explores the Tor Network and how it provides privacy and anonymity when browsing the internet. Tor works by routing internet traffic through multiple relays, making it difficult for any single relay to identify both the user and their destination.

We will research how Tor circuits work, including guard, middle, and exit relays, as well as directory authorities, network consensus, bridges, pluggable transports, and onion services.

For the practical portion of our project, we plan to set up a non-exit middle Tor relay using a Linux-based VPS hosted through Hetzner. The relay will help carry encrypted Tor network traffic without connecting directly to destination websites. We also plan to use Nyx to monitor the relay, view bandwidth usage, and observe network activity.

Our goal is to understand how Tor protects users' privacy while gaining hands-on experience setting up and monitoring a Tor relay.

## Technologies and Hardware
- **Operating System:** Linux (Ubuntu)
- **Hosting Provider:** Hetzner VPS 
- **Software:** Tor, Nyx, Tor Browser
- **Hardware:** VPS (Virtual Private Server)

## Implementation Plan
1. Research the Tor Network and understand how its relays and circuits operate.
2. Set up a Linux VPS using Hetzner.
3. Install and configure Tor on the VPS.
4. Configure the server as a non-exit relay.
5. Configure the required firewall rules and networking settings.
6. Start the Tor service and verify that the relay joins the network.
7. Install and use Nyx to monitor relay activity, bandwidth, and connections.
8. Check whether the relay appears on Tor Metrics after it has been running long enough to be listed.

## Reproducing the Setup

The following steps describe our planned setup. Exact commands and configuration details may be updated as implementation progresses.

1. Create a Linux VPS through [Hetzner](https://www.hetzner.com/).
2. Connect to the VPS using SSH.
3. Update the Linux system packages.
4. Install Tor using the official Tor Project installation instructions.
5. Install Nyx for relay monitoring.
6. Edit the Tor configuration file (`torrc`) to configure the relay nickname, contact information, ORPort, and non-exit relay settings.
7. Configure the VPS firewall to allow the required relay traffic.
8. Restart the Tor service and verify that it is running correctly.
9. Use Nyx to monitor the relay and check its status on Tor Metrics.

## Live Host Address

- **Status:** Deployed
- **Hosting Provider:** Hetzner VPS
- **Operating System:** Ubuntu Linux
- **Relay IP Address / Hostname:** Pending VPS deployment
- **Relay Nickname:** To be configured
- **ORPort:** To be configured (commonly 9001)
- **Relay Type:** Non-exit middle relay
- **Monitoring Tool:** Nyx
- **Network Status:** Not yet connected to the Tor network
