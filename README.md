# Automatic Folder Backup Scheduler

The Automatic Folder Backup Scheduler is a versatile Python script for automating the backup of folders from a specified source directory to a destination directory on a daily basis. It provides users with a convenient solution for ensuring the safety and organization of their important files without manual intervention.

## Features

- **Automated Backup:** Automatically backs up folders from a specified source directory to a destination directory.
- **Daily Schedule:** Utilizes the `schedule` library to schedule the backup process to run at a predefined time each day.
- **Folder Organization:** Copies the contents of the specified folder to a destination directory named with the current date for easy organization and retrieval.
- **Flexible Configuration:** Users can specify the source and destination directories, as well as the scheduled backup time, to suit their specific needs.
- **Error Handling:** Provides informative messages for existing destination folders and ensures smooth execution of the backup process.

## Usage

1. Clone the repository to your local machine.
2. Ensure you have Python installed on your system.
3. Install the required dependencies using pip: pip install schedule
4. Open the script in a text editor and modify the `source_dir`, `destination_dir`, and `backup_time` variables to specify the source and destination directories, as well as the scheduled backup time.
5. Open a terminal window and navigate to the project directory.
6. Run the script using the appropriate command for your operating system (e.g., `python automatic_backup_scheduler.py`).
7. The script will automatically run at the scheduled time and copy the contents of the specified folder to the destination directory.

## Dependencies

- This project requires the `schedule` library for scheduling the backup process. You can install it via pip: pip install schedule
- The script uses built-in Python modules such as `os`, `shutil`, `datetime`, and `time`.

## Contributing

Contributions to the Automatic Folder Backup Scheduler are welcome! If you have suggestions for improvements, bug fixes, or new features, please feel free to submit a pull request.

Happy backing up!
