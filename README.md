# Efficient-and-Scalable-Application-Delivery-with-Azure-Load-Balancer-and-Virtual-Machine
Deploy webserver with Load Balancer And Vm Scale Set

#  Diagram-1
![Screenshot 2023-02-25 182443](https://user-images.githubusercontent.com/113555417/221364325-72f405bc-2128-4709-a893-cb5ba580dc9a.jpg)

# Diagram-2
![Screenshot 2023-02-25 182409](https://user-images.githubusercontent.com/113555417/221364336-f6d90472-22b9-4d63-8a09-efe2b55a9a1f.jpg)

>>>>   # Create Virtual Machine Scale set   <<<<
  # fill details as per our Project requirnment

![Screenshot 2023-02-25 121521](https://user-images.githubusercontent.com/113555417/221364619-a0447a20-a8c0-4781-b5fa-fd42075999e6.jpg)
![Screenshot 2023-02-25 121615](https://user-images.githubusercontent.com/113555417/221364621-db137af2-7333-4989-982c-3bbb8e95eeba.jpg)
![Screenshot 2023-02-25 121633](https://user-images.githubusercontent.com/113555417/221364622-87286a27-7503-4fbd-ba64-71f9109bf4b7.jpg)
![Screenshot 2023-02-25 121652](https://user-images.githubusercontent.com/113555417/221364623-d7e091dd-9ad2-445a-a6c2-3eb4663fab5f.jpg)
![Screenshot 2023-02-25 122151](https://user-images.githubusercontent.com/113555417/221364625-e3e82f3a-e350-4477-bd99-aaaee144dc3a.jpg)

>>>>   # VMSS OverView <<<<

![Screenshot 2023-02-25 170423](https://user-images.githubusercontent.com/113555417/221365664-dceeecd2-a647-44aa-9f82-8ab43857bb34.jpg)

>>>>  # Instances <<<<
![Screenshot 2023-02-25 123425](https://user-images.githubusercontent.com/113555417/221364759-26d668d1-d790-4f7f-9bd2-60bb68cc9b22.jpg)
![Screenshot 2023-02-25 170454](https://user-images.githubusercontent.com/113555417/221365056-3f0aae3c-1cdd-4326-a226-d4931158c3a5.jpg)
![Screenshot 2023-02-25 170505](https://user-images.githubusercontent.com/113555417/221364856-6a939beb-c279-44f7-9d59-91e9835f4348.jpg)

>>>>  # Create Virtual Machine  with public Ip address <<<< 

![Screenshot 2023-02-25 140851](https://user-images.githubusercontent.com/113555417/221364773-7032bda5-802e-4399-90a9-d86d0c8f6f86.jpg)
![Screenshot 2023-02-25 140905](https://user-images.githubusercontent.com/113555417/221364775-fa995d5b-d5b5-4f42-95ed-366b49449be7.jpg)
![Screenshot 2023-02-25 140918](https://user-images.githubusercontent.com/113555417/221364777-b96c0c51-228f-44d2-b6ab-14b8f18fad8e.jpg)
![Screenshot 2023-02-25 140930](https://user-images.githubusercontent.com/113555417/221364779-ba505baf-a4d4-4a2f-ad2d-8f6df0c7a836.jpg)

>>>> # OverView <<<<

![Screenshot 2023-02-25 170515](https://user-images.githubusercontent.com/113555417/221364829-729443c5-41fd-44c3-9dcf-b5e216efbd3d.jpg)


>>>>  # Access our public Vm through RDP  & install IIS server <<<<
      # And VMSS instances access through private Ip using RDP 
![Screenshot 2023-02-25 132011](https://user-images.githubusercontent.com/113555417/221365332-59a7b6de-72ae-4fe1-b5fb-1d59006f72c4.jpg)
![Screenshot 2023-02-25 153705](https://user-images.githubusercontent.com/113555417/221365348-fe2d9d29-4bfb-4ced-b916-ee2021bbae05.jpg)

>>>> # Create Load Balancer  <<<<
![Screenshot 2023-02-25 170530](https://user-images.githubusercontent.com/113555417/221365787-6b3e4c96-8ae1-4558-80a2-f939fc07a205.jpg)
 >>>> # FronIp configure <<<<
![Screenshot 2023-02-25 170551](https://user-images.githubusercontent.com/113555417/221365792-870eed8c-018a-4dba-bcc7-c685629f3303.jpg)
 >>>> # Backend Poool <<<<
![Screenshot 2023-02-25 170609](https://user-images.githubusercontent.com/113555417/221365794-c4de2240-9f9d-48be-bde3-4ea82efd0a30.jpg)
>>>> # add virtual machine <<<<
![Screenshot 2023-02-25 170626](https://user-images.githubusercontent.com/113555417/221365815-33546f14-66d4-4a5e-8585-04ca8b00c12d.jpg)
![Screenshot 2023-02-25 170641](https://user-images.githubusercontent.com/113555417/221365817-631e0eb5-b539-4502-8c2c-65a6143fa847.jpg)
>>>> # Health Prob <<<<
![Screenshot 2023-02-25 170700](https://user-images.githubusercontent.com/113555417/221365820-50329e93-f7fa-42c5-ad73-2282f700eb79.jpg)
>>>> # LoadBalancer Rule <<<<
![Screenshot 2023-02-25 170717](https://user-images.githubusercontent.com/113555417/221365823-720c06d2-62e2-406f-a5d8-5808a401af12.jpg)
>>>> # NatRule <<<<
![Screenshot 2023-02-25 170735](https://user-images.githubusercontent.com/113555417/221365825-603b3dda-01dc-48dc-b1ef-b73874501f8a.jpg)

>>>> # Check Server Using Frontend Ip <<<<

![Screenshot 2023-02-25 172143](https://user-images.githubusercontent.com/113555417/221365911-6d952633-1781-4c5c-a106-68f9ff800b53.jpg)
![Screenshot 2023-02-25 170814](https://user-images.githubusercontent.com/113555417/221365917-74ec9ff2-c73d-45a1-afc0-65d4d7b4f035.jpg)


>>>> # Virtual Machine Scale Set Rule <<<<
   # Custom autoscale 
![Screenshot 2023-02-25 173529](https://user-images.githubusercontent.com/113555417/221365965-84453f89-4010-430e-8f39-a624e4b774c5.jpg)
![Screenshot 2023-02-25 173711](https://user-images.githubusercontent.com/113555417/221365969-73f17a86-929d-495d-b6d9-6201ff7e7e4f.jpg)
>>>> # scale Rule <<<<
![Screenshot 2023-02-25 173947](https://user-images.githubusercontent.com/113555417/221365970-6f32058a-a23d-4ccb-8a86-8d5a20561171.jpg)
![Screenshot 2023-02-25 174001](https://user-images.githubusercontent.com/113555417/221365972-8746477a-26d5-44a5-afb9-21471b7680ab.jpg)
![Screenshot 2023-02-25 174050](https://user-images.githubusercontent.com/113555417/221365974-7d4fab1b-0886-47a0-ba41-4b389c708cc3.jpg)

>>>> # Create a.bat file and Run a.bat file for Checking autoscale working or not <<<<

![Screenshot 2023-02-25 175506](https://user-images.githubusercontent.com/113555417/221366107-232ce01d-ae71-4a7f-b087-46ffa651a40f.jpg)
![Screenshot 2023-02-25 175536](https://user-images.githubusercontent.com/113555417/221366109-30902890-c889-425f-8cb5-22861a26f72e.jpg)
![Screenshot 2023-02-25 175753](https://user-images.githubusercontent.com/113555417/221366110-1f3a78fd-8020-4818-8628-6cac969147ba.jpg)
![Screenshot 2023-02-25 175926](https://user-images.githubusercontent.com/113555417/221366112-56e1572a-d1f3-4358-b5c7-cd96a0733c10.jpg)
![Screenshot 2023-02-25 180029](https://user-images.githubusercontent.com/113555417/221366113-74f92e6d-7636-497f-a617-0529b6cf1479.jpg)
![Screenshot 2023-02-25 180118](https://user-images.githubusercontent.com/113555417/221366114-771d41e3-b680-4b82-a31a-0bb00433da69.jpg)

>>>> # Final Diagrams <<<<

![Screenshot 2023-02-25 182357](https://user-images.githubusercontent.com/113555417/221366139-6df0e0bb-b838-4c7e-b777-bd43e2301aa2.jpg)

![Screenshot 2023-02-25 182427](https://user-images.githubusercontent.com/113555417/221366141-521137f6-0aad-40c5-a9de-288f96f5c964.jpg)

