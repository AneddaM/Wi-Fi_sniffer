# Wi-Fi_sniffer

This script is for counting mobile devices with active Wi-Fi interface within the Wi-Fi sniffer coverage area.

The Wi-Fi sniffer behaves similarly to an Access Point (AP) that exchanges information with mobile devices for a potential connection.

The mobile device broadcasts probe requests and receives probe responses from the Wi-Fi sniffers.

The Wi-Fi sniffer stores the information proceeds from the mobile devices:
- "ANTENNA": the numbering of the sniffer.
- "MAC_ADDRESS": the anonymized Mac Address,
- "TIMESTAMP": the unix time stamp is a way to track time as a running total of seconds.
- "FREQUENCY": the communication frequency between monbile device and Wi-Fi sniffer
- "POWER_dBm": the power received by the signal.
- "CHANNEL": the communication channel used in the probe request.
