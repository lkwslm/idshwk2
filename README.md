# idshwk2

write two rules in test.rules

• Deadline : March 29th 11:00

• if snort see two packets in a TCP flow with 

  \t• first packet has “login” or “Initial” in payload, destination port is 3399;

  \t• and second packet has a “IPv4Address:Port”string(E.g. 123.45.6.7:8080) in payload. destination port is

  \t3399;

  \t• output a alert with msg “bot founded” and sid 1000001
