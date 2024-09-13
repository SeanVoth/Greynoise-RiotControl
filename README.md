# Greynoise-RiotControl
Scans a list of IPs and removes known RIOT and Benign IPs from the list


<h1>Description</h1>
Project consists of a Powershell script that will scan through a list of IPs and using the Greynoise API to detect if any IPs are known as RIOT or Benign. If they are RIOT or Benign then they are removed from the list.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Powershell</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows 11</b>


<h2>Example of script </h2>

RIOT IPs:
- 212.102.40.218
- 84.17.41.82

Benign IPs:
- 65.49.1.38
- 216.218.206.67
- 169.228.66.212

  Removed 2 RIOT IPs and 3 Benign IPs from the file.
  Removed IPs have been saved to C:\temp\RIOT_Benign.txt

<br />


<!--
example of the screenshots when ready 
<p align="center">
Launch the utility: <br/>
<img src="[https://i.imgur.com](https://imgur.com/a/BHxrOZk)"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com"/>
<br />
<br />
</p>



 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
