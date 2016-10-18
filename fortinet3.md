### Logging in to the test drive:
Once the test drive is launched, use the URL, Login and Password from the “Environment log” on the test drive launch page, or from the email you received once the test drive was created.

Both the environment log and the email contain the URL, login id, password, two license file URLs, and private IP of both A & B FortiGates.

Once you’ve logged in to the test drive, you will create a policy on FortiGate-A (and FortiGate-B) to allow outbound internet connectivity (be sure to enable NAT using the outgoing interface address. To do this, you can:

 Connect to FortiGate-A via https on default port 443 [link](https://dnsUR)

 Connect to FortiGate-B via https on port 8443 [link](https://dnsURL:8443)

For example, use the URL provided in the environment window and in the email to connect to FortGate-A (on port 443 by default), and use the same URL but with :8443 appended at the end to connect to Fortigate-B.

Note: these ports are configured in the Azure Load Balancer Inbound NAT rules and can be changed (for instance if you want to use port 443 for internal resources). Additionally, you can add multiple frontends to the load balancer each with its own public IP address.
