{{{
  "title": "Create Manual Checkpoint",
  "date": "12-27-2017",
  "author": "Anshul Arora",
  "attachments": [],
  "contentIsHTML": false
}}}

### Article Overview
This article explains how to create a manual checkpoint using SafeHaven Console.

### Assumption
Protection Group has completed initial replication.

### Create Checkpoint
1. Right click the protection group, and click **Create Manual Checkpoint**.
2. Check **Use VSS** if a VSS checkpoint is needed **only for Windows**.
3. Click **Create**.
4. The **Manual Checkpoint** job will appear at the bottom of the screen.
5. Once **Create Image** job is complete, click on **Checkpoint History** to view the checkpoint. (This may take a few minutes/hours depending on the EBS Snapshot and AMI creation process.)

### Video Tutorial
<p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/OG60GTH7rUw" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
</p>

As a **Next Step** the user may wish to do a [Test Failover to AWS](Test Failover to AWS.md)