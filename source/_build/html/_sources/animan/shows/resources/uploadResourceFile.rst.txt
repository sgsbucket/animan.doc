.. _uploadResourceFile:

Upload Resource File
========================


Privileges Required:
 - admin
 - or EDIT RESOURCE privilege
 - or assigned worker/reviewer of the current stage

Location:
 - (page) Resource
 - (page) Shot

Members who has the privilege to edit the file of a resource can upload files to the resource.

Everytime a new file is uploaded to the resource, the file will be given a version and marked as the latest version.
All previous versions of the file are kept in animan for references.


To upload a file to the resource:

#. If you are eligible to upload a file, you can find the Check In/Out bar on Resource page (or Shot page).

   .. image:: check_in_out_bar.png
     :width: 100%
     :alt: Check In/Out Bar

#. Click "Check Out" button.
   - When a resource is checked out, it is locked to other members. Only the one who checks out the resource can upload files of this resource.
#. Once the resource is checked out, a file drop zone will appear in the file box with a "Browse" button.
#. Drag a file to the drop zone or click "Browser" button to select the desired file.
   - The file must be the type of the :ref:`resourceCategory` that the resource belongs to.
#. Click "Upload" to start uploading.
#. Click "Check In" button to release the lock of the resource.
   - Alternatively, a worker can click "&#10004; (Done)" button which is located on the right of the "Check In" button.
     This "Done" button will check in the file and also move the resource to the next stage.


Save Elsewhere
++++++++++++++

For a not-shot resource, you have an extra option to choose after you click "Upload" button, "Save Elsewhere".
This function is for files that are very large to download/upload, and is easier to be placed in a shared storage in your studio.

You will provide a url and a download instruction and click "Save" to complete the uploading.
When a member try to download the file, he will need to follow the instructions you provided to get the file.
