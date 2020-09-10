# Python_CPP_Bazel_target

# Below step User need to follow in order to execute this bazel target.

1) Install tensorflow 2.2 by using below command through anaconda enviornment.
pip install tensorflow-gpu==2.2

2) Once tensorflow 2.2 installed then copy below paths.
<tensorflow2.2>\include
<tensorflow2.2>\libs

and Past into below path.

<path>/Python_CPP_Bazel_target/thirdParty/tensorflow/

3) open cmd.exe and go to below path.

<path>/Python_CPP_Bazel_target

4) open file(Python_CPP_Bazel_target\main\python_cpp.cc) and modify line number 11 (tensorflow env path with your tensorflow env path) 

std::string tensoflow_env = "C:\\Users\\PRATIK\\anaconda3\\envs\\tensorflow_GPU\\";

5) execute below bazel target.wait for some time to complete bazel target execution.
bazel build //main:python_cpp

6) once bazel target executed succussfully then #"bazel-out" folder will be created inside Python_CPP_Bazel_target folder.
   inside bazel-out folder multiple folder also created so go to below path. 
   <path>\Python_CPP_Bazel_target\bazel-out\x64_windows-fastbuild\bin\main

7) copy sample.py file and past into below path.
  <path>\Python_CPP_Bazel_target\bazel-out\x64_windows-fastbuild\bin\main

8) go to below path and execute "python_cpp.exe"
    <path>\Python_CPP_Bazel_target\bazel-out\x64_windows-fastbuild\bin\main




