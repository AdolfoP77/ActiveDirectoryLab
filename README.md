# ActiveDirectoryLab
In this Lab we're going to walk through how to create an Active Directory home lab Environment using Oracle Virtual Box. Configuring and running this lab will definitely help develop your understanding of how active directory and windows networking works, so I'd highly recommend running through it a couple times, ask questions where stuff is unclear, and eventually try to build it on your own without watching. Please let me know if you have any questions!


--Project Overview Flowmap:
![Flow map ](https://user-images.githubusercontent.com/107056915/172675842-3184752e-6d4e-49b5-8c07-b9d6e96591d5.png)

<p>Requirements for this lab are: </p>
<p>1 Windows 10 Client. (VM)</p>
<p>1 Windows Server 2019 (VM) </p>
<p>For steps on how to set these 2 VM's click here:</p>
<br>
<br>

Setup Server Network Adapters 
<br>
Label Adapters
![Label Internet](https://user-images.githubusercontent.com/107056915/172684263-2428e781-18aa-4776-8170-c4c245d64016.png)
Determine Internet and Internal.
![Int](https://user-images.githubusercontent.com/107056915/172686256-e98d8b77-a51f-4842-b2dd-bbcd6877d05c.png)
Rename 
![labeled done](https://user-images.githubusercontent.com/107056915/172686517-f5236d22-2bb8-4bcc-8c50-fca234ccf2a0.png)
Change System Name to DC (Domain Controller)
![SYSTEM](https://user-images.githubusercontent.com/107056915/172686686-22b9a3eb-4745-486f-ae3a-0920bcfaf0a3.png)
![button rename](https://user-images.githubusercontent.com/107056915/172686703-6c6f44c0-0757-4761-94a3-97bc8e589f9c.png)
![DC](https://user-images.githubusercontent.com/107056915/172686715-ec05aedf-1e03-470a-85a4-1b8e93429286.png)
System will Reboot.

<br>

Assign IP address to internal adapter.
![Assign IP 1](https://user-images.githubusercontent.com/107056915/172696971-0801e060-46a2-480e-b393-d296e976da0e.png)
![Assign IP 2](https://user-images.githubusercontent.com/107056915/172696991-96c70940-540e-4832-b652-8e71afc0eca0.png)
![Assing ip 3](https://user-images.githubusercontent.com/107056915/172697061-7ce8e8cb-7190-4fa6-848c-b71d2dba7309.png)
![assign IP 4](https://user-images.githubusercontent.com/107056915/172696993-e6416426-463c-46c4-9fdd-8576b83f565f.png)

<br>

Install Active Directory Domain Services.
![installadds1](https://user-images.githubusercontent.com/107056915/172698612-543fb52c-3a46-4ad7-9d6a-a6dc3e174092.png)
![installadds2](https://user-images.githubusercontent.com/107056915/172698623-863b7960-ef78-4dc6-b862-1cfd71819125.png)
![installadds3](https://user-images.githubusercontent.com/107056915/172698635-68340ae5-34c3-42a4-9958-eb404a16e5e8.png)
![installadds4](https://user-images.githubusercontent.com/107056915/172698651-88000a39-a368-4595-8b7c-29b158bad024.png)
![installadds5](https://user-images.githubusercontent.com/107056915/172698668-60227b14-70ad-4ca3-b236-9de1fde416e9.png)

<br>

Promote Domain Controller




