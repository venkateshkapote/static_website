Step 1: Create an S3 Bucket

1.   Sign in to the AWS Management Console
     Navigate to the [AWS Management Console](https://aws.amazon.com/).
     Sign in with your AWS account credentials.

2.   Navigate to S3:
   - In the AWS Management Console, go to the "S3" service.

3.   Create a Bucket:
   - Click the "Create bucket" button.
   - Choose a unique and meaningful name for your bucket.
   - Select the region for your bucket (choose a region close to your target audience for better latency).

4.   Configure Options:
   - Choose the default settings for "Configure options."

5.  Set Permissions:
   - For "Set permissions," you can either configure the bucket to be private or make it public. If you want your website to be publicly accessible, you'll need to configure the bucket policy or enable public access.

6. mReview:
   - Review your settings and click "Create bucket."

Step 2: Upload Your Website Files

1.  Open Your Bucket
   - In the S3 console, open the bucket you just created.

2.  Upload Files:
   - Click the "Upload" button.
   - Add all your static website files (HTML, CSS, JavaScript, images, etc.) to the bucket.
   - photo that you wanna add on website add also upload it

3.  Set Permissions:
   - Make sure to set permissions for your files to be public if you want your website to be publicly accessible.
   - Select the files, click on "Actions," and choose "Make public" or configure the permissions accordingly.

Step 3: Configure Your Bucket for Static Website Hosting

1.  Bucket Properties:
   - In your bucket, go to the "Properties" tab.

2.  Static Website Hosting:
   - Scroll down to the "Static website hosting" card.
   - Click the "Edit" button.
   - Choose the "Use this bucket to host a website" option.

3.  Index Document:
   - Specify the index document (e.g., "index.html").

4. go to bucket permission and go to bucket policy and edit and paste code and update your bucket name so that it can be publicly available and save changes
   - 

5.  Save Changes:
   - Click "Save changes."

Step 4: Obtain the Website URL

1.  Access Endpoint:
   - In the "Static website hosting" card, you'll find the endpoint URL (e.g., `http://your-bucket-name.s3-website-your-region.amazonaws.com`).

2.  Verify:
   - Open a web browser and navigate to the endpoint URL to verify that your website is accessible.

