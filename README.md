# Network Engineer Simulator

A browser-based educational game for learning network topology, device wiring, and basic web hosting in a simulated environment.
URL - https://networking-game.netlify.app/
## Features

- Add Internet, tower equipment, managed switches, web servers, database servers, rack servers, laptops, and desktop hosts
- Connect devices via port-to-port cable wiring
- Automatic WAN/Fiber behavior for Internet and WAN ports
- Drag devices around the canvas to create custom network layouts
- Host Screen with simulated Terminal, Browser, HTML Lab, and Guide
- Import or write HTML/CSS/JavaScript in the built-in editor
- Run a local HTML preview inside the app
- Save HTML to a host and serve it through the simulation
- Built-in demo network for quick exploration

## Getting started

1. Save the `network_engineer_simulator.html` file to your computer.
2. Open it in a modern browser.
3. Add devices from the left panel.
4. Connect devices by dragging from one port to another, or click a source port and then a destination port.
5. Click “Enable Host Screen” to open the host utilities.

## Host Screen

The Host Screen lets you interact with a selected device as if it were a real computer. It includes:

- Terminal
- Browser
- HTML Lab
- Guide

This gives you a quick, hands-on way to test simulated networking and basic web hosting concepts.

## HTML Lab

The HTML Lab allows you to:

- Write HTML/CSS/JavaScript directly
- Import a local `.html` file
- Run a preview in an isolated sandbox
- Save the page to a host in the simulated environment

## Simulated Server Workflow

1. Select a host
2. Open the HTML Lab
3. Write or import HTML
4. Click “Save to host”
5. In the Terminal, run:
   ```bash
   python3 -m http.server 8000

   supported terminal commands 

help
hostname
ip addr
ip route
ping <ip>
curl <url>
python3 -m http.server [port]
systemctl status
ls
uptime
clear
