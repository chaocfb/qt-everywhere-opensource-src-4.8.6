#############################################################################
# Makefile for building: libqgif.so
# Generated by qmake (2.01a) (Qt 4.8.6) on: Tue Jun 3 11:44:12 2014
# Project:  gif.pro
# Template: lib
# Command: /root/qt-everywhere-opensource-src-4.8.6/bin/qmake -spec ../../../../mkspecs/linux-g++-64 -o Makefile gif.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQT_NO_DEBUG -DQT_PLUGIN -DQT_GUI_LIB -DQT_CORE_LIB -DQT_HAVE_MMX -DQT_HAVE_3DNOW -DQT_HAVE_SSE -DQT_HAVE_MMXEXT -DQT_HAVE_SSE2 -DQT_HAVE_SSE3 -DQT_HAVE_SSSE3 -DQT_HAVE_SSE4_1 -DQT_HAVE_SSE4_2 -DQT_HAVE_AVX -D_LARGEFILE64_SOURCE -D_LARGEFILE_SOURCE -DQT_SHARED
CFLAGS        = -m64 -pipe -O2 -fvisibility=hidden -D_REENTRANT -Wall -W -fPIC $(DEFINES)
CXXFLAGS      = -m64 -pipe -O2 -fvisibility=hidden -fvisibility-inlines-hidden -D_REENTRANT -Wall -W -fPIC $(DEFINES)
INCPATH       = -I../../../../mkspecs/linux-g++-64 -I. -I../../../../include/QtCore -I../../../../include/QtGui -I../../../../include -I../../../gui/image -I.moc/release-shared
LINK          = g++
LFLAGS        = -Wl,-rpath-link,/root/qt-everywhere-opensource-src-4.8.6/lib -m64 -Wl,-O1 -Wl,-rpath,/usr/local/Trolltech/Qt-4.8.6/lib -Wl,-rpath,/usr/local/Trolltech/Qt-4.8.6/lib -shared
LIBS          = $(SUBLIBS)  -L/root/qt-everywhere-opensource-src-4.8.6/lib -lQtGui -L/root/qt-everywhere-opensource-src-4.8.6/lib -L/usr/X11R6/lib64 -lQtCore -lpthread 
AR            = ar cqs
RANLIB        = 
QMAKE         = /root/qt-everywhere-opensource-src-4.8.6/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = $(COPY)
COPY_DIR      = $(COPY) -r
STRIP         = strip
INSTALL_FILE  = install -m 644 -p
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = install -m 755 -p
DEL_FILE      = rm -f
SYMLINK       = ln -f -s
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p

####### Output directory

OBJECTS_DIR   = .obj/release-shared/

####### Files

SOURCES       = ../../../gui/image/qgifhandler.cpp \
		main.cpp 
OBJECTS       = .obj/release-shared/qgifhandler.o \
		.obj/release-shared/main.o
DIST          = ../../../../mkspecs/common/unix.conf \
		../../../../mkspecs/common/linux.conf \
		../../../../mkspecs/common/gcc-base.conf \
		../../../../mkspecs/common/gcc-base-unix.conf \
		../../../../mkspecs/common/g++-base.conf \
		../../../../mkspecs/common/g++-unix.conf \
		../../../../mkspecs/features/exclusive_builds.prf \
		../../../../mkspecs/features/default_pre.prf \
		../../../../.qmake.cache \
		../../../../mkspecs/qconfig.pri \
		../../../../mkspecs/modules/qt_webkit_version.pri \
		../../../../mkspecs/features/qt_functions.prf \
		../../../../mkspecs/features/qt_config.prf \
		../../../qt_targets.pri \
		../../qpluginbase.pri \
		../../../gui/image/qgifhandler.pri \
		../../../../mkspecs/features/release.prf \
		../../../../mkspecs/features/default_post.prf \
		../../../../mkspecs/features/unix/hide_symbols.prf \
		../../../../mkspecs/features/qt.prf \
		../../../../mkspecs/features/unix/thread.prf \
		../../../../mkspecs/features/moc.prf \
		../../../../mkspecs/features/unix/dylib.prf \
		../../../../mkspecs/features/unix/largefile.prf \
		../../../../mkspecs/features/shared.prf \
		../../../../mkspecs/features/dll.prf \
		../../../../mkspecs/features/unix/gdb_dwarf_index.prf \
		../../../../mkspecs/features/warn_on.prf \
		../../../../mkspecs/features/resources.prf \
		../../../../mkspecs/features/uic.prf \
		../../../../mkspecs/features/yacc.prf \
		../../../../mkspecs/features/lex.prf \
		gif.pro
