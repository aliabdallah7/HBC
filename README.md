<p><a href="https://www.asu.edu.eg/"><img align="right" src="https://ums.asu.edu.eg/images/logo.png" width="100" /></a></p>
<div align=left>
<h1>
  HPC 'Labs & practical Exams' Solutions
</h1>
  <h5>
    "High Performance Computing" course at FCIS - ASU
</div>
<br>
<br>

### How to run the MPI project
- In the folder of the project go to `Debug` folder you can see now this file `theNameOfTheProject.exe`. Run the cmd there and write the following code :
```bash
mpiexec "nameOfTheProject.exe"
```
### How to run the MPI project on a specefic number of processors
```bash
mpiexec -n 3 "nameOfTheProject.exe"
```
- The `3` is the number of the processors. You can write yours..


## 📌 Note :
- This repo is for educational purposes only and to provide my colleagues with more examples and exercises on the practical part of the HPC course
