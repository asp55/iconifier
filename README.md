iconifier
=========

NAME
	iconifier -- Utility for creating .icns files from a provided .png file

SYNOPSIS
	iconifier -i input_file [-o output_directory | output_file] 

DESCRIPTION
	iconifier takes a single png (ideally 1024x1024, though not enforced) and creates an iconset which it then converts to a '.icns' file. It is possible to specify the name of the output file by passing the file path as the argument to the -o flag. If -o is not set iconifier will write converted '.icns' file to the same directory as the source file using the same file name with the correct extension for the output type.

OPTIONS
	-i The location of the input file

	-o Overrides the default output file name that iconifier uses to save the final '.icns' file.