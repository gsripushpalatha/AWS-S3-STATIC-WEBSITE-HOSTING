<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Host a Website on Amazon S3

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-host-a-website-on-s3)

**Author:** gsripushpalatha@gmail.com  
**Email:** gsripushpalatha@gmail.com

---

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate WEBSITES USING S3 BUCKETS I'm doing this project to learn... S3

### Tools and concepts

Services I used were...s3 Key concepts I learnt include...creation of buckets,enabling policy

### Time, challenges, and wins

This project took me approximately... 50 minThe most challenging part was.. enabling bucket policy. It was most rewarding to...host a website

---

## How I Set Up an S3 Bucket

### What I did in this step

### How long it took to create the bucket

Creating an S3 bucket took me...10 min

### Region selection

The Region I picked for my S3 bucket was hyd  because it is nearest to me

### Understanding bucket name uniqueness

S3 bucket names are globally unique! This means that your bucket name cannot be used by anyone unless until you delete it

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-host-a-website-on-s3_ba6d42ad)

---

## Upload Website Files to S3

### What I did in this step

In this step, I will DOWNLOAD THE HTML FILE OF MY WEBSITE AND IMAGES because...TO UPLOAD THEMINTO S3 BUCKET

### Files I uploaded

I uploaded two files to my S3 bucket - they were HTML FILE AND IMAGES FOLDER

### How the files work together

Both files are necessary for this project as they show the website

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-host-a-website-on-s3_a265af88)

---

## Static Website Hosting on S3

### What I did in this step

In this step, I will configure s3 bucket for static website hosting because to visit the public link

### Understanding website hosting

Website hosting means to makingwebsite public on internet

### How I enabled website hosting

To enable website hosting with my S3 bucket, I went to properties of the bucket i created

### Access Control Lists (ACLs)

An ACL is... access contol list thatdefines the set of rules that decides the control of resources


![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-host-a-website-on-s3_c22c54c0)

---

## Bucket Endpoints

### Understanding bucket endpoint URLs

Once static website is enabled, S3 produces a bucket endpoint URL, which is the regukar url that allows users to access the website

### What I saw when I tested the endpoint

When I first visited the bucket endpoint URL, I saw 404 forbidden error The reason for this error was that the contents in the bucket are in private

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-host-a-website-on-s3_22ce4daf)

---

## Success!

### What I did in this step

In this step, I will make website public access because. to access

### How I resolved the 403 error

To resolve this 403 Forbidden error, I enabled make publicusingACL

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Bucket Policies

### What I did in this extension

In this project extension I'm about to SET UP BUCKET POLICY I'm doing this so that...TO STOP DELETING MY INDEX PAGE

### Understanding bucket policies

An alternative to ACLs are bucket policies, which are THE POLICIES THAT HELPS TO CONTROL ACCESS he benefit of using bucket policies is. CUSTOMIZED while ACLs are useful for...

![Image](http://learn.nextwork.org/thankful_maroon_lucky_lemongrass/uploads/aws-host-a-website-on-s3_sm2sm2sm)

### What my bucket policy does

My bucket policy... blocked users from deleting my websiteI tested this by...  enabling buxcket policy and saw...website

---

---
