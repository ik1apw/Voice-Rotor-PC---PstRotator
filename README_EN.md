# Voice-Rotor-PC---PstRotator
It’s a simple software that reads the rotor position from PstRotator and converts it into voice, without any additional hardware and without modifying the existing setup.
Voice Rotor PC UDP

Software for voice reading of the rotor position from PstRotator.

REQUIREMENTS
- Windows
- PstRotator installed and working

PSTROTATOR CONFIGURATION
1. Open PstRotator
2. Accept the opening of the firewall
3. Menu: Communication → UDP Control Port
4. Set port to: 12000
5. Set Remote IP 127.0.0.1
6. Open Setup
7. Enable UDP Control

USAGE
1. Run VoiceRotorPC_UDP.exe
2. Set:
   Host: 127.0.0.1
   Port: 12000
3. Press START

The program will announce the rotor position.

NOTES
- Does not interfere with normal PstRotator operation
- No serial ports or additional software required
- Supports IT / EN / ES languages
