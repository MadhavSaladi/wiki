{% include templates/device_specific/firmware_update_oneplus_fastbootd.md content="
fastboot flash --slot=all abl abl.img
fastboot flash --slot=all aop aop.img
fastboot flash --slot=all aop aop.img
fastboot flash --slot=all bluetooth bluetooth.img
fastboot flash --slot=all cmnlib64 cmnlib64.img
fastboot flash --slot=all cmnlib cmnlib.img
fastboot flash --slot=all devcfg devcfg.img
fastboot flash --slot=all devcfg devcfg.img
fastboot flash --slot=all dsp dsp.img
fastboot flash --slot=all dsp dsp.img
fastboot flash --slot=all featenabler featenabler.img
fastboot flash --slot=all hyp hyp.img
fastboot flash --slot=all imagefv imagefv.img
fastboot flash --slot=all keymaster keymaster.img
fastboot flash --slot=all logo logo.img
fastboot flash --slot=all mdm_oem_stanvbk mdm_oem_stanvbk.img
fastboot flash --slot=all modem modem.img
fastboot flash --slot=all multiimgoem multiimgoem.img
fastboot flash --slot=all qupfw qupfw.img
fastboot flash --slot=all spunvm spunvm.img
fastboot flash --slot=all storsec storsec.img
fastboot flash --slot=all tz tz.img
fastboot flash --slot=all uefisecapp uefisecapp.img
fastboot flash --slot=all xbl_config xbl_config.img
fastboot flash --slot=all xbl xbl.img
" %}
