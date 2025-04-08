<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Post-Install Configuration Guide</h1>

<p>This tutorial outlines the steps to configure the osTicket system after installation, ensuring it is ready to manage support tickets, end-user requests, and agent assignments efficiently.</p>

<hr />

<h2>🌐 Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Computer)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
</ul>

<h2>🖥️ Operating Systems Used</h2>
<ul>
  <li>Windows 10 (22H2)</li>
</ul>

<h2>⚙️ Post-Install Configuration</h2>
<p>
  Once osTicket is installed, it's essential to configure the system to handle real-world ticket flow, support teams, and end-user requests. This configuration ensures streamlined support operations, accountability, and role management within the help desk environment.
</p>

<h2>🔧 Configuration Components</h2>
<ul>
  <li><strong>Roles:</strong> Define permissions for Admins and Support Staff</li>
  <li><strong>Departments:</strong> Organize support into logical categories (e.g., IT, HR)</li>
  <li><strong>Teams:</strong> Structure support tiers such as Level I and Level II</li>
  <li><strong>Agents:</strong> Add staff members who resolve tickets</li>
  <li><strong>Users:</strong> Register end-users who will submit support requests</li>
  <li><strong>SLAs:</strong> Set service standards and time expectations for ticket resolution</li>
  <li><strong>Help Topics:</strong> Define categories to route incoming requests</li>
</ul>

<hr />

<h2>📋 Configuration Walkthrough</h2>

<h3>1. Configure Roles</h3>
<ul>
  <li>Navigate to: <strong>Admin Panel → Agents → Roles</strong></li>
  <li>Create or assign roles such as <code>Supreme Admin</code> for full system control</li>
</ul>

<h3>2. Configure Departments</h3>
<ul>
  <li>Navigate to: <strong>Admin Panel → Agents → Departments</strong></li>
  <li>Example: Create a <code>System Administrators</code> department to handle high-priority issues</li>
</ul>

<img src="https://github.com/user-attachments/assets/c8b7dfb9-2dfb-49c8-a311-64a130afac0f" alt="Departments Configuration" width="700"/>

<h3>3. Configure Teams</h3>
<ul>
  <li>Navigate to: <strong>Admin Panel → Agents → Teams</strong></li>
  <li>Create teams for structured support (e.g., Level I and Level II)</li>
</ul>

<h3>4. Add Agents</h3>
<ul>
  <li>Navigate to: <strong>Admin Panel → Agents → Add New</strong></li>
  <li>Add agents like <code>Jane</code> and <code>John</code> to manage ticket flow</li>
</ul>

<img src="https://github.com/user-attachments/assets/be234317-0ddf-4282-878b-2fab96f93623" alt="Agents Configuration" width="700"/>

<h3>5. Register End-Users (Clients)</h3>
<ul>
  <li>Navigate to: <strong>Agent Panel → Users → Add New</strong></li>
  <li>Example users: <code>Karen</code> and <code>Ken</code>, who will submit support tickets</li>
</ul>

<img src="https://github.com/user-attachments/assets/69a17245-7149-4b9b-bea2-cffaff891c8e" alt="User Setup" width="700"/>

<h3>6. Configure SLAs (Service Level Agreements)</h3>
<p>SLAs ensure timely responses to tickets based on urgency. They are critical to managing expectations and service standards.</p>

<img src="https://github.com/user-attachments/assets/cf3c8485-4d97-428d-af7a-59e983fdf1ac" alt="SLA Configuration" width="700"/>

<ul>
  <li>Navigate to: <strong>Admin Panel → Manage → SLA</strong></li>
  <li>Example SLA setup:
    <ul>
      <li><strong>Sev-A:</strong> 1 hour, 24/7 (Critical system outages)</li>
      <li><strong>Sev-B:</strong> 4 hours, 24/7 (High-priority issues like software failures)</li>
      <li><strong>Sev-C:</strong> 8 hours, business hours (Minor issues such as password resets)</li>
    </ul>
  </li>
</ul>

<h3>7. Configure Help Topics</h3>
<p>Help topics guide users when submitting tickets and ensure they are routed to the appropriate team.</p>

<img src="https://github.com/user-attachments/assets/99eee362-904b-4ec6-bd37-4ad9491d1f14" alt="Help Topics" width="700"/>

<ul>
  <li>Navigate to: <strong>Admin Panel → Manage → Help Topics</strong></li>
  <li>Suggested topics:
    <ul>
      <li>Business Critical Outage</li>
      <li>Personal Computer Issues</li>
      <li>Equipment Request</li>
      <li>Password Reset</li>
    </ul>
  </li>
</ul>

<hr />

<h2>✅ Summary</h2>
<p>
  After installing osTicket, configuring its foundational elements is crucial for effective support operations. By defining roles, setting up departments and teams, registering users and agents, and configuring SLAs and help topics, you create a structured and responsive environment ready to handle incoming support requests.
</p>

<p>
  This post-install configuration ensures osTicket is optimized for real-world use, enabling support teams to act efficiently and users to receive timely assistance.
</p>
