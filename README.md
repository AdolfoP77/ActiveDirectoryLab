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
<br>
Install RAS
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
Green arrow indicates succesfull installation.
![RASLABEL3](https://user-images.githubusercontent.com/107056915/172879923-0dcb21c6-aed6-4de8-bfaa-d57000aa0143.png)

<br>
Install and Configure DHCP.
<br>
This will allow our windows10 client to receive IP address to access the internet.
![DHCP](https://user-images.githubusercontent.com/107056915/172886822-cb5cd3a2-df53-4ea9-8b37-8d32b7529f37.png)
![DHCP1](https://user-images.githubusercontent.com/107056915/172886838-88d4cf4e-06ca-4bee-9d2d-be88fbb33f0c.png)
![DHCP2](https://user-images.githubusercontent.com/107056915/172886898-e54ece31-5ef6-4e5c-81f4-fc9fe6e5998f.png)
![DHCP3](https://user-images.githubusercontent.com/107056915/172886908-5838a9d2-5ed7-434e-8f04-2b5a453f03f6.png)
![DHCP4](https://user-images.githubusercontent.com/107056915/172886963-7c7c65a2-bf34-4618-bce4-e233f6caf127.png)
![DHCP5](https://user-images.githubusercontent.com/107056915/172886967-f651e042
![DHCP6](https://user-images.githubusercontent.com/107056915/172887040-583e881c-2318-47dc-9d76-c4f0599b5a5b.png)

<br>

Install Scope
![SCOPE1](https://user-images.githubusercontent.com/107056915/172887044-7ae3ef6b-1c23-4f34-ba70-55f363f79fe4.png)
-0b2e-47e6-a229-9d9f657a9bb5.png)
![SCOPE2](https://user-images.githubusercontent.com/107056915/172887153-6851ecae-aeac-4a36-a686-0883d2d2eaee.png)
![SCOPE3](https://user-images.githubusercontent.com/107056915/172887156-e930ede7-445f-465d-8330-cfa2e0ff7c69.png)
![SCOPE4](https://user-images.githubusercontent.com/107056915/172887186-c043cd13-68e3-4971-af1f-4e889749c9ea.png)
![SCOPE5](https://user-images.githubusercontent.com/107056915/172887191-4f7424c4-0306-4544-a996-9614ddb22241.png)
![SCOPE6](https://user-images.githubusercontent.com/107056915/172887225-675b6638-e90d-45bd-806e-adce4bc37fa0.png)
![SCOPE7](https://user-images.githubusercontent.com/107056915/172887233-88781a55-09ed-4031-928a-1cb71af753ea.png)
![SCOPE8](https://user-images.githubusercontent.com/107056915/172887246-bd66d3d8-6b54-47b1-a5e6-edcc44fa2e50.png)
![SCOPE9](https://user-images.githubusercontent.com/107056915/172887251-1b820753-394e-40fe-a087-1b1f84bc0a51.png)
![SCOPE10](https://user-images.githubusercontent.com/107056915/172887286-4b99751d-becc-46e6-81fa-4b8163ca45ac.png)
![SCOPE11](https://user-images.githubusercontent.com/107056915/172887290-700910e0-784c-4aeb-a9c3-8c038d9b955e.png)
![SCOPE12](https://user-images.githubusercontent.com/107056915/172887325-ebb3ada2-becb-4bcc-9563-161005b2dffc.png)
![SCOPE13](https://user-images.githubusercontent.com/107056915/172887332-e1f4dc27-723f-47ce-a9cb-cdac30cf7469.png)
![SCOPE14](https://user-images.githubusercontent.com/107056915/172887366-8bc1e708-e654-4593-afd3-a317d660b82c.png)
![SCOPE15](https://user-images.githubusercontent.com/107056915/172887370-7b14044c-8ae1-44ff-ab13-b9dd6aa32bac.png)
![SCOPE16](https://user-images.githubusercontent.com/107056915/172887401-06906b24-ddfa-4c15-8553-d26065c8b9ea.png)
![SCOPE17](https://user-images.githubusercontent.com/107056915/172887404-cf492394-dab7-48d3-856e-88b7fba9c524.png)
