This is the solution to DLW Backup Track 3, which revolves around creating a deep learning solution that resolves the gap in proper security for underserved rural communities.

Our solution is a computer vision model that leverages Ultralytics' YOLOv8-nano (pre-trained DL human detection model) for the purpose of detecting crowds of anomalous size that persist past a certain time threshold,
and subsequently sending an alert message to the end user.

The repository has detailed PDF documentation and an MP4 demo video to see the decisions behind the solution and the solution in action respectively.

It is worth noting that the test videos were too large for GitHub, but the documentation has a link to a Kaggle dataset that contains plenty of CCTV data.
I recommend using longer videos larger than 80 MB as it gives the system ample time to output multiple alerts.
It is also beneficial to have said videos look over a longer stretch of road instead of a very small area, e.g. an ATM or a cashier's desk.

The demo video is linked in the Google Drive folder: https://drive.google.com/drive/folders/1ThCdiNbArJeNVykRzA7_h2hDtkayiOh0?usp=drive_link
