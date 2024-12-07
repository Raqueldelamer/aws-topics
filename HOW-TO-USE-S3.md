## **How to Use AWS S3**

## **Getting Started**
- You will need to create an account @ https://aws.amazon.com/console, which requires personal credit card information in order to create an AWS account. 
- The next step is to setup the necessary authentication to secure it.
- Sign in to AWS created account
- Navigate to Amazon S3 Service

## **Create a New Bucket**
- Click on Create bucket
- Enter an unused name for your bucket 
- Once a name is approved, Click on Create Bucket
- Enable public access in Permissions tab in General purpose buckets screen
- In Block public access (bucket settings) , click Edit and uncheck "Block all public access" 
- Save changes 

## **Create a Bucket Policy**
- Step 1: On AWS Policy Generator, Select Policy Type => choose S3 Bucket Policy
- Step 2: Add Statements (Effect => Allow: Principal=> *: AWS Service => Amazon S3:
    Actions => GetObject)
- Step 3: Generate an Amazon Resource Name (ARN) 

## **Generate Bucket Policy**
- After entering an ARN click on Generate Policy
- Once Bucket policy JSON is given, copy and paste to "Bucket policy editor" and SAVE

## **Upload Images**
- upload images and click on upload again.
- click on uploaded image and it will open a new window in browser with the image url.
- copy and paste image URL on browser to test & share

## **Key Concepts Explained**
- Bucket = A logical container in Amazon S3 where data, such as images or files, is stored. Each bucket must have a unique name globally.
- Policy = A JSON document that specifies permissions and defines who can access your bucket and its objects.
- ARN (Amazon Resource Name) = A unique identifier for AWS resources. Example: arn:aws:s3:::my-uniquesitename-images-123/* 