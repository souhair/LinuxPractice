1. Create three virtual machines in VirtualBox

    ![1](https://user-images.githubusercontent.com/25878224/224850734-a82484fe-b9b8-4773-b2c2-9e11c71e6bf2.PNG)

2. Rename the hostname for the three VMs
    - Linux A hostname called souhairserver
    ![hostname1](https://user-images.githubusercontent.com/25878224/224851340-bea6e79f-a6c6-40eb-a44f-dd2023e6003d.PNG)


    - Linux B hostname called souhairgateway
    ![hostname2](https://user-images.githubusercontent.com/25878224/224852802-ccc60827-ced8-448a-9bb7-bdb4d51e45b2.PNG)

    - Linux C hostname called souhairclient
    ![hostname3](https://user-images.githubusercontent.com/25878224/224851349-422d36ed-e4e3-4f80-ae5d-f85e79891276.PNG)


After renaming we have to reboot VM.
3. Create new user for each VM and name it souhair_1, souhair_2, souhair_3 recpectively

- Linux A: new user called souhair_1
    ![user1](https://user-images.githubusercontent.com/25878224/224853045-de609537-bf40-4ec0-b8ca-4c3000e2d8cf.PNG)

- Linux B: new user called souhair_2
    ![user2](https://user-images.githubusercontent.com/25878224/224853066-a1225ce1-33bd-4ffc-a6dc-b15457c59af3.PNG)

- Linux C: new user called souhair_3
    ![user3](https://user-images.githubusercontent.com/25878224/224853080-5118e568-926b-46a3-8c9d-1a3cd50c931b.PNG)

4. Network Settings for VMs
   ### - Linux A
    
    ![adapter A-1](https://user-images.githubusercontent.com/25878224/224854061-f0a08f4d-f597-4caf-9cb9-75c7684030e2.PNG)
    

    ![adapter A-2](https://user-images.githubusercontent.com/25878224/224854117-e9f9c785-d41e-43fa-97c1-3637249a69ee.PNG)


   ### - Linux B


    ![adapter B-1](https://user-images.githubusercontent.com/25878224/224854125-5b662429-c508-425f-ac66-273611d2dcb1.PNG)
    

    ![adapter B-2](https://user-images.githubusercontent.com/25878224/224854144-3ca62341-bf4a-40a3-b2f9-4a6988b85bea.PNG)
    

    ![adapter B-3](https://user-images.githubusercontent.com/25878224/224854156-ef97d6b7-2e35-45f0-bde7-c222b22d9c2c.PNG)

   ### - Linux C


    ![adapter C-1](https://user-images.githubusercontent.com/25878224/224854199-53cbe18f-00f3-425d-9733-dc0b32df9c9d.PNG)
    
    ![adapter C -2 neww](https://user-images.githubusercontent.com/25878224/224864839-c11e892d-a6c4-4cdd-b1ee-cd85ab357bdd.PNG)


5. Connect virtual machine to the subnet with your laptop.
   ### - Linux A 
   
    ![ip addr 1](https://user-images.githubusercontent.com/25878224/224855027-5fc5a249-8d1f-4f2d-939c-71a4d37367d8.PNG)
 
    ![check ip A](https://user-images.githubusercontent.com/25878224/224855799-7e0a25d4-9d64-4c0d-a89f-8e2f2694e588.PNG)
 
   ### - Linux B
  
    ![ip addr 2](https://user-images.githubusercontent.com/25878224/224855042-fb45a831-9a7b-4ae1-b797-027656054b4d.PNG)
  
    ![check ip B](https://user-images.githubusercontent.com/25878224/224855826-8b6fceec-d58e-4b3d-98f3-63eecb944ae1.PNG)

   ### - Linux C
  
    ![ip addr 3](https://user-images.githubusercontent.com/25878224/224855065-7c181d53-c321-426f-ae95-7dca868e039b.PNG)

    ![check ip C](https://user-images.githubusercontent.com/25878224/224855852-571409e9-e1f5-4c83-99c1-6190bbd4c6b9.PNG)

6. Setting up an SSH connection with machines
   ### - Linux A 
   
    ![ssh A-1](https://user-images.githubusercontent.com/25878224/224857215-7f644c6d-2923-4766-83b3-84d2ae0eb606.PNG)
   
    ![ssh A-2](https://user-images.githubusercontent.com/25878224/224857234-dab26f6b-123f-4bc6-ac34-2b8ff778b597.PNG)

   ### - Linux B
   
    ![ssh B-1](https://user-images.githubusercontent.com/25878224/224857266-e814e9a3-9ca5-44d6-85f0-dee666bfd854.PNG)

    ![ssh B -2](https://user-images.githubusercontent.com/25878224/224857276-790394fa-589e-42d2-9493-7ead57a71eda.PNG)
   
    ![ssh B-3](https://user-images.githubusercontent.com/25878224/224857282-d8beddbe-be07-40cd-bd9e-a1380296e2ae.PNG)

   ### - Linux C
   
    ![ssh C -1](https://user-images.githubusercontent.com/25878224/224857314-7ae968c1-8c1e-4dd0-96dc-43081cd56a0d.PNG)

    ![ssh C -2](https://user-images.githubusercontent.com/25878224/224857330-541b5867-0833-4ea6-b038-b0a111bd0908.PNG)

7. Configration neworks and adapters for machines
  ### - Linux A 
  ![netplan config A -1](https://user-images.githubusercontent.com/25878224/224859158-9b387d51-9b03-46fa-8339-49a52b8d4e9b.PNG)

  ![netplan config A -2](https://user-images.githubusercontent.com/25878224/224859181-5b0f1bf9-9018-44fb-9653-8689ca25447f.PNG)

  ### - Linux B 
  
   ![netplan config B -1](https://user-images.githubusercontent.com/25878224/224858856-5c6fd46a-f03e-49ba-b2c9-331ec02d43a2.PNG)
  
   ![netplan config B -2](https://user-images.githubusercontent.com/25878224/224858866-7cfcd918-0825-4d2e-b2ee-87e3fdab23ee.PNG)
  
  ### - Linux C 

   ![netplan config C -1](https://user-images.githubusercontent.com/25878224/224858925-92a3b892-386c-4f4f-a333-81fb5bbddc05.PNG)

   ![ip addr C Neww](https://user-images.githubusercontent.com/25878224/224864978-e00fbd20-658b-4608-a82b-709223d7a0ea.PNG)

    
8. Route configuration 
    - check the connection between server and gateway using tcp over enp0s8
    
    ![tcp B - A](https://user-images.githubusercontent.com/25878224/224865139-45c038ba-2197-48f5-a844-9645f62cae7e.PNG)

    
    - check the connection between client and gateway using tcp over enp0s9

    ![tcp B -C](https://user-images.githubusercontent.com/25878224/224865158-3425933c-7137-4edb-b0dd-a3539520c99e.PNG)

    - connection between sever and client over gateway 
        - The easiest way with the current configuration is to allow ip packet forwarding in our gateway
    
10. Web Server (Machine A)


12. Web Client (Machine C)


