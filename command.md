* Find file with a certain name / format

find [folder_path] -name "[file_name]"			e.g., find ./ -name "file.txt"

find [folder_path] -name "[file_format]"		e.g., find ./ -name "*format*"





* find file that contains certain string

grep -l [text_to_find] [files_to_look_in]		e.g., grep -l ""

* find strings recursively

grep -lr [text to find] [files_to_look_in]		e.g., grep -lr "text to find" ./


