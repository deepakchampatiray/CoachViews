# CoachViews
IBM BPM Coach Views that make sense.

# TODO
1. **Expandable Output Text (DCR_OutputText_Exp) :**
An output text that collapses the text contents when it exceeds a specified limit. It will show an icon that will toggle the full text, either in the same space or as a pop-up. This will be particularly useful when we want to display very long text on the UI.
1. **Masked Output Text (DCR_OutputText_Mask) :**
An output text part of which's value can be masked (based on a regular expression). It will show an optional icon (based on configuration parameters) that will show the full text. This will be useful when it is necessary to display only partial information on the user screen (credit card numbers, SSN, ...).
1. **Drag and drop file upload :**
A file upload coachview that supports drag-and-drop. The upload service should begin as soon as the file is dropped inside the drop-zone. An option of enabling or disabling this feature should be available. A list of all files uploaded should be visible as well. It must support uploading of multiple files at once. It should show a continuously updating percentage status of the progress of file-upload. Design of the uploader should resemble [this](https://cdn-images-1.medium.com/max/800/1*Krw2Zqd9adJPUYnhuiHF-w.png). This mode should only be enabled in the desktop version. In the mobile version of the coach-view it should fall back to using the traditional UI for file upload.
