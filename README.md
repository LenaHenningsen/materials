# Material Filing Template
This repo contains a folder template and readme instructions for how to go about storing the primary source materials collected during field work.

The goal is to use and document a uniform filing system to maintain long-term usability of our data. The easiest way to use this repo is to simply fork it and start filling out the provided templates. Of course you are free to start creating them from scratch too, as long as you follow the conventions defined here.


## Important
Before backing-up files via GitHub you must decide if the data you are about to share is in the public domain, or if it contains sensitive information and should remain private for either legal or privacy reasons.

Sensitive data **must** be encrypted before uploading, it should be stored in private repos only! You have received detailed instructions for how to encrypt files before uploading. This information will not be repeated here.

Once you have determined if your files are either private or public you can simply follow the instructions outlined below.

## How To
This repo contains two top-level folders `audio` and `image`, since these are the most frequent data types you are likely to collect during field work. Should you wish to collect a significant number of other file types simple create a new top level folder and name if after the data-type of the files collected there, e.g. `text`. Each folder contains a `readme.md` file that outlines the naming and folder conventions and contains some boilerplate for you to fill in when you are collecting data in the field. They also contain a sample file for demonstration purposes, make sure to delete the sample file before publishing your data.


### Step-by-Step
1.  Go to a folder on your hard-drive where you want to collect the data, e.g. `my-data`. Make sure not to use whitespaces for folder names, so not ~~`My Data`~~.
```bash
cd my-data
```

2.  Clone this repo
```bash
git clone https://github.com/readchina/materials.git
```

3.  Navigate to the folder with the first letter of your surname (**H**enningsen, **L**in, **M**andzunowski, **P**aterson,**Y**ang) and the correct file type, e.g.: 

```bash
cd materials/audio/Y
```

4.  Check the `readme.md` for either [audio](image/readme.md) or [image](audio/readme.md) files as necessary and fill out the template.

5.  Add you files

6.  Create a new repo for your files (if necessary) and commit and push as usual.
