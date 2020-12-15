### Components
# Drag and drop file upload
Use the drag and drop file upload component to help users upload multiple files at the same time.

![Drag and drop file upload image](/images/drag_and_drop.png "Drag and drop file upload image")

[HTML](/components/drag_and_drop/drag_and_drop.html) and [Styles](/components/drag_and_drop/styles.scss) for this component

## When to use this component
The drag and drop file upload component can be useful if you need to let users upload multiple folders at once, on a regular basis. For example, in a case working system.

## When not to use this component
Do not use this component if users only need to upload one file.

Uploading multiple files at the same time is more error-prone than uploading files, one at a time. This is because users have to use a custom form control that may not be as easy to understand.

For this reason, do not use this component unless research shows that users need a faster way to upload files.

## How it works
The drag and drop file upload consists of a dropzone and feedback area which starts off hidden.

Users can drag and drop folders onto the dropzone or click the button and select folders using the folder picker.

Each selected folder will start uploading immediately and appear as a row in the feedback area.

When a folder has been uploaded it will show as:

- green, next to a tick icon, if it’s been uploaded successfully
- red, next to a warning icon, if there’s been an error

For errors use these [error messages](drag_and_drop_error.html)

## Research on this component
The design, code and guidance here are based on [recommendations from the community](https://github.com/alphagov/govuk-design-system-backlog/issues/49).

TDR have tested this pattern on their file upload page and most participants have given positive feedback on all aspects demonstrating they were drawn to the drop-zone area and were able to identify exactly where they can upload their folder.