# Perform Foundational Infrastructure Tasks in Google Cloud: Challenge Lab

## Task 1: Create a bucket
In the console, click the Navigation menu > Storage.
Click Create a bucket.

<br/>
<br/>

## Task 2: Create a Pub/Sub topic

In the console, click the Navigation menu > Pub/Sub > Topics.

Click Create a topic.

imp: Make sure you remember the topic name, which will be used in Task 3.
<br/>
<br/>
## Task 3: Create the Cloud Function
In the console, click the Navigation menu > Cloud Functions.

Click Create function.

In the Create function dialog, enter the following values:

Field	Value

Function to execute	thumbnail

Runtime	Node.js 10

Trigger	Cloud Storage

Copy the given index.js and package.json to the dialog.

Make sure you replace the text REPLACE_WITH_YOUR_TOPIC with the topic you created in task 2, in line 15 of index.js.

Upload a JPG or PNG image file to the bucket created in Task 1.

<br/>
<br/>

## Task 4: Remove the previous cloud engineer
In the console, click the Navigation menu > I AM.

Find the second user.

Click the pencil icon, select Delete.



Congratulations! You completed this challenge lab.