QMAKE_TARGET  = qgif
DESTDIR       = ../../../../plugins/imageformats/
TARGET        = libqgif.so
TARGETD       = libqgif.so

first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile  ../../../../plugins/imageformats/$(TARGET)

../../../../plugins/imageformats/$(TARGET):  $(OBJECTS) $(SUBLIBS) $(OBJCOMP)  
	@$(CHK_DIR_EXISTS) ../../../../plugins/imageformats/ || $(MKDIR) ../../../../plugins/imageformats/ 
	-$(DEL_FILE) $(TARGET)
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(LIBS) $(OBJCOMP)
	-$(MOVE) $(TARGET) ../../../../plugins/imageformats/



Makefile: gif.pro ../../../../.qmake.cache ../../../../mkspecs/linux-g++-64/qmake.conf ../../../../mkspecs/common/unix.conf \
		../../../../mkspecs/common/linux.conf \
		../../../../mkspecs/common/gcc-base.conf \
		../../../../mkspecs/common/gcc-base-unix.conf \
		../../../../mkspecs/common/g++-base.conf \
		../../../../mkspecs/common/g++-unix.conf \
		../../../../mkspecs/features/exclusive_builds.prf \
		../../../../mkspecs/features/default_pre.prf \
		../../../../.qmake.cache \
		../../../../mkspecs/qconfig.pri \
		../../../../mkspecs/modules/qt_webkit_version.pri \
		../../../../mkspecs/features/qt_functions.prf \
		../../../../mkspecs/features/qt_config.prf \
		../../../qt_targets.pri \
		../../qpluginbase.pri \
		../../../gui/image/qgifhandler.pri \
		../../../../mkspecs/features/release.prf \
		../../../../mkspecs/features/default_post.prf \
		../../../../mkspecs/features/unix/hide_symbols.prf \
		../../../../mkspecs/features/qt.prf \
		../../../../mkspecs/features/unix/thread.prf \
		../../../../mkspecs/features/moc.prf \
		../../../../mkspecs/features/unix/dylib.prf \
		../../../../mkspecs/features/unix/largefile.prf \
		../../../../mkspecs/features/shared.prf \
		../../../../mkspecs/features/dll.prf \
		../../../../mkspecs/features/unix/gdb_dwarf_index.prf \
		../../../../mkspecs/features/warn_on.prf \
		../../../../mkspecs/features/resources.prf \
		../../../../mkspecs/features/uic.prf \
		../../../../mkspecs/features/yacc.prf \
		../../../../mkspecs/features/lex.prf \
		/root/qt-everywhere-opensource-src-4.8.6/lib/libQtGui.prl \
		/root/qt-everywhere-opensource-src-4.8.6/lib/libQtCore.prl
	$(QMAKE) -spec ../../../../mkspecs/linux-g++-64 -o Makefile gif.pro
