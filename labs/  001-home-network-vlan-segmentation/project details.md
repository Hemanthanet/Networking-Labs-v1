Lab 001 (Packet Tracer): “Home Network + Guest VLAN + Basic Security”

  Goal: Separate home users from guest Wi-Fi using VLANs, plus DHCP + basic ACL.

Devices:

  1 router, 1 switch, 2 PCs (Home/Guest), 1 server (optional)

What to implement:

  VLAN 10 = Home (e.g., 192.168.10.0/24)

  VLAN 20 = Guest (e.g., 192.168.20.0/24)

  Router-on-a-stick (subinterfaces)

  DHCP for both VLANs

  ACL: Guest can reach internet (or “outside”) but cannot reach Home VLAN

Step-by-step build (high level)

  Place devices and cable them

  Create VLANs on switch + assign access ports

  Configure trunk to router

  Configure router subinterfaces (dot1q) + gateway IPs

  Configure DHCP pools

  Apply ACL rules

Verify: pings within VLAN, ping gateway, guest blocked from home

What you save to GitHub:

  The .pkt file

  2–4 screenshots (topology + successful tests)

  README.md using my template
