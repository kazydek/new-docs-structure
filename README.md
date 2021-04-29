See how a sample docs structure will look like on [GitHub](/github).

Some more detailed examples of subfolders, floating docs, and regular docs are shown in the [Operational Guides](/github//04-operational-guides).

Important info:

- Each folder must contain a `metadata.yaml` file that defines the folder's display name.

- Display name of a given doc is defined in its metadata.

- Both folders and files will be clickable on the website.

- Order of folders and files is alphabetical. The order of a doc or folder can be modified by adding its preferred position in the left navigation in the form of a prefix (`01`,`12`, etc.).

- "Floating files" refer to the docs that are "hanging" under a given folder with subfolders. Most often, they are to give some basic info about the given folder or provide some intro to the subfolders.

  > **NOTE:** There can be more than just one floating file!

- [FUTURE?] Unless you specify otherwise in the `metadata.yaml`, if you click on a given node (e.g. tutorials) that has no floating docs, the website will display the first document from the first subfolder on the list.
