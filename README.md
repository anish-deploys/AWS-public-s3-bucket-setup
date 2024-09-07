<h1>Project Title: Public S3 Bucket Setup</h1>
<h3>Description</h3>
  <p>This project demonstrates the creation of an Amazon S3 bucket with public access using AWS Management Console. The bucket is configured to allow unrestricted access to its contents, making it suitable for hosting static files such as images, videos, or websites. The project includes steps to set up the bucket, configure public access settings, and verify access permissions, serving as a reference for setting up publicly accessible resources in S3.</p>
<h3>Objectives</h3>  
   <ul>
        <li>Create an S3 bucket with public access enabled to host static files or content.</li>
        <li>Configure bucket policies and permissions to allow public read access while ensuring security best practices.</li>
        <li>Verify and test public access to the S3 bucket by uploading files and checking accessibility through a public URL.</li>
    </ul>
<h3>Execution</h3>  

<hr></hr>

<h4>Step 1 : Open your AWS Management Console</h4>

<hr></hr>

![1](https://github.com/user-attachments/assets/7751c7f4-4c40-44bd-a40d-25c95f0330da)

<hr></hr>

<h4>Step 2 : Select the S3 Service from the Search Bar</h4>

<hr></hr>

![2](https://github.com/user-attachments/assets/6be3c6f4-1f7b-4870-bbee-419b3f055246)

<hr></hr>

<h4>Step 3 : Select Create Bucket</h4>

<hr></hr>

 ![3](https://github.com/user-attachments/assets/093b8994-eb7c-43d6-9997-3f58d48b2ad2)

 <hr></hr>

<h4>Step 4 : Give a unique name to create bucket and ACL's should be enabled</h4>

<hr></hr>

![4](https://github.com/user-attachments/assets/42d4b9b9-cf92-4bc0-a708-8f5bdaa90acd)

<hr></hr> 

<h4>Step 5 : Select Object Ownership as Object Writer and uncheck the Block all public access option and checkbox the acknowledgement option to proceed</h4>

<hr></hr> 

![5](https://github.com/user-attachments/assets/907fe956-09b8-4d27-bf14-371724689c8b)

<hr></hr> 

<h4>Step 6 : Select Create Bucket to successfully create the bucket</h4>

<hr></hr> 

![6](https://github.com/user-attachments/assets/fbb9e20f-70d9-49a5-9d12-32f3d497bbb8)

<hr></hr>

<h4>Step 7 : Select the bucket and Open Objects tab</h4>

<hr></hr>

![7](https://github.com/user-attachments/assets/b85cf3cd-277a-4c90-b979-84293acaf815)

<hr></hr>

<h4>Step 8 : Select Upload to add files or folders</h4>

<hr></hr>

![8](https://github.com/user-attachments/assets/0260a77d-40ee-4190-9f80-8d3124a48334)

<hr></hr>

<h4>Step 9 : Open the properties tab of the uploaded file/folder, there you can see the Object URL</h4>

<hr></hr>

![9](https://github.com/user-attachments/assets/2d24f919-3d42-4e43-bc79-30b67751db72)

<hr></hr>

<h4>Step 10 : Go to the permissions tab and select edit</h4>

<hr></hr>

![10](https://github.com/user-attachments/assets/6274e93b-717b-47ff-bade-6ed53d2249f8)

<hr></hr>

<h4>Step 11 : Checkbox the Read in Objects to gain public access and also checkbox the understanding and then save</h4>

<hr></hr>

![11](https://github.com/user-attachments/assets/763922e0-8beb-4ca7-983b-90edd7abd3eb)

<hr></hr>

<h4>Now the URL in the properties tab can access everyone</h4>

<hr></hr>

![12](https://github.com/user-attachments/assets/d61787a9-9b6a-45f9-ad4b-cb4e9244db50)

<hr></hr>
