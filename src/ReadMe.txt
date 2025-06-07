All the Source files are in python programming developed in Jupyter Notebook

We used various Modules to develop these source code to generate an outputs

1.Pandas
2.Numpy
3.Matplotlib
4.Sklearn
5.Networkx

When you run the code If any error is displayed about module is not found Then you have install that Module by using the following  command this  command should run in command prompt
* pip install pandas etc...
We modified the codes actual codes like, The code should read the input files from the input directory an also the output should store in build folder 
We used the following relative paths like

*INPUT_DIR = "../input": Points to the input folder (one level up from src).
*OUTPUT_DIR = "../build": Points to the build
*Files are accessed using os.path.join(INPUT_DIR, filename)
*Output file is written to ../build/output file

The source code of graph generation in this code we generated only graph but manually we have to keep the india Map that is available in the input folder india.png