../../../../mkspecs/common/unix.conf:
../../../../mkspecs/common/linux.conf:
../../../../mkspecs/common/gcc-base.conf:
../../../../mkspecs/common/gcc-base-unix.conf:
../../../../mkspecs/common/g++-base.conf:
../../../../mkspecs/common/g++-unix.conf:
../../../../mkspecs/features/exclusive_builds.prf:
../../../../mkspecs/features/default_pre.prf:
../../../../.qmake.cache:
../../../../mkspecs/qconfig.pri:
../../../../mkspecs/modules/qt_webkit_version.pri:
../../../../mkspecs/features/qt_functions.prf:
../../../../mkspecs/features/qt_config.prf:
../../../qt_targets.pri:
../../qpluginbase.pri:
../../../gui/image/qgifhandler.pri:
../../../../mkspecs/features/release.prf:
../../../../mkspecs/features/default_post.prf:
../../../../mkspecs/features/unix/hide_symbols.prf:
../../../../mkspecs/features/qt.prf:
../../../../mkspecs/features/unix/thread.prf:
../../../../mkspecs/features/moc.prf:
../../../../mkspecs/features/unix/dylib.prf:
../../../../mkspecs/features/unix/largefile.prf:
../../../../mkspecs/features/shared.prf:
../../../../mkspecs/features/dll.prf:
../../../../mkspecs/features/unix/gdb_dwarf_index.prf:
../../../../mkspecs/features/warn_on.prf:
../../../../mkspecs/features/resources.prf:
../../../../mkspecs/features/uic.prf:
../../../../mkspecs/features/yacc.prf:
../../../../mkspecs/features/lex.prf:
/root/qt-everywhere-opensource-src-4.8.6/lib/libQtGui.prl:
/root/qt-everywhere-opensource-src-4.8.6/lib/libQtCore.prl:
qmake:  FORCE
	@$(QMAKE) -spec ../../../../mkspecs/linux-g++-64 -o Makefile gif.pro

dist: 
	@$(CHK_DIR_EXISTS) .obj/release-shared/qgif4.8.6 || $(MKDIR) .obj/release-shared/qgif4.8.6 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) .obj/release-shared/qgif4.8.6/ && $(COPY_FILE) --parents ../../../gui/image/qgifhandler_p.h .obj/release-shared/qgif4.8.6/ && $(COPY_FILE) --parents ../../../gui/image/qgifhandler.cpp main.cpp .obj/release-shared/qgif4.8.6/ && (cd `dirname .obj/release-shared/qgif4.8.6` && $(TAR) qgif4.8.6.tar qgif4.8.6 && $(COMPRESS) qgif4.8.6.tar) && $(MOVE) `dirname .obj/release-shared/qgif4.8.6`/qgif4.8.6.tar.gz . && $(DEL_FILE) -r .obj/release-shared/qgif4.8.6


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


check: first

mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_moc_header_make_all:
compiler_moc_header_clean:
compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: .uic/release-shared/qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) .uic/release-shared/qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: 

####### Compile

