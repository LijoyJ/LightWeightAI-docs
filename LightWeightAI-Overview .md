# LightWeightAI<a name="EN-US_TOPIC_0000001064024128"></a>

-   [Introduction](#section1270210396435)
-   [Technical Architecture](#section2502124574318)
-   [Technical Features](#section12212842173518)
-   [Device Types](#section145241459142416)
-   [Getting Started](#section44681652104210)
-   [LightWeightAI Documentation](#section21031470109)
-   [Source Code Downloading](#section39011923144212)
-   [How to Participate](#section19611528174215)
-   [License Agreement](#section1245517472115)
-   [Contact Info](#section61728335424)

## Introduction<a name="section1270210396435"></a>
LightWeightAI is an open-source project launched by the OpenHarmony.
LightWeightAI platform build an ultra-lightweightAI subsystem based on the community for different device types to implement device-side capabilities of lightweight harmony

## Technical Architecture<a name="section2502124574318"></a>

**Runtime**

Loads and runs the graph

**Kernel**

Basic mathematical arithmetic operations and operators.It can also be connected to third-party acceleration libraries.
Default operator supports optimization.
Operator support by different kernel framework.
       - TVM  -> 140
       - TinyTVM custom ops -> 6
       - ACL  -> 123
       - CMSIS-NN  -> 15

**Memory**

Memory management module

**Loader**

Loads Models in Flatbuffer and JSON formats

**Third-party library**

Third party operator library or acceleration library.such as CMSIS-NN and ACL

**Hardware backend**

The upstream community supports architectures such as CPU(x86/ARM),GPU,DSP,FPGA,NPU and linux platforms


## Technical Features<a name="section12212842173518"></a>
Based on the TVM upstream community solution,compatible with all popular frontend frameworks,covering customization from L0 to L2



## Device Types<a name="section145241459142416"></a>

LightWeightAI supports the following device types:

-   **Mini-System Devices \(reference memory ≥ 128 KB\)**

    Such devices are equipped with MCU processors such as ARM Cortex-M and 32-bit RISC-V. Typical products include LinkIoT module devices and smart home sensors.

-   **Small-System Devices \(reference memory ≥ 1 MB\)**

    Such devices are equipped with application processors such as ARM Cortex-A. Typical products include smart home IP cameras, electronic cat eyes, and routers, and smart travel.


-   **Standard-System Devices \(reference memory ≥ 128 MB\)**

    Such devices are equipped with application processors such as ARM Cortex-A.  a diverse range of components and visual displays, for example the type included on a high-end refrigerator.

-   **Large-System Devices \(reference memory ≥ 1 GB\)**

    Such devices are equipped with application processors such as ARM Cortex-A and provide a complete compatible application framework. Typical products include smart TVs and smart watches.


## Getting Started<a name="section44681652104210"></a>



## Source Code Downloading<a name="section39011923144212"></a>

For details about how to obtain the source code of LightweightAI, see  [Source Code Acquisition](https://gitee.com/openharmony/docs/).

## How to Participate<a name="section19611528174215"></a>


## License Agreement<a name="section1245517472115"></a>

LightWeightAI is an open-source. For details, see the LICENSE in each repository.

## Contact Info<a name="section61728335424"></a>

Website:



Email:



