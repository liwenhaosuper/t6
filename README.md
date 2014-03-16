T6
===

T6: An operating system for TrustZone based Trusted Execution Environment(TEE) in ARM-based systems
===

T6 is an open source operating system for Trusted Execution Environment(TEE)  in mobile devices using  ARM hardware security extension: TrustZone, which supports legacy operating systems(Android, Linux, etc.) to run simultaneously and provides a strong security property for the legacy operating systems. The design goal of T6 includes:  small code base, secure boot and user interaction, multitasks, fault isolation,  etc.  We named it T6 because the kernel design follows the design art of XV6. 

Features of T6
===

Feature | T6 
----|----
TrustZone Extensions | Provide general API
Rich legacy OS | Support Android, and other Unix like OS
TEE API | support Global Platform TEE API
Crypto API	| PolarSSL and hardware crypto
POSIX API	| Partial of libC
Task isolation	| Kernel-User mode and address isolation
Multitask	| Support
Dynamic third party trustlet loading	| Support
Secure network connection	| Yes
Secure User Input	| Yes
Secure Display	| Yes
Code base( code size)	| About 6K LOC
Supported development board	| Samsung Exynos4,Samsung Exynos5,Versatile Express,ARM Fast Models
Virtualization	| In progress
Secure Boot	| In progress

Source code of T6
===
The source code is available in http://www.liwenhaosuper.com/t6/ 
