<h1>Failed RDP with Microsoft Sentinel</h1>

<h2>Description</h2>
<b>Utilized a Powershell script to parse out Windows Event Logs from Windows Event Viewer for failed RDP attacks and using a third party API to collect information about the attackers Geographic location.
</b>
<br />
<br />
Configured Microsoft Sentinel (Azure cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to location and magnitude of attacks.
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/1Ai1S6j.png" height="55%" width="55%" alt=""/>
</p>

<h2>Utilities Used</h2>

- <b>ipgeolocation.io: API to convert IP Address to Geolocation</b>

<h2>Attacks coming in; Custom logs being output with geodata</h2>

<p align="center">
<img src="https://i.imgur.com/EDA8vKu.png" height="85%" width="85%" alt=""/>
</p>

<h2>World map of incoming attacks</h2>

<p align="center">
<img src="https://i.imgur.com/NWIHziF.png" height="85%" width="85%" alt=""/>
</p>
