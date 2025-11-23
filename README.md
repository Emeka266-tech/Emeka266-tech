<h2>Hi i'm Ferdinand a cybersecurity professional</h2>

<h2>My cybesecurity project(SIEM)</h2>

i'm currently working on a SIEM solution that involves uploading, extracting, parsing using regular expressions, filtering values, creating a table for analysis, utilizing basic commands and analyzing some of the created values. I created a dashboard with the log and uploaded it to my homepage for easy analysis.

Here's how i did it. 

firstly, i uploaded a downloaded DNS log file, using the settings - add data and upload option.
<img width="803" height="443" alt="image" src="https://github.com/user-attachments/assets/3578c72e-6c28-4733-b859-d52ead7f2657" />

 After uploading it, i saved it with a name, reviewed and began my search. which displayed the log for analysis.

 <img width="929" height="461" alt="image" src="https://github.com/user-attachments/assets/7a444eae-a8cf-4803-bd47-1d71d705b0de" />

After searching the log file. i used the extract new option to choose the particular field i wanted to analyse. i proceded to parse and extract it using regular expression.

<img width="906" height="469" alt="image" src="https://github.com/user-attachments/assets/985201bb-d233-4709-9902-094497cc17da" />


I went further to indicate the values i wanted to monitor and analyze. in this case i highlighted multiple values but it,s industry best practice to go one at a time.
i highlighted the source and destination ip address. the source and destination port numbers. the fully qualified domain name(FQDN) and the DNS record type.

<img width="938" height="433" alt="image" src="https://github.com/user-attachments/assets/5f719e8d-163d-4086-ab3e-a27bf074fe3e" />


And automatically on the left hand side of the screen, in the interesting fields. it gave me the values i highlighited for easier analysis.

<img width="925" height="405" alt="image" src="https://github.com/user-attachments/assets/09569d00-5559-4ef5-9ff9-2678cd0638f8" />


Afterwards i began analyzing the logs using commands like top limit, stats count and the table command.
using the top limit command, i analyzed how many times a particular domain has been queried. which can be very helpful in detecting attacks such as ransomeware.

<img width="932" height="430" alt="image" src="https://github.com/user-attachments/assets/1b81f473-a73b-43b5-8671-79f11e5bf0cf" />


I also used the stats count commmand to analyze the FQDN..

<img width="942" height="441" alt="image" src="https://github.com/user-attachments/assets/469568b3-0b9e-40f4-a71f-0f1b445a63ba" />


I went further to analyze some of the fields i created, like the src_ip. which was crucial in identifying top traffic sources, potential anomalies or malicious activities from specific ip addresses.

<img width="938" height="463" alt="image" src="https://github.com/user-attachments/assets/8c1ee64e-3b4a-4495-95b7-f58342753390" />


And finally, i created a dashboard with the log file and saved it on my homepage for easy analysis.

What i did was using the save as option on the top right. created a dashboard using the searched logs and uploaded it to my homescreen for easy analysis..


<img width="938" height="466" alt="image" src="https://github.com/user-attachments/assets/3085e06c-3b05-4c61-b720-ee7b894b7ea1" />


<img width="941" height="477" alt="image" src="https://github.com/user-attachments/assets/a3f05996-f806-4480-a43e-8fd66fddc8b0" />


<h2>WHAT I LEARNT FROM THIS PROJECT</h2>


I learnt alot of important SIEM skills from this project. like, Data ingestion, parsing, analysis and visualization. i also leanrt how to utilize basic commands to better analyze logs. this project also helped in giving me more knowledge on threat detection, as i learnt to recognize patterns indicative of common security threats..