.obj/release-shared/qgifhandler.o: ../../../gui/image/qgifhandler.cpp ../../../gui/image/qgifhandler_p.h \
		../../../../include/QtGui/qimageiohandler.h \
		../../../gui/image/qimageiohandler.h \
		../../../../include/QtCore/qplugin.h \
		../../../corelib/plugin/qplugin.h \
		../../../../include/QtCore/qobject.h \
		../../../corelib/kernel/qobject.h \
		../../../../include/QtCore/qobjectdefs.h \
		../../../corelib/kernel/qobjectdefs.h \
		../../../../include/QtCore/qnamespace.h \
		../../../corelib/global/qnamespace.h \
		../../../../include/QtCore/qglobal.h \
		../../../corelib/global/qglobal.h \
		../../../../include/QtCore/qconfig.h \
		../../../corelib/global/qconfig.h \
		../../../../include/QtCore/qfeatures.h \
		../../../corelib/global/qfeatures.h \
		../../../../include/QtCore/qstring.h \
		../../../corelib/tools/qstring.h \
		../../../../include/QtCore/qchar.h \
		../../../corelib/tools/qchar.h \
		../../../../include/QtCore/qbytearray.h \
		../../../corelib/tools/qbytearray.h \
		../../../../include/QtCore/qatomic.h \
		../../../corelib/thread/qatomic.h \
		../../../../include/QtCore/qbasicatomic.h \
		../../../corelib/thread/qbasicatomic.h \
		../../../../include/QtCore/qatomic_bootstrap.h \
		../../../corelib/arch/qatomic_bootstrap.h \
		../../../../include/QtCore/qatomic_arch.h \
		../../../corelib/arch/qatomic_arch.h \
		../../../../include/QtCore/qatomic_integrity.h \
		../../../corelib/arch/qatomic_integrity.h \
		../../../../include/QtCore/qatomic_vxworks.h \
		../../../corelib/arch/qatomic_vxworks.h \
		../../../../include/QtCore/qatomic_powerpc.h \
		../../../corelib/arch/qatomic_powerpc.h \
		../../../../include/QtCore/qatomic_alpha.h \
		../../../corelib/arch/qatomic_alpha.h \
		../../../../include/QtCore/qatomic_arm.h \
		../../../corelib/arch/qatomic_arm.h \
		../../../../include/QtCore/qatomic_armv7.h \
		../../../corelib/arch/qatomic_armv7.h \
		../../../../include/QtCore/qatomic_armv6.h \
		../../../corelib/arch/qatomic_armv6.h \
		../../../../include/QtCore/qatomic_armv5.h \
		../../../corelib/arch/qatomic_armv5.h \
		../../../../include/QtCore/qatomic_avr32.h \
		../../../corelib/arch/qatomic_avr32.h \
		../../../../include/QtCore/qatomic_bfin.h \
		../../../corelib/arch/qatomic_bfin.h \
		../../../../include/QtCore/qatomic_generic.h \
		../../../corelib/arch/qatomic_generic.h \
		../../../../include/QtCore/qatomic_i386.h \
		../../../corelib/arch/qatomic_i386.h \
		../../../../include/QtCore/qatomic_ia64.h \
		../../../corelib/arch/qatomic_ia64.h \
		../../../../include/QtCore/qatomic_m68k.h \
		../../../corelib/arch/qatomic_m68k.h \
		../../../../include/QtCore/qatomic_macosx.h \
		../../../corelib/arch/qatomic_macosx.h \
		../../../../include/QtCore/qatomic_x86_64.h \
		../../../corelib/arch/qatomic_x86_64.h \
		../../../../include/QtCore/qatomic_mips.h \
		../../../corelib/arch/qatomic_mips.h \
		../../../../include/QtCore/qatomic_parisc.h \
		../../../corelib/arch/qatomic_parisc.h \
		../../../../include/QtCore/qatomic_s390.h \
		../../../corelib/arch/qatomic_s390.h \
		../../../../include/QtCore/qatomic_sparc.h \
		../../../corelib/arch/qatomic_sparc.h \
		../../../../include/QtCore/qatomic_windows.h \
		../../../corelib/arch/qatomic_windows.h \
		../../../../include/QtCore/qatomic_windowsce.h \
		../../../corelib/arch/qatomic_windowsce.h \
		../../../../include/QtCore/qatomic_symbian.h \
		../../../corelib/arch/qatomic_symbian.h \
		../../../../include/QtCore/qatomic_sh.h \
		../../../corelib/arch/qatomic_sh.h \
		../../../../include/QtCore/qatomic_sh4a.h \
		../../../corelib/arch/qatomic_sh4a.h \
		../../../../include/Qt3Support/q3cstring.h \
		../../../qt3support/tools/q3cstring.h \
		../../../../include/QtCore/qstringbuilder.h \
		../../../corelib/tools/qstringbuilder.h \
		../../../../include/QtCore/qmap.h \
		../../../corelib/tools/qmap.h \
		../../../../include/QtCore/qiterator.h \
		../../../corelib/tools/qiterator.h \
		../../../../include/QtCore/qlist.h \
		../../../corelib/tools/qlist.h \
		../../../../include/QtCore/qalgorithms.h \
		../../../corelib/tools/qalgorithms.h \
		../../../../include/QtCore/qcoreevent.h \
		../../../corelib/kernel/qcoreevent.h \
		../../../../include/QtCore/qscopedpointer.h \
		../../../corelib/tools/qscopedpointer.h \
		../../../../include/QtCore/qpointer.h \
		../../../corelib/kernel/qpointer.h \
		../../../../include/QtCore/qfactoryinterface.h \
		../../../corelib/plugin/qfactoryinterface.h \
		../../../../include/QtCore/qstringlist.h \
		../../../corelib/tools/qstringlist.h \
		../../../../include/QtCore/qdatastream.h \
		../../../corelib/io/qdatastream.h \
		../../../../include/QtCore/qiodevice.h \
		../../../corelib/io/qiodevice.h \
		../../../../include/QtCore/qregexp.h \
		../../../corelib/tools/qregexp.h \
		../../../../include/QtCore/qstringmatcher.h \
		../../../corelib/tools/qstringmatcher.h \
		../../../../include/Qt3Support/q3valuelist.h \
		../../../qt3support/tools/q3valuelist.h \
		../../../../include/QtCore/qlinkedlist.h \
		../../../corelib/tools/qlinkedlist.h \
		../../../../include/QtGui/qimage.h \
		../../../gui/image/qimage.h \
		../../../../include/QtGui/qtransform.h \
		../../../gui/painting/qtransform.h \
		../../../../include/QtGui/qmatrix.h \
		../../../gui/painting/qmatrix.h \
		../../../../include/QtGui/qpolygon.h \
		../../../gui/painting/qpolygon.h \
		../../../../include/QtCore/qvector.h \
		../../../corelib/tools/qvector.h \
		../../../../include/QtCore/QPointF \
		../../../../include/QtCore/qpoint.h \
		../../../corelib/tools/qpoint.h \
		../../../../include/QtCore/QPoint \
		../../../../include/QtCore/qrect.h \
		../../../corelib/tools/qrect.h \
		../../../../include/QtCore/qsize.h \
		../../../corelib/tools/qsize.h \
		../../../../include/QtGui/qregion.h \
		../../../gui/painting/qregion.h \
		../../../../include/QtGui/qwindowdefs.h \
		../../../gui/kernel/qwindowdefs.h \
		../../../../include/QtGui/qmacdefines_mac.h \
		../../../gui/kernel/qmacdefines_mac.h \
		../../../../include/QtGui/qwindowdefs_win.h \
		../../../gui/kernel/qwindowdefs_win.h \
		../../../../include/QtCore/qline.h \
		../../../corelib/tools/qline.h \
		../../../../include/QtGui/qwmatrix.h \
		../../../gui/painting/qwmatrix.h \
		../../../../include/QtGui/qpainterpath.h \
		../../../gui/painting/qpainterpath.h \
		../../../../include/QtGui/qpaintdevice.h \
		../../../gui/painting/qpaintdevice.h \
		../../../../include/QtGui/qrgb.h \
		../../../gui/painting/qrgb.h \
		../../../../include/QtCore/qvariant.h \
		../../../corelib/kernel/qvariant.h \
		../../../../include/QtCore/qmetatype.h \
		../../../corelib/kernel/qmetatype.h \
		../../../../include/QtCore/qhash.h \
		../../../corelib/tools/qhash.h \
		../../../../include/QtCore/qpair.h \
		../../../corelib/tools/qpair.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/qgifhandler.o ../../../gui/image/qgifhandler.cpp

