installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = SoftwareManager PositionerSetup Satfinder \
	SkinSelector SatelliteEquipmentControl Videomode VideoTune Hotplug \
	DefaultServicesScanner DiseqcTester \
	CableScan FastScan OSDPositionSetup OSD3DSetup HdmiCEC VideoClippingSetup \
	VideoEnhancement WirelessLan NetworkWizard BlackHoleApi

if HAVE_LIBVUGLES2
SUBDIRS += AnimationSetup
endif

if HAVE_TEMPFANCONTROL
SUBDIRS += TempFanControl
endif

if DREAMBOX
SUBDIRS += FrontprocessorUpgrade NFIFlash
endif

install_PYTHON =	\
	__init__.py
