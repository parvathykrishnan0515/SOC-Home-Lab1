<h1>🛡️ SOC Home Lab 1 – SIEM & Incident Detection</h1>

<h2>🎯 Objective</h2>
<p>
The <b>SOC Home Lab – SIEM & Incident Detection</b> project was designed to build a realistic
Security Operations Center (SOC) environment for detecting, analyzing, and investigating
security incidents.
</p>

<p>
The primary objective was to simulate real-world cyber attacks, ingest endpoint and network
logs into a SIEM platform, and perform alert monitoring, log analysis, and incident response
activities—demonstrating practical SOC analyst skills aligned with enterprise security operations.
</p>

<hr>

<h2>🧠 Skills Learned</h2>
<ul>
  <li>Hands-on experience with SIEM deployment and configuration</li>
  <li>Log ingestion, normalization, and correlation</li>
  <li>Security alert monitoring, triage, and investigation</li>
  <li>Detection of brute-force attacks and malicious PowerShell activity</li>
  <li>Analysis of Windows and Linux security logs</li>
  <li>Mapping attacker behavior to the MITRE ATT&CK framework</li>
  <li>Incident analysis, documentation, and decision-making</li>
</ul>

<hr>

<h2>🛠️ Tools Used</h2>
<ul>
  <li><b>SIEM Platform:</b> Splunk</li>
  <li><b>Endpoint Operating Systems:</b>
    <ul>
      <li>Windows 10</li>
      <li>Ubuntu Linux</li>
    </ul>
  </li>
  <li><b>Attacker System:</b> Kali Linux</li>
  <li><b>Log Collection:</b> Splunk Universal Forwarder, Sysmon</li>
  <li><b>Network Analysis:</b> Wireshark</li>
  <li><b>Framework:</b> MITRE ATT&CK</li>
</ul>

<hr>

<h2>🧪 Steps Performed</h2>

<h3>🔹 Step 1: SOC Lab Architecture Design</h3>
<ul>
  <li>Central SIEM (Splunk)</li>
  <li>Windows and Linux endpoints</li>
  <li>Attacker machine generating malicious activity</li>
  <li>Log forwarding from endpoints to the SIEM</li>
</ul>
<p><img src="Soc Lab Architecture.png" alt="SOC Architecture Diagram" width="800"></p>

<h3>🔹 Step 2: Log Collection & Ingestion</h3>
<ul>
  <li>Windows Security and Sysmon logs</li>
  <li>Linux authentication logs</li>
  <li>Network-related events</li>
</ul>
<p><i>📸 Ref 2: Log Ingestion Verification</i></p>

<h3>🔹 Step 3: Attack Simulation</h3>
<ul>
  <li>SSH brute-force attacks</li>
  <li>Windows login brute-force attempts</li>
  <li>Malicious and encoded PowerShell execution</li>
</ul>
<p><i>📸 Ref 3: Attack Simulation Activity</i></p>

<h3>🔹 Step 4: Detection Rule Creation</h3>
<ul>
  <li>Multiple failed authentication attempts</li>
  <li>Suspicious or encoded PowerShell commands</li>
</ul>
<p><i>📸 Ref 4: SIEM Detection Rule Configuration</i></p>

<h3>🔹 Step 5: Alert Monitoring & Investigation</h3>
<ul>
  <li>Analyzed log events</li>
  <li>Reviewed source IPs and user accounts</li>
  <li>Correlated events across multiple data sources</li>
  <li>Determined alert severity and legitimacy</li>
</ul>
<p><i>📸 Ref 5: Alert Investigation Dashboard</i></p>

<h3>🔹 Step 6: Incident Documentation & Reporting</h3>
<ul>
  <li>Event timelines</li>
  <li>Indicators of Compromise (IOCs)</li>
  <li>MITRE ATT&CK technique mapping</li>
  <li>Final verdict (True Positive / False Positive)</li>
</ul>
<p><i>📸 Ref 6: Incident Investigation Report</i></p>

<hr>

<h2>📌 MITRE ATT&CK Mapping</h2>
<table>
  <tr>
    <th>Technique</th>
    <th>ID</th>
  </tr>
  <tr>
    <td>Brute Force</td>
    <td>T1110</td>
  </tr>
  <tr>
    <td>PowerShell</td>
    <td>T1059.001</td>
  </tr>
</table>

<hr>

<h2>📊 Outcome</h2>
<ul>
  <li>Successfully built a functional SOC home lab</li>
  <li>Generated realistic attack telemetry</li>
  <li>Detected and investigated simulated security incidents</li>
  <li>Gained hands-on experience with real SOC analyst workflows</li>
</ul>

<hr>

<h2>🚀 Future Improvements</h2>
<ul>
  <li>Integrate EDR/XDR telemetry</li>
  <li>Add threat intelligence enrichment</li>
  <li>Automate alert triage using Python</li>
  <li>Expand detection coverage for additional MITRE ATT&CK techniques</li>
</ul>
