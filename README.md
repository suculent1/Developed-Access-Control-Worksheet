<!DOCTYPE html>
<html>
<body>
  <header>
    <h1>Developed Access Control Worksheet</h1>
  </header>
  <main>
    <section>
      <h2>Overview</h2>
      <p>Deep packet inspection is a type of data processing which inspects in detail the data being sent over a computer network. Depending on the details within the data, deep packet inspection (DPI) programs will allow, block, reroute, or log data being sent.</p>
    </section>
    <section>
      <h2>Project Description</h2>
      <p>In this project, you will use a DPI tool to identify and analyze data being sent across a network. You will set up a virtual lab with two host machines, send data between the two devices while the DPI tool monitors the communication between each device.</p>
    </section>
    <section>
      <h2>Popular DPI Tools</h2>
      <ul>
        <table>
  <tr>
    <th>Access Control type</th>
    <th>Identify the threat</th>
    <th>Identify Authorization Issues</th>
    <th>Recommendations</th>
  </tr>
  <tr>
    <td>Authorization /authentication</td>
    <td>Objective: <br>List 1-2 pieces of information that can help identify the threat:</td>
    <td>Objective:<br> Based on your notes, list 1-2 authorization issues: </td>
     <td>Objective:<br> Make at least 1 recommendation that could prevent this kind of incident:
</td>
  </tr>
  <tr>
    <td>Authorization /authentication</td>
    <td> Who caused this incident? Legal/Administrator. They added a payroll event for FAUX_BANK 
When did it occur? 10/03/2023 08:29:57 AM 
What device was used? 
Up2-NoGud 
The user is legal/administrator 
The user accessed the AdsmEmployeeService service from the Up2-NoGud computer with the IP address 152.207.255.255 </td>
    <td> What level of access did the user have? Admin 
Should their account be active? No Issue1. Employee Robert Taylor Jr. accessed the system using an unauthorized level of admin despite his contractor status. 
Issue2. Employee Joanne Phelps was given access to the system two years ago and still has access despite her position ending in January 2021. </td>
    <td> 
Which technical, operational, or managerial controls could help? 
Implement an access control system to control and monitor user activity on the network. This system should be configured to check user credentials , limit user rights, track access attempts and log user activities. 

Implement endpoint security solution to provide protection against malicious software, restrict unauthorized access to data sources and control device usage
Implement a multi-factor authentication system to require a second form of authentication such as a pin or biometric data when a user attempts to use the system. </td>
  </tr>
</table>    </section>
    <section>
      <h2>Project Showcase</h2>
      <img src="virtual-lab-setup.png" alt="Virtual Lab Setup">
      <img src="dpi-tool-analysis.png" alt="DPI Tool Analysis">
    </section>
  </main>
</body>
</html>