.obj/release-shared/main.o: main.cpp ../../../../include/QtGui/qimageiohandler.h \
		../../../gui/image/qimageiohandler.h \
		../../../../include/QtCore/qplugin.h \
		../../../corelib/plugin/qplugin.h \
		../../../../include/QtCore/qobject.h \
		../../../corelib/kernel/qobject.h \
		../../../../include/QtCore/qobjectdefs.h \
		../../../corelib/kernel/qobjectdefs.h \
		../../../../include/QtCore/qnamespace.h \
		../../../corelib/global/qnamespace.h \
		../../../../include/QtCore/qglobal.h \
		../../../corelib/global/qglobal.h \
		../../../../include/QtCore/qconfig.h \
		../../../corelib/global/qconfig.h \
		../../../../include/QtCore/qfeatures.h \
		../../../corelib/global/qfeatures.h \
		../../../../include/QtCore/qstring.h \
		../../../corelib/tools/qstring.h \
		../../../../include/QtCore/qchar.h \
		../../../corelib/tools/qchar.h \
		../../../../include/QtCore/qbytearray.h \
		../../../corelib/tools/qbytearray.h \
		../../../../include/QtCore/qatomic.h \
		../../../corelib/thread/qatomic.h \
		../../../../include/QtCore/qbasicatomic.h \
		../../../corelib/thread/qbasicatomic.h \
		../../../../include/QtCore/qatomic_bootstrap.h \
		../../../corelib/arch/qatomic_bootstrap.h \
		../../../../include/QtCore/qatomic_arch.h \
		../../../corelib/arch/qatomic_arch.h \
		../../../../include/QtCore/qatomic_integrity.h \
		../../../corelib/arch/qatomic_integrity.h \
		../../../../include/QtCore/qatomic_vxworks.h \
		../../../corelib/arch/qatomic_vxworks.h \
		../../../../include/QtCore/qatomic_powerpc.h \
		../../../corelib/arch/qatomic_powerpc.h \
		../../../../include/QtCore/qatomic_alpha.h \
		../../../corelib/arch/qatomic_alpha.h \
		../../../../include/QtCore/qatomic_arm.h \
		../../../corelib/arch/qatomic_arm.h \
		../../../../include/QtCore/qatomic_armv7.h \
		../../../corelib/arch/qatomic_armv7.h \
		../../../../include/QtCore/qatomic_armv6.h \
		../../../corelib/arch/qatomic_armv6.h \
		../../../../include/QtCore/qatomic_armv5.h \
		../../../corelib/arch/qatomic_armv5.h \
		../../../../include/QtCore/qatomic_avr32.h \
		../../../corelib/arch/qatomic_avr32.h \
		../../../../include/QtCore/qatomic_bfin.h \
		../../../corelib/arch/qatomic_bfin.h \
		../../../../include/QtCore/qatomic_generic.h \
		../../../corelib/arch/qatomic_generic.h \
		../../../../include/QtCore/qatomic_i386.h \
		../../../corelib/arch/qatomic_i386.h \
		../../../../include/QtCore/qatomic_ia64.h \
		../../../corelib/arch/qatomic_ia64.h \
		../../../../include/QtCore/qatomic_m68k.h \
		../../../corelib/arch/qatomic_m68k.h \
		../../../../include/QtCore/qatomic_macosx.h \
		../../../corelib/arch/qatomic_macosx.h \
		../../../../include/QtCore/qatomic_x86_64.h \
		../../../corelib/arch/qatomic_x86_64.h \
		../../../../include/QtCore/qatomic_mips.h \
		../../../corelib/arch/qatomic_mips.h \
		../../../../include/QtCore/qatomic_parisc.h \
		../../../corelib/arch/qatomic_parisc.h \
		../../../../include/QtCore/qatomic_s390.h \
		../../../corelib/arch/qatomic_s390.h \
		../../../../include/QtCore/qatomic_sparc.h \
		../../../corelib/arch/qatomic_sparc.h \
		../../../../include/QtCore/qatomic_windows.h \
		../../../corelib/arch/qatomic_windows.h \
		../../../../include/QtCore/qatomic_windowsce.h \
		../../../corelib/arch/qatomic_windowsce.h \
		../../../../include/QtCore/qatomic_symbian.h \
		../../../corelib/arch/qatomic_symbian.h \
		../../../../include/QtCore/qatomic_sh.h \
		../../../corelib/arch/qatomic_sh.h \
		../../../../include/QtCore/qatomic_sh4a.h \
		../../../corelib/arch/qatomic_sh4a.h \
		../../../../include/Qt3Support/q3cstring.h \
		../../../qt3support/tools/q3cstring.h \
		../../../../include/QtCore/qstringbuilder.h \
		../../../corelib/tools/qstringbuilder.h \
		../../../../include/QtCore/qmap.h \
		../../../corelib/tools/qmap.h \
		../../../../include/QtCore/qiterator.h \
		../../../corelib/tools/qiterator.h \
		../../../../include/QtCore/qlist.h \
		../../../corelib/tools/qlist.h \
		../../../../include/QtCore/qalgorithms.h \
		../../../corelib/tools/qalgorithms.h \
		../../../../include/QtCore/qcoreevent.h \
		../../../corelib/kernel/qcoreevent.h \
		../../../../include/QtCore/qscopedpointer.h \
		../../../corelib/tools/qscopedpointer.h \
		../../../../include/QtCore/qpointer.h \
		../../../corelib/kernel/qpointer.h \
		../../../../include/QtCore/qfactoryinterface.h \
		../../../corelib/plugin/qfactoryinterface.h \
		../../../../include/QtCore/qstringlist.h \
		../../../corelib/tools/qstringlist.h \
		../../../../include/QtCore/qdatastream.h \
		../../../corelib/io/qdatastream.h \
		../../../../include/QtCore/qiodevice.h \
		../../../corelib/io/qiodevice.h \
		../../../../include/QtCore/qregexp.h \
		../../../corelib/tools/qregexp.h \
		../../../../include/QtCore/qstringmatcher.h \
		../../../corelib/tools/qstringmatcher.h \
		../../../../include/Qt3Support/q3valuelist.h \
		../../../qt3support/tools/q3valuelist.h \
		../../../../include/QtCore/qlinkedlist.h \
		../../../corelib/tools/qlinkedlist.h \
		../../../gui/image/qgifhandler_p.h \
		../../../../include/QtGui/qimage.h \
		../../../gui/image/qimage.h \
		../../../../include/QtGui/qtransform.h \
		../../../gui/painting/qtransform.h \
		../../../../include/QtGui/qmatrix.h \
		../../../gui/painting/qmatrix.h \
		../../../../include/QtGui/qpolygon.h \
		../../../gui/painting/qpolygon.h \
		../../../../include/QtCore/qvector.h \
		../../../corelib/tools/qvector.h \
		../../../../include/QtCore/QPointF \
		../../../../include/QtCore/qpoint.h \
		../../../corelib/tools/qpoint.h \
		../../../../include/QtCore/QPoint \
		../../../../include/QtCore/qrect.h \
		../../../corelib/tools/qrect.h \
		../../../../include/QtCore/qsize.h \
		../../../corelib/tools/qsize.h \
		../../../../include/QtGui/qregion.h \
		../../../gui/painting/qregion.h \
		../../../../include/QtGui/qwindowdefs.h \
		../../../gui/kernel/qwindowdefs.h \
		../../../../include/QtGui/qmacdefines_mac.h \
		../../../gui/kernel/qmacdefines_mac.h \
		../../../../include/QtGui/qwindowdefs_win.h \
		../../../gui/kernel/qwindowdefs_win.h \
		../../../../include/QtCore/qline.h \
		../../../corelib/tools/qline.h \
		../../../../include/QtGui/qwmatrix.h \
		../../../gui/painting/qwmatrix.h \
		../../../../include/QtGui/qpainterpath.h \
		../../../gui/painting/qpainterpath.h \
		../../../../include/QtGui/qpaintdevice.h \
		../../../gui/painting/qpaintdevice.h \
		../../../../include/QtGui/qrgb.h \
		../../../gui/painting/qrgb.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/main.o main.cpp

####### Install

install_target: first FORCE
	@$(CHK_DIR_EXISTS) $(INSTALL_ROOT)/usr/local/Trolltech/Qt-4.8.6/plugins/imageformats/ || $(MKDIR) $(INSTALL_ROOT)/usr/local/Trolltech/Qt-4.8.6/plugins/imageformats/ 
	-$(INSTALL_PROGRAM) "../../../../plugins/imageformats/$(TARGET)" "$(INSTALL_ROOT)/usr/local/Trolltech/Qt-4.8.6/plugins/imageformats/$(TARGET)"
	-$(STRIP) --strip-unneeded "$(INSTALL_ROOT)/usr/local/Trolltech/Qt-4.8.6/plugins/imageformats/$(TARGET)"

uninstall_target:  FORCE
	-$(DEL_FILE) "$(INSTALL_ROOT)/usr/local/Trolltech/Qt-4.8.6/plugins/imageformats/$(TARGET)"
	-$(DEL_DIR) $(INSTALL_ROOT)/usr/local/Trolltech/Qt-4.8.6/plugins/imageformats/ 


install:  install_target  FORCE

uninstall: uninstall_target   FORCE

FORCE:

