# Dynamsoft Capture Vision Samples for C++ Edition

This repository contains multiple samples that demonstrate how to use the [Dynamsoft Capture Vision](https://www.dynamsoft.com/capture-vision/docs/core/introduction/?lang=cplusplus) C++ Edition.

## System Requirements

### Supported Platforms

**Windows**
- Supported Versions: Windows 8 and higher, or Windows Server 2012 and higher
- Architectures: x64, x86

**Linux**
- Supported Distributions: Ubuntu 18.04+ LTS, Debian 10+, CentOS/RHEL 8+
- Architectures: x64, ARM64
- Dependencies: glibc 2.27 or higher

### Development Environment
- Visual Studio 2012 or higher
- GCC 5.4+ / G++ 5.4+

## Samples

| Sample            | Description |
|---------------|----------------------|
|[`MRZScanner`](Samples/MRZScanner)          | Capture and extract user's information from machine-readable travel documents with Dynamsoft Capture Vision SDK.            |
|[`DriverLicenseScanner`](Samples/DriverLicenseScanner)          | Capture and extract user's information from driver license/ID with Dynamsoft Capture Vision SDK.            |
|[`DocumentScanner`](Samples/DocumentScanner)          | The simplest way to detect and normalize a document from an image and save the result as a new image.            |
|[`GS1AIScanner`](Samples/GS1AIScanner) | Shows how to extract and interpret GS1 Application Identifiers (AIs) from GS1 barcodes. |

## License

The library requires a license to work, you use the API `CLicenseManager::InitLicense` to initialize license key and activate the SDK.

These samples use a free public trial license which require network connection to function. You can request a 30-day free trial license via the <a href="https://www.dynamsoft.com/customer/license/trialLicense?product=dcv&utm_source=github&package=c_cpp" target="_blank">Request a Trial License</a> link which works offline.

## Contact Us

https://www.dynamsoft.com/company/contact/
