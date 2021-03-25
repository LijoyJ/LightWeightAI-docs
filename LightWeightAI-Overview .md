# LightWeightAI<a name="EN-US_TOPIC_0000001064024128"></a>

-   [Introduction](#section1270210396435)
-   [Technical Architecture](#section2502124574318)
-   [Technical Features](#section12212842173518)
-   [LightWeightAI Compiler Framework](#section21031470109)
-   [Getting Started](#section44681652104210)
-   [LightWeightAI Compiler Framework Code Downloading](#section39011923144212)
-   [How to Participate](#section19611528174215)
-   [License Agreement](#section1245517472115)
-   [Contact Info](#section61728335424)

## Introduction<a name="section1270210396435"></a>
LightWeightAI is an open-source project launched by the OpenHarmony.<br />
LightWeightAI platform build an ultra-lightweightAI subsystem based on the community for different device types to implement device-side capabilities of lightweight harmony
       

## Technical Architecture<a name="section2502124574318"></a>

-   **Runtime**

Loads and runs the graph

-   **Kernel**

Basic mathematical arithmetic operations and operators.It can also be connected to third-party acceleration libraries.<br />
Default operator supports optimization.<br />

-   **Memory**

Memory management module

-   **Loader**

Loads Models in Flatbuffer and JSON formats

-   **Third-party library**

Third party operator library or acceleration library.such as CMSIS-NN and ACL

-   **Hardware backend**

The upstream community supports architectures such as CPU(x86/ARM),GPU,DSP,FPGA,NPU and linux platforms



## Technical Features<a name="section12212842173518"></a>
Based on the TVM upstream community solution,compatible with all popular frontend frameworks,covering customization from L0 to L2

## LightWeightAI Compiler Framework<a name="section21031470109"></a>
LightWeight AI compiler framework will build an accessible, extensible framework that optimizes current and emerging machine learning models for any hardware platform.LightWeightAI compiler framework use TVM codegen solution for this.

-   TVM codegen framework**

A unified framework for  accelerator vendors to integrate their codegens.<br />
TVM codegen framework does the following step
-   Graph anotation
-   Grapn transformation
-   Code generation
-   Runtime<br />
You can find more details in [TVM codegen document](https://tvm.apache.org/docs/dev/relay_bring_your_own_codegen.html?highlight=codegen)

## Getting Started<a name="section44681652104210"></a>



## LightWeightAI Compiler Framework Code Downloading<a name="section39011923144212"></a>

For details about how to obtain the source code of LightweightAI, see  [Source Code Acquisition](https://gitee.com/openharmony/docs/).

## How to Participate<a name="section19611528174215"></a>


## License Agreement<a name="section1245517472115"></a>

LightWeightAI is an open-source. For details, see the LICENSE in each repository.

## Contact Info<a name="section61728335424"></a>

Website:



Email:



