SUBDIRS=util xcms xlibi18n xkb

lib_LTLIBRARIES=libX11.la

BUILT_SOURCES=ks_tables.h
CLEANFILES=ks_tables.h ks_tables_h

AM_CFLAGS= \
	-I$(top_srcdir)/include \
	-I$(top_srcdir)/include/X11 \
	-I$(top_builddir)/include \
	-I$(top_builddir)/include/X11 \
	-I$(top_srcdir)/src/xcms \
	-I$(top_srcdir)/src/xkb \
	-I$(top_srcdir)/src/xlibi18n \
	$(X11_CFLAGS) \
	$(BIGREQS_CFLAGS) \
	$(BIGFONT_CFLAGS) \
	$(XDMCP_CFLAGS) \
	-D_BSD_SOURCE -DX11_t -DTRANS_CLIENT \
	$(XMALLOC_ZERO_CFLAGS)

#
# =============================== I18N =============================
#

I18N_LIBS = \
	xlibi18n/libi18n.la

#
# =============================== XCMS =============================
#

XCMS_LIBS = \
	xcms/libxcms.la

#
# =============================== XKB ==============================
#

XKB_LIBS = \
	xkb/libxkb.la

#
# =============================== XLIB =============================
#

libX11_la_SOURCES = \
                  AllCells.c \
                  AllowEv.c \
                  AllPlanes.c \
                  AutoRep.c \
                  Backgnd.c \
                  BdrWidth.c \
                  Bell.c \
                  Border.c \
                  ChAccCon.c \
                  ChActPGb.c \
                  ChClMode.c \
                  ChCmap.c \
                  ChGC.c \
                  ChKeyCon.c \
                  ChkIfEv.c \
                  ChkMaskEv.c \
                  ChkTypEv.c \
                  ChkTypWEv.c \
                  ChkWinEv.c \
                  ChPntCon.c \
                  ChProp.c \
                  ChSaveSet.c \
                  ChWAttrs.c \
                  ChWindow.c \
                  CirWin.c \
                  CirWinDn.c \
                  CirWinUp.c \
                  ClDisplay.c \
                  ClearArea.c \
                  Clear.c \
		  Cmap.h \
                  ConfWind.c \
                  ConnDis.c \
                  Context.c \
                  ConvSel.c \
                  CopyArea.c \
                  CopyCmap.c \
                  CopyGC.c \
                  CopyPlane.c \
                  CrBFData.c \
                  CrCmap.c \
                  CrCursor.c \
                  CrGC.c \
                  CrGlCur.c \
                  Cr.h \
                  CrPFBData.c \
                  CrPixmap.c \
                  CrWindow.c \
                  Cursor.c \
                  DefCursor.c \
                  DelProp.c \
                  Depths.c \
                  DestSubs.c \
                  DestWind.c \
                  DisName.c \
                  DrArc.c \
                  DrArcs.c \
                  DrLine.c \
                  DrLines.c \
                  DrPoint.c \
                  DrPoints.c \
                  DrRect.c \
                  DrRects.c \
                  DrSegs.c \
                  ErrDes.c \
                  ErrHndlr.c \
                  evtomask.c \
                  EvToWire.c \
                  FetchName.c \
                  FillArc.c \
                  FillArcs.c \
                  FillPoly.c \
                  FillRct.c \
                  FillRcts.c \
                  FilterEv.c \
                  Flush.c \
                  Font.c \
                  FontInfo.c \
                  FontNames.c \
                  FreeCmap.c \
                  FreeCols.c \
                  FreeCurs.c \
                  FreeEData.c \
                  FreeGC.c \
                  FreePix.c \
                  FSSaver.c \
                  FSWrap.c \
                  GCMisc.c \
                  Geom.c \
                  GetAtomNm.c \
                  GetColor.c \
                  GetDflt.c \
                  GetFPath.c \
                  GetFProp.c \
                  GetGCVals.c \
                  GetGeom.c \
                  GetHColor.c \
                  GetHints.c \
                  GetIFocus.c \
                  GetImage.c \
                  GetKCnt.c \
                  GetMoEv.c \
                  GetNrmHint.c \
                  GetPCnt.c \
                  GetPntMap.c \
                  GetProp.c \
                  GetRGBCMap.c \
                  GetSOwner.c \
                  GetSSaver.c \
                  GetStCmap.c \
                  GetTxtProp.c \
                  GetWAttrs.c \
                  GetWMCMapW.c \
                  GetWMProto.c \
                  globals.c \
                  GrButton.c \
                  GrKeybd.c \
                  GrKey.c \
                  GrPointer.c \
                  GrServer.c \
                  Host.c \
                  Iconify.c \
                  IfEvent.c \
		  imConv.c \
                  ImText16.c \
                  ImText.c \
                  ImUtil.c \
                  InitExt.c \
                  InsCmap.c \
                  IntAtom.c \
                  KeyBind.c \
                  Key.h \
                  KeysymStr.c \
                  KillCl.c \
                  LiHosts.c \
                  LiICmaps.c \
                  LiProps.c \
                  ListExt.c \
                  LoadFont.c \
                  LockDis.c \
                  locking.c \
                  locking.h \
                  LookupCol.c \
                  LowerWin.c \
                  Macros.c \
                  MapRaised.c \
                  MapSubs.c \
                  MapWindow.c \
                  MaskEvent.c \
                  Misc.c \
                  ModMap.c \
                  MoveWin.c \
                  NextEvent.c \
                  OCWrap.c \
                  OMWrap.c \
                  OpenDis.c \
                  ParseCmd.c \
                  ParseCol.c \
                  ParseGeom.c \
                  PeekEvent.c \
                  PeekIfEv.c \
                  Pending.c \
                  PixFormats.c \
                  PmapBgnd.c \
                  PmapBord.c \
                  poly.h \
                  PolyReg.c \
                  PolyTxt16.c \
                  PolyTxt.c \
                  PropAlloc.c \
                  PutBEvent.c \
                  PutImage.c \
                  Quarks.c \
                  QuBest.c \
                  QuColor.c \
                  QuColors.c \
                  QuCurShp.c \
                  QuExt.c \
                  QuKeybd.c \
                  QuPntr.c \
                  QuStipShp.c \
                  QuTextE16.c \
                  QuTextExt.c \
                  QuTileShp.c \
                  QuTree.c \
                  RaiseWin.c \
                  RdBitF.c \
                  RecolorC.c \
                  ReconfWin.c \
                  ReconfWM.c \
                  Region.c \
                  RegstFlt.c \
                  RepWindow.c \
                  RestackWs.c \
                  RotProp.c \
                  ScrResStr.c \
                  SelInput.c \
                  SendEvent.c \
                  SetBack.c \
                  SetClMask.c \
                  SetClOrig.c \
                  SetCRects.c \
                  SetDashes.c \
                  SetFont.c \
                  SetFore.c \
                  SetFPath.c \
                  SetFunc.c \
                  SetHints.c \
                  SetIFocus.c \
                  SetLocale.c \
                  SetLStyle.c \
                  SetNrmHint.c \
                  SetPMask.c \
                  SetPntMap.c \
                  SetRGBCMap.c \
                  SetSOwner.c \
                  SetSSaver.c \
                  SetState.c \
                  SetStCmap.c \
                  SetStip.c \
                  SetTile.c \
                  SetTSOrig.c \
                  SetTxtProp.c \
                  SetWMCMapW.c \
                  SetWMProto.c \
                  StBytes.c \
                  StColor.c \
                  StColors.c \
                  StName.c \
                  StNColor.c \
                  StrKeysym.c \
                  StrToText.c \
                  Sync.c \
                  Synchro.c \
                  Text16.c \
                  Text.c \
                  TextExt16.c \
                  TextExt.c \
                  TextToStr.c \
                  TrCoords.c \
                  UndefCurs.c \
                  UngrabBut.c \
                  UngrabKbd.c \
                  UngrabKey.c \
                  UngrabPtr.c \
                  UngrabSvr.c \
                  UninsCmap.c \
                  UnldFont.c \
                  UnmapSubs.c \
                  UnmapWin.c \
                  VisUtil.c \
                  WarpPtr.c \
                  Window.c \
                  WinEvent.c \
                  Withdraw.c \
                  WMGeom.c \
                  WMProps.c \
                  WrBitF.c \
                  x11_trans.c \
                  Xatomtype.h \
                  Xintatom.h \
                  Xintconn.h \
                  XlibAsync.c \
                  XlibInt.c \
                  XomGeneric.h \
                  Xresinternal.h \
                  Xrm.c \
                  XrmI.h

