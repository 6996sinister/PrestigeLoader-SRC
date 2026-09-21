# Prestige Loader Source

Prestige Loader source codebase for Visual Studio 2022.

## Requirements

Before opening or building the project, ensure you have the following installed:

* **Visual Studio 2022** (Community, Professional, or Enterprise)
* **Desktop development with C++** workload installed via Visual Studio Installer
* **v143 Build Tools** (included with the C++ workload)

## Getting Started

1. Double-click and open the solution file (`.sln`) in Visual Studio 2022.
2. Select your build configuration (`Debug` / `Release` and `x64`).
3. Build or run the project directly from Visual Studio.

## Project Structure

* `src/core/` — Main application logic & configuration
* `src/inject/` — Process injection engine & DLL mappers
* `src/jni/` — JNI bridge & JVM attachment hooks
* `src/gui/` — User interface & rendering components
* `src/auth/` — Authentication & license validation
* `src/security/` — Security, anti-debugging, HWID, and VM detection
* `src/net/` — HTTP client & network communications
* `src/crypto/` — Cryptographic helpers & string encryption
* `src/utils/` — Memory utilities & pattern scanner
