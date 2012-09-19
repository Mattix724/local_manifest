Local manifest for building JellyBean from source

<?xml version="1.0" encoding="UTF-8"?>
  <manifest>

    <!-- remove projects -->
    <remove-project name="SlimRoms/hardware_samsung"/>
     
    <!-- local projects -->
    <project name="EpicCM/android_device_samsung_d710" path="device/samsung/d710" revision="jellybean" remote="github" />
    <project name="EpicAOSP/android_kernel_samsung_smdk4210_new" path="kernel/samsung/smdk4210" revision="jellybean" remote="github" />
    <project name="CyanogenMod/android_device_samsung_galaxys2-common" path="device/samsung/galaxys2-common" revision="jellybean" remote="github" />
    <project name="CyanogenMod/android_hardware_samsung" path="hardware/samsung" revision="jellybean" remote="github" />

  </manifest>