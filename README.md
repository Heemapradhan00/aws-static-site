# Static Website Hosted on AWS S3

This project demonstrates how to host a static website on Amazon S3. The site consists of a simple HTML and CSS page showcasing AWS S3's capabilities for static hosting.

## Features
- Fully static website hosting on AWS S3.
- Publicly accessible via the provided S3 URL.
- Simple HTML and CSS for styling.

## Files
- **index.html**: The main webpage file.

## Steps to Recreate
1. *Set Up AWS S3 Bucket:*
   - Create an S3 bucket with public access.
   - Upload the index.html and style.css files.

2. *Enable Static Website Hosting:*
   - Go to the bucket's *Properties* tab.
   - Enable *Static Website Hosting* and specify index.html as the index document.

3. *Make the Bucket Public:*
   - Add a bucket policy to allow public access to the files.

4. *Access the Website:*
   - Copy the *Endpoint URL* from the *Static Website Hosting* section.
   - Paste the URL into your browser to view the site.

## Example Output
https://my-static-stite-heema.s3.ap-south-1.amazonaws.com/Weather+app.html 
![image](https://github.com/user-attachments/assets/7eaeff3e-14b8-4e7c-837b-30af02c8518d)


## Technologies Used
- *HTML5*
- *CSS3*
- *AWS S3*

## How to Run Locally
1. Clone the repository:
   bash
   git clone https://github.com/heema pradhan/aws-static-site.git
   
2. Navigate to the folder:
   bash
   cd aws-static-site
   
3. Open index.html in your browser.

---

Feel free to update this README with your own bucket name, endpoint URL, and project-specific details!
