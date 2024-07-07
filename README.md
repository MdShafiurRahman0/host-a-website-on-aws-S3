
### Host a Website on AWS S3



🌐 Hey everyone! 👋

I'm excited to share my latest project where I created and hosted a simple HTML page with an image on Amazon S3 as a static website. 🎉


#### Description:
This project involves creating a simple yet elegant HTML page designed to showcase a beautiful image. The HTML page was developed with a focus on minimalism, ensuring a clean and visually appealing layout. The page was then hosted using Amazon S3's static website hosting feature, which provides a robust and scalable solution for serving static content. To ensure the website is both secure and accessible, a bucket policy was configured to allow public read access while adhering to security best practices. This project demonstrates effective use of HTML and Amazon S3 for hosting static websites, along with implementing appropriate security measures.


### Project Highlights:

1. **HTML** : Designed a minimalistic HTML page to showcase a beautiful image.
2. **Amazon S3**: Leveraged Amazon S3's static website hosting feature to make the page publicly accessible.
3. **Bucket Policy**: Configured the S3 bucket policy to ensure the website is secure yet accessible to everyone.




### Step 1: Create Bucket in Amazon S3

1.Log in to your AWS Account.
2.In the AWS Management Console, search for S3.
3.Choose Create bucket.
4.AWS Region: select the Region closest to you.
5.For Object Ownership, choose ACLs enabled.
6.Choose Bucket owner preferred.
7.For Block Public Access settings for this bucket, clear the check box for Block all public access.
8.For Bucket Versioning, choose Enable.

💡

![2024-07-07_16h48_32](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/5dab4e3f-911f-45bb-ab40-eff51f4f5d89)

![2024-07-07_17h17_08](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/181ed07d-5754-40b3-aba1-298248af72d6)

![image](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/2da1daf8-a084-4183-838f-c141e9109826)





### Step 2: Upload website content into your bucket

1. Unzip the zip file you've downloaded.
3. Return to the Amazon S3 console with your bucket page open. 
4. Choose the Objects tab.
5. Choose Upload.
6. Choose Add files.
7. Choose index.html.
8. Choose Add folder.
9. Choose the unzipped folder - NOT the zip file itself!
10. You might get a popup that tells you that all files in that folder will be uploaded. 
11. Choose Upload.
12. Choose Upload.
13. S3 will get to work right away!
    
![2024-07-07_17h02_32](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/74e67f2e-14e0-49b1-ba57-6b748cb1b068)




### Step 3: Enable Static Website Hosting

1. Make sure you're back in your bucket's page. 
2. If you're not sure, choose Buckets on the left-hand side navigation bar, and then choose the bucket you created for this project.
3. Choose the Properties tab.
4. Scroll allllllllll the way down to the Static website hosting panel.
5. Choose Edit.
6. Configure the following settings:
    - Static web hosting: Choose Enable.
    - Hosting type: Choose Host a static website.
    - Index document: Enter index.html.
  
      
![2024-07-07_17h12_14](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/69312c51-f83f-4212-8827-c5bb5501e981)




1. Choose Save changes.
2. In the Static website hosting panel under bucket website endpoint, click on the URL.
3. An error! 👀

![2024-07-07_17h14_54](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/90863730-462d-4143-bffb-a0066c945f24)







![2024-07-07_17h21_51](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/3ab23cb8-56da-4d77-8cc3-dcc40c051fa0)




![2024-07-07_17h25_21](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/139c26e7-7991-4a37-986a-de2d5eed22a1)



1.Choose Make public

2.Once the green banner pops up choose Close.

3.Return to the web browser tab that has the 403 Forbidden message

4.Refresh the tab



### Step 4: Write index.html file

![2024-06-19_08h46_44](https://github.com/MdShafiurRahman0/static-website-hosted-on-aws-S3-bucket/assets/113176437/3ec33b99-af7d-40a6-971f-4c10200673fb)



![2024-06-19_08h47_29](https://github.com/MdShafiurRahman0/static-website-hosted-on-aws-S3-bucket/assets/113176437/ecfc33c1-2e53-40bd-93b7-62bf69eb42a5)




### Step 5: Enable Public Access


![2024-06-19_08h47_36](https://github.com/MdShafiurRahman0/static-website-hosted-on-aws-S3-bucket/assets/113176437/be9825cc-9e75-40ba-a5c4-fc22c433bca7)


![2024-06-19_08h48_12](https://github.com/MdShafiurRahman0/static-website-hosted-on-aws-S3-bucket/assets/113176437/a5702d07-0375-47ab-9217-22da2f3b21c6)


![2024-06-19_08h48_53](https://github.com/MdShafiurRahman0/static-website-hosted-on-aws-S3-bucket/assets/113176437/fa80c3db-ef01-4cf5-b5b6-c3d1da9b0250)







### Step 6: Website is hosted on S3 Successfully 


![2024-07-07_17h25_21](https://github.com/MdShafiurRahman0/host-a-website-on-aws-S3/assets/113176437/3fa64177-40e3-4709-91ee-987d00de69c0)


### What I Learned:

- How to create and style a basic HTML page.
- Setting up an Amazon S3 bucket for static website hosting.
- Configuring bucket policies to manage access and permissions.

### Why This Matters:

Hosting static websites on Amazon S3 is an efficient and cost-effective way to deploy simple web pages. This project demonstrates my ability to use cloud services to deliver web content swiftly and securely.



Feel free to leave your thoughts and feedback in the comments. I'm looking forward to hearing what you think! 😊

#WebDevelopment #HTML #CSS #AWS #AmazonS3 #CloudComputing #TechSkills #WebHosting #ProjectShowcase



