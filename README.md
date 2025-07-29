Secure VPN (C++ with Poco)

A lightweight and secure VPN application built in C++ using Poco C++ Libraries. It enables encrypted communication and secure tunneling over public networks.

Features

- End-to-end encrypted data transfer  
- SSL/TLS-based secure sockets  
- TCP tunneling between client & server  
- Certificate-based authentication  
- Cross-platform and lightweight  

 Requirements

- C++17 or later  
- CMake ≥ 3.10  
- Poco Libraries (via vcpkg or manual)  
Install Poco (via vcpkg)


git clone https://github.com/microsoft/vcpkg.git
cd vcpkg
./bootstrap-vcpkg.bat      
vcpkg install poco

Then build an configuration file and Build and run the application using below commands
mkdir build && cd build
cmake ..
cmake --build .
./vpn-app        

