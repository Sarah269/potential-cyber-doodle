## File Integrity Monitor
<pre>Proof of concept
Create a file integrity monitor to continuously inspect files and raise an alert if a file changes.

Tool:  Powershell ISE</pre>

<ul>
  <li> Create powershell script</li>
  <li>Prompt user for input</li>
  <li>Create a baseline</li>
    <ul>
      <li>Calculate a hash for each file in the directory</li>
      <li>Store the hash with filename in a file</li>
    </ul>
  <li>Monitor the directory</li>
     <ul>
       <li>Re-calculate the hashs for each file in the directory</li>
       <li>Compare the newly calculated hash with the baseline hash</li>
       <ul>
        <li>Deleted:  file listed in the baseline is no longer in the directory</li>
        <li>New: file is in the directory and not in the baseline</li>
        <li>Change: newly calculated hash and the baseline hash are not the same</li>
        <li>No change: newly calculated hash and baseline hash are the same</li>
       </ul>
     </ul>
  <li>Write message to console for each file</li>
</ul>

<p>Create Baseline</p>

![Create Baseline](https://github.com/Sarah269/potential-cyber-doodle/blob/main/FIM/FIM_2.png)

<p>Create Baseline.  Entered wrong option</p>

![Entered wrong option](https://github.com/Sarah269/potential-cyber-doodle/blob/main/FIM/FIM_1.png)

<p>Monitor files.  No changes</p>

![Monitor files. No changes](https://github.com/Sarah269/potential-cyber-doodle/blob/main/FIM/FIM_3.png)

<p>Monitor files.  Changes detected</p>

![Monitor files. Changes detected](https://github.com/Sarah269/potential-cyber-doodle/blob/main/FIM/FIM_4.png)

<p>Monitor files.  No baseline exists</p>

![Monitor files. No baseline exists](https://github.com/Sarah269/potential-cyber-doodle/blob/main/FIM/FIM_5.png)


