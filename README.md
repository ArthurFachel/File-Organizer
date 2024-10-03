Setup

    Clone the repository or save the script to your desired location.

    Install dependencies: Use pip to install the necessary libraries. Run:

    bash

pip install whatchdog
Edit the script:

    Open the script in your favorite editor.
    Set the following variables with appropriate paths:
        source_dir: The directory where the script will monitor for new files.
        dest_dir_image: The directory where image files will be moved.
        dest_dir_documents: The directory where document files will be moved.

Run the script:

    Execute the script with:

    bash

        python autoscript.py

        The script will start monitoring the source directory and move files to their corresponding folders based on their extensions.

Customization

    You can add more file extensions to image_extensions and document_extensions lists to extend the functionality.

Logging

    The script will log moved files with a timestamp, showing the type and name of the files being moved.

Stopping the Script

    To stop the script, press Ctrl + C in the terminal where it is running.

Example

If you set:

    source_dir to "/Users/yourname/Downloads",
    dest_dir_image to "/Users/yourname/Pictures",
    dest_dir_documents to "/Users/yourname/Documents",

Then all new images and documents added to the Downloads folder will be automatically moved to the Pictures and Documents folders, respectively.
