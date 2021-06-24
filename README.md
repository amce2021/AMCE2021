    Sequential Sort:

Run amce.exe under /exe

Usage: amce.exe <input_file_path>

<input_file_path> is the path to the input string file. Each string should be on a separate line in the file. amce.exe reads the input file first and output "Done reading" once reading is finished. It then starts sorting and show the time elapsed in microseconds once completed. If the output is required, please enter Y/y when being asked on whether to output to a file. The output is then written to file sorted.txt in the current directory.

    Parallel Sort:

Run amce-para.exe under /exe

Usage: amce-para.exe <input_file_path> <number of threads>

<input_file_path> is the path to the input string file (same as the sequential version). Specifiy the number of threads to use. If it is larger than the maximum hyper-threads the machine supports, it will be cut to that number.