#
# ========================= Extra stuff ============================
#

if OS2
libX11_la_SOURCES+=os2Stubs.c
endif OS2

if UDC
libX11_la_SOURCES+=udcInf.c
endif

if THRSTUBS
libX11_la_SOURCES+=UIThrStubs.c
endif

x11datadir = @X11_DATADIR@
x11data_DATA = XKeysymDB XErrorDB

EXTRA_DIST = \
	$(x11data_DATA) \
	os2Stubs.c \
	udcInf.c \
	UIThrStubs.c 

#
# Figure out which sub-libraries to link into Xlib
#

if XLOCALE
USE_I18N_LIBS = $(I18N_LIBS)
endif

if XCMS
USE_XCMS_LIBS = $(XCMS_LIBS)
endif

if XKB
USE_XKB_LIBS = $(XKB_LIBS)
endif

libX11_la_LDFLAGS = -version-number 6:2:0 -no-undefined

libX11_la_LIBADD = \
	$(USE_I18N_LIBS) \
	$(USE_XCMS_LIBS) \
	$(USE_XKB_LIBS) \
	$(X11_LIBS) \
	$(BIGREQS_LIBS) \
	$(XDMCP_LIBS)

preprocess: $(patsubst %.c,%.ii,$(libX11_la_SOURCES))
.c.ii:
	$(COMPILE) -E -o $@ `test -f '$<' || echo '$(srcdir)/'`$<

#
# Building ks_tables.h requires the makekeys utility
#

KEYSYMDEF=@KEYSYMDEF@

ks_tables.h: $(KEYSYMDEF) $(top_builddir)/src/util/makekeys$(EXEEXT)
	$(top_builddir)/src/util/makekeys < $(KEYSYMDEF) > ks_tables_h
	mv ks_tables_h $@

$(top_builddir)/src/util/makekeys$(EXEEXT): force
	cd util; $(MAKE)

force:
