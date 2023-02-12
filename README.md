<h1>How to build event-driven serverless image application</h1>

<h2>Description</h2>

In this project I will be demonstrating how I built an event-driven serverless image processing pipeline using S3 event notifications and Lambda. The pipeline uses two S3 buckets, a source bucket and a processed bucket. When images are added to the source bucket a Lambda function is triggered based on the PUT. When invoked the Lambda function receives the event and extracts the bucket and object information. Once those details are known, the Lambda function, using the PIL (Pillow known as PIL this is a library which allows Python to perform operations on images.) module pixelates the image with 5 different variations (8x8, 16x16, 32x32, 48x48 and 64x64) and uploads them to the processed bucket. 

<br />


<h2>Services Used</h2>

- <b>S3</b>
- <b>IAM</b> 
- <b>Lambda</b> 

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>Program walk-through:</h2>
<H3>Step 1 - Create S3 bucket and upload content</H3>
<img src="https://i.imgur.com/a30DOD0.png" height="80%" width="80%" alt="Image 1"/>

<H3>Step 2 - Create S3 bucket and upload content</H3>
<img src="https://i.imgur.com/L79YUH2.png" height="80%" width="80%" alt="Image 2"/>


<H3>Step 3 - Create S3 bucket and upload content</H3>
<img src="https://i.imgur.com/ouSc9gY.png" height="80%" width="80%" alt="Image 3"/>


<h2>Selecting one of the pixelated images</h2>

<img src="https://i.imgur.com/m3FRkYg.png" height="80%" width="80%" alt="Image 1"/>


<h2>YouTube Demonstration </h2>

[How to build event-driven serverless image application](https://youtu.be/gA0x_mbkN-c)



</p>
