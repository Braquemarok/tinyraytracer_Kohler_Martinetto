current result : 
![](raw.githubusercontent.com/Braquemarok/tinyraytracer_Kohler_Martinetto/main/out.jpg)

## compilation
```sh
git clone --recurse-submodules https://github.com/ssloy/tinyraytracer.git
cd tinyraytracer
git checkout homework_assignment
git submodule update --init
mkdir build
cd build
cmake ..  
make
```

