#### THIS REPOSITORY IS NOT CURRENTLY IN USE.

# Submitting a device

Congratulations! After weeks (months?) of hard work, LineageOS is running well on your device!
If you're interested in adding your device to LineageOS' roster of officially supported devices, we
ask that you meet some important prerequisites and then get in touch with our developer relations team.

## Prerequisites

### Device

Make sure your device meets the the requirements in the [charter](https://github.com/LineageOS/charter/blob/master/device-support-requirements.md).

### Maintainer

Make sure **you** meet the following requirements:

* **Continued support** - Ask yourself: *"Do I want to provide continuous support?"* - LineageOS is *not* a "submit it and forget it" home.
You need to be willing to continue maintaining the device by fixing bugs, applying security updates and eventually improving performance.

## Submitting your device

Create an issue in this repository with the provided issue template.

Please be patient once you've created your issue. It takes time to review your source code and vendor blobs.
If changes are deemed necessary, you'll receive notice and suggestions for improvement. It will be up
to you to implement the changes before resubmitting your work for approval. Keep in mind that not all
device port requests are accepted. Developer relations will do their best to inform you of the rationale for their decision, though.

## Making your device official

Once you have successfully submitted your device, you will be given access to our internal tools (e.g. team chat, cve tracker, ...) to help maintain your device and coordinate development of LineageOS. You only need to worry about these steps once you've been given access to them."

The following steps are necessary to finally make your device an official one:

* Patch it: Make sure the kernel is patched against all applicable [CVEs](https://cve.lineageos.org).
* Prepare all the info: [Add your device to the wiki](https://wiki.lineageos.org/addingdevice-howto.html).
* Make it build: Create a patch for the `hudson` project on our GitHub org and add your device to the `lineage_build_targets` file.
