
# Android Architecture Detailed Overview

### 1. Linux Kernel

**Function:** Manages core system services like security, memory management, process management, network stack, and driver model.

**Components:**
- **Drivers:** Device drivers (e.g., Camera, Wi-Fi, Bluetooth).
- **Security:** SELinux (Security-Enhanced Linux).

  

### 2. Hardware Abstraction Layer (HAL)

**Function:** Acts as an interface between hardware and Android framework.

**Components:**
- **Modules:** Separate modules for each type of hardware component.



### 3. Android Runtime (ART)

**Function:** Executes and manages applications.

**Components:**
- **ART:** Ahead-of-time (AOT) and just-in-time (JIT) compilation.
- **Core Libraries:** Java core libraries.



### 4. Native C/C++ Libraries

**Function:** Provide functionalities that are not available in the Java APIs.

**Components:**
- **Libraries:** libc, libm, OpenGL, WebKit, etc.



### 5. Java API Framework

**Function:** Exposes the Android OS features to the application layer.

**Components:**
- **Managers:** Activity Manager, Window Manager, Package Manager, etc.
- **Content Providers:** For accessing shared data.



### 6. System Apps

**Function:** Provide basic functionalities for phone operations.

**Components:**
- **Default Apps:** Phone, Contacts, Email, etc.


