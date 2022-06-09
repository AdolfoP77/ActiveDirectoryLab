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
![pdc1](https://user-images.githubusercontent.com/107056915/172701121-31983577-75f7-420f-8f2e-dd4a8d80e831.png)
![pdc2](https://user-images.githubusercontent.com/107056915/172701266-fe176c9d-974c-4efd-a47f-5f456306197c.png)
![pdc3](https://user-images.githubusercontent.com/107056915/172701279-3bde6a39-d614-4616-aee9-84976558ca59.png)
![pdc4](https://user-images.githubusercontent.com/107056915/172701291-8cb8ef07-3c11-48ae-9245-d25193738261.png)
![pdc5](https://user-images.githubusercontent.com/107056915/172701304-1f06cc3c-b6dc-4b91-8d24-c4dcdc77e617.png)
System will reboot.
![pdc6](https://user-images.githubusercontent.com/107056915/172701319-a1d359d2-75ab-4e70-9d6b-cf6c2e402a83.png)

<br>

Create Domain Admin Account
![admin1](https://user-images.githubusercontent.com/107056915/172871252-87a12308-7bc3-4a19-8c46-43549e38bd78.png)
![admin2](https://user-images.githubusercontent.com/107056915/172871260-e40310ed-27ee-4647-82b4-96b77c5acd40.png)
![admin3](https://user-images.githubusercontent.com/107056915/172871270-83c31086-65f4-4702-a154-e67e94cdbc37.png)
![admin4](https://user-images.githubusercontent.com/107056915/172871277-0ef7deec-ecc8-4da6-a6a7-00f86c473353.png)
In this section we set a "a-" to specify this will be an admin account followed by First initial and Last name.
![adminadd](https://user-images.githubusercontent.com/107056915/172874163-7ba3d435-a2a2-4362-a31e-704ca8bb86fe.png)
![admin6](https://user-images.githubusercontent.com/107056915/172871293-ff6f56d6-c094-498c-ab25-19012dcd4f09.png)
70e20e8-43f0-4412-83eb-8e3209f4d180.png)
![admin7](https://user-images.githubusercontent.com/107056915/172871339-fe658c32-60b4-4c95-904d-814538a971cc.png)
![admin8](https://user-images.githubusercontent.com/107056915/172871347-d5b0839d-1daa-4398-b655-3061d7b5d15a.png)
![admin9](https://user-images.githubusercontent.com/107056915/172871450-de456602-e1c2-41eb-be89-64cd2547a0a2.png)
![admin10](https://user-images.githubusercontent.com/107056915/172871457-c1e79eaf-2e0b-4c2b-a96b-a942c7f85c03.png)
![admin11](https://user-images.githubusercontent.com/107056915/172871492-5f39aad7-c9b1-41fc-b1c2-cafdec3bc0b0.png)
![admin12](https://user-images.githubusercontent.com/107056915/172871502-0835799d-168d-4c9d-83a0-9f7d1488ea9b.png)
![admin13](https://user-images.githubusercontent.com/107056915/172871542-93869146-dc74-4322-85c4-39569676d52b.png)
![admin14](https://user-images.githubusercontent.com/107056915/172871545-7cfe29b0-789e-41e2-b1ce-81614fb32458.png)
![admin15](https://user-images.githubusercontent.com/107056915/172871564-93a0479b-c4f4-4c4e-97e2-76eae5d2a61b.png)

<br>

Install RAS/NAT (Remote Access Server/Network Address Translation)
![RAS1](https://user-images.githubusercontent.com/107056915/172879459-5c80e481-3bc2-4899-a445-fc46c44f42cd.png)
![RAS2](https://user-images.githubusercontent.com/107056915/172879466-c43c692d-6a9f-4d56-b629-55bd103c96b1.png)
![RAS3](https://user-images.githubusercontent.com/107056915/172879552-d687c683-f21c-4c5b-b9a6-634046f173a9.png)
![RAS4](https://user-images.githubusercontent.com/107056915/172879555-5761493b-60f5-49af-a911-08b392186126.png)
![RAS5](https://user-images.githubusercontent.com/107056915/172879601-e8522f8d-5dad-4294-a848-6e44c0de9154.png)
![RAS6](https://user-images.githubusercontent.com/107056915/172879606-4daa8d62-8073-4c93-835a-5f387179a547.png)
![RAS7](https://user-images.githubusercontent.com/107056915/172879653-b0c7fd42-d174-49ed-9266-4c4440621b65.png)
Install NAT
![RAS8](https://user-images.githubusercontent.com/107056915/172879658-75ddc7ae-8157-4818-9fd1-79600acac0cf.png)
![RAS9](https://user-images.githubusercontent.com/107056915/172879697-a7a6c998-113b-439c-913e-006b50143e50.png)
![RAS10](https://user-images.githubusercontent.com/107056915/172879700-6de73d38-bc0b-46d7-9b46-72ba3852f696.png)
![RAS11](https://user-images.githubusercontent.com/107056915/172879729-6b9bc533-c844-47fc-b8da-62e59ab20e30.png)
![RAS12](https://user-images.githubusercontent.com/107056915/172879738-43de4c26-1ed8-4c43-b692-3cdde8a01a72.png)
![RASLABEL](https://user-images.githubusercontent.com/107056915/172879860-54883cbe-c0ad-4be0-8c7b-502586d2a9a6.png)
![RASLABEL1](https://user-images.githubusercontent.com/107056915/172879864-1b09e705-be3b-4287-8d9e-62b167086c0f.png)
![RASLABEL2](https://user-images.githubusercontent.com/107056915/172879919-dde21f84-9199-4f7c-9258-c3f33b632986.png)
![RASLABEL3](https://user-images.githubusercontent.com/107056915/172879923-0dcb21c6-aed6-4de8-bfaa-d57000aa0143.png)
