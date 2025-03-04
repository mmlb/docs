---
description: Stop on-screen keyboard from popping up while typing
---

# Disable On-Screen Keyboard



You can disable on-screen keyboard by two methods,

#### From command-line:

  `# lxc-attach -P /var/lib/waydroid/lxc/ -n waydroid --clear-env pm disable com.android.inputmethod.
latin`

#### Going to settings app and selecting Apps & notifications:

![](../.gitbook/assets/132976664-23ded884-6a57-41b0-9033-6d27a887df31.png)

Then select App info:

![](../.gitbook/assets/132976670-3f401d7f-6c17-472e-bba3-40cf9e5a3844.png)

And finally clicking on Android Keyboard \(AOSP\) entry in the app list:

![](../.gitbook/assets/132976694-b17abd88-3807-45ba-8d58-0be1352f0d80.png)

Clicking on Disable button and confirming in a pop-up dialog will disable on-screen android keyboard from appearing when trying to type.

![](../.gitbook/assets/132976739-83a33469-92d4-422c-a340-30f4275df510.png)

This will not disable your physical keyboard and you will be able to use it to type.

