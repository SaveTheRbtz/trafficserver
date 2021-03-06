# Makefile.am for the lib/records
#
#  Licensed to the Apache Software Foundation (ASF) under one
#  or more contributor license agreements.  See the NOTICE file
#  distributed with this work for additional information
#  regarding copyright ownership.  The ASF licenses this file
#  to you under the Apache License, Version 2.0 (the
#  "License"); you may not use this file except in compliance
#  with the License.  You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
#  Unless required by applicable law or agreed to in writing, software
#  distributed under the License is distributed on an "AS IS" BASIS,
#  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#  See the License for the specific language governing permissions and
#  limitations under the License.

AM_CPPFLAGS = \
  -I$(top_srcdir)/iocore/eventsystem \
  -I$(top_srcdir)/iocore/utils \
  -I$(top_srcdir)/mgmt \
  -I$(top_srcdir)/mgmt/cluster \
  -I$(top_srcdir)/mgmt/web2 \
  -I$(top_srcdir)/mgmt/api/include \
  -I$(top_srcdir)/mgmt/utils \
  -I$(top_srcdir)/lib \
  -I$(top_builddir)/lib \
  -I$(top_srcdir)/lib/ts

noinst_LIBRARIES = libreclocal.a librecprocess.a librec4cop.a

libreclocal_a_CXXFLAGS = $(ink_with_modules_local)
libreclocal_a_SOURCES = \
  I_RecAlarms.h \
  I_RecCore.h \
  I_RecDefs.h \
  I_RecEvents.h \
  I_RecLocal.h \
  I_RecMutex.h \
  I_RecSignals.h \
  P_RecFile.h \
  P_RecCore.h \
  P_RecCore.cc \
  P_RecDefs.h \
  P_RecLocal.h \
  P_RecMessage.h \
  P_RecTree.h \
  P_RecUtils.h \
  P_RecFile.h \
  RecFile.cc \
  RecCore.cc \
  RecLocal.cc \
  RecMessage.cc \
  RecMutex.cc \
  RecTree.cc \
  I_RecHttp.h \
  RecHttp.cc \
  RecUtils.cc \
  RecDebug.cc \
  RecConfigParse.cc

librecprocess_a_CXXFLAGS = $(ink_with_modules_process)
librecprocess_a_SOURCES = \
  I_RecAlarms.h \
  I_RecCore.h \
  I_RecDefs.h \
  I_RecEvents.h \
  I_RecMutex.h \
  I_RecProcess.h \
  I_RecSignals.h \
  P_RecFile.h \
  P_RecCore.h \
  P_RecCore.cc \
  P_RecDefs.h \
  P_RecMessage.h \
  P_RecProcess.h \
  P_RecTree.h \
  P_RecUtils.h \
  P_RecFile.h \
  RecFile.cc \
  RecCore.cc \
  RecMessage.cc \
  RecMutex.cc \
  RecProcess.cc \
  RecTree.cc \
  I_RecHttp.h \
  RecHttp.cc \
  RecUtils.cc \
  RecDebug.cc \
  RecConfigParse.cc


librec4cop_a_CXXFLAGS = $(ink_with_modules_process)
librec4cop_a_SOURCES = \
  RecConfigParse.cc \
  RecFile.cc \
  RecDebug.cc
