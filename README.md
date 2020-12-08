# FileUtility
File Utility can be used to do file operation like creating directories, deleting directories, creating files, deleting files, cut paste file and folder, copy paste file and folder, zip and unzip files.
Features:
1. create_directories - To create folders in root path
2. delete_directories - To delete folders in root path
3. delete_files - To delete files in root path
4. rename_file_folder - To rename files and folders in root path
5. copy_move_file_folder - To cut paste files/folders in root path to destination path
6. copy_move_rename_file_folder - To copy rename and paste file from root location to destination folder
7. zip - To zip files in root path.
8. unzip - To unzip zipped file in root path.

10 arguments totally to be passed to do all the file operation:
1. action - file operations to be performed as stated above in features.
2. root_path - path where the operation is performed
3. folder_file_names - folder or file name to be created, deleted, moved, etc. If multiple give in comma seperated
4. destination_path - path where file/folder has to be copy pasted or cut pasted 
5. new_folder_file_name - folder_file_names will be renamed with new_file_folder_name. 1st file/folder name given in folder_file_names will be renamed with 1st file/folder name given in new_folder_file_name
6. selected_date - Add date or any suffix to new_folder_file_name when copy pasted to destination_path 
7. zip_folder_name - Zip file to be created or unzipped in root folder. e.g. if you want to zip all the files in root_path to test.zip give test.zip here. if you want to unzip test.zip then give test.zip
8. file_type - If you want to zip only certain type of file in root folder i.e. .pdf files give .pdf here
9. password - If zipped folder is password protected
10. output_path - Path where status of the file operation is saved
