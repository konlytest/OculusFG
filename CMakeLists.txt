include(FlightGearComponent)

set(SOURCES
	CameraGroup.cxx
	FGEventHandler.cxx
	WindowBuilder.cxx
	WindowSystemAdapter.cxx
	fg_os_osgviewer.cxx
	fgviewer.cxx
	renderer.cxx
	renderingpipeline.cxx
	splash.cxx
	viewer.cxx
	viewmgr.cxx
	oculusviewer.cpp
	oculusdevice.cpp
	oculuseventhandler.cpp
	oculusupdateslavecallback.cpp
	)

set(HEADERS
	CameraGroup.hxx
	FGEventHandler.hxx
	WindowBuilder.hxx
	WindowSystemAdapter.hxx
	fgviewer.hxx
	renderer.hxx
	renderingpipeline.hxx
	splash.hxx
	viewer.hxx
	viewmgr.hxx
	oculusviewer.h
	oculusdevice.h
	oculuseventhandler.h
	oculusupdateslavecallback.h
	)

flightgear_component(Viewer "${SOURCES}" "${HEADERS}")
