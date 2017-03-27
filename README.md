# multihack-brackets
Synchronizes code and project structure between multiple users in realtime.

## Usage
1. You and another person with this extension should have the same project open.  
2. **File > Start Multihack**  
3. Enter the same room ID.    
4. Click **Join Room**. Your code is now being synchronized!  
5. **File > Stop Multihack** will stop collaboration.  

This extension currently only syncs *changes* and will not realize any code differences on joining a room. Use Git or another version control to make sure you start with the same initial code.

## Running Your Own Instance
This extension points to the author's server by default.  
Please run your own instance of [multihack-server](https://github.com/RationalCoding/multihack-server) if you want lower latency and improved privacy.  
You can target a different host through the Brackets option **multihack-brackets.hostname**.

## Future Features
- [ ] Integration with web version
- [ ] Integration with future versions on Atom and VSCode
- [ ] Switch from server forwarding to P2P
- [ ] Text, audio and video chat
- [ ] Initial code sync
- [ ] Public coding rooms
- [ ] End-to-end encryption

Also check out [the web version](https://github.com/RationalCoding/multihack-brackets). (Not yet compatible with this extension.)
