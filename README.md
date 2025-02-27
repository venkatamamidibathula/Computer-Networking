# Computer-Networks

**Difference between IP Address and MAC address**

![ipmac](ipmac.jpg)


## Half-Duplex vs Full-Duplex Communication

### Half-Duplex
- **Definition**: Data flows in both directions, but one at a time (e.g., walkie-talkie).
- **Pros**: Simple, cost-effective.
- **Cons**: Slower, turn-based.
- **Examples**: Two-way radios, early Ethernet hubs.

### Full-Duplex
- **Definition**: Data flows in both directions simultaneously (e.g., phone call).
- **Pros**: Faster, efficient for real-time use.
- **Cons**: More complex, costly.
- **Examples**: Modern phones, broadband, Ethernet switches.

| Feature       | Half-Duplex         | Full-Duplex         |
|---------------|---------------------|---------------------|
| **Data Flow** | One way at a time   | Both ways at once   |
| **Speed**     | Slower              | Faster              |
| **Complexity**| Simpler             | More complex        |

## Network Transmission Types: Unicast, Multicast, Broadcast

### Unicast
- **Definition**: Data sent from one sender to one specific receiver.
- **Use Case**: Email, web browsing.
- **Pros**: Precise, efficient for single targets.
- **Cons**: Inefficient for multiple recipients.

### Multicast
- **Definition**: Data sent from one sender to a specific group of receivers.
- **Use Case**: Video streaming, online gaming.
- **Pros**: Efficient for group communication.
- **Cons**: Requires group management.

### Broadcast
- **Definition**: Data sent from one sender to all devices on a network.
- **Use Case**: Network discovery (e.g., ARP), TV broadcasts.
- **Pros**: Simple, reaches everyone.
- **Cons**: Can flood network, less secure.

| Type      | Sender | Receiver       | Example             |
|-----------|--------|----------------|---------------------|
| Unicast   | 1      | 1              | Email              |
| Multicast | 1      | Specific group | Live stream        |
| Broadcast | 1      | All            | Network announcement |



