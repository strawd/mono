thisdir = class

# Note that Mono.Security and System.Security aren't listed.
# We may have to add those if 'mcs' starts using them.
basic_SUBDIRS := corlib System System.XML System Mono.Security System.Core 

# resgen is corlib specific so we need to wait until corlib is build
# and build it just a step before first dll needs it
resgen_dir = ../tools/resgen

build_SUBDIRS :=  \
	corlib \
	System \
	System.XML \
	System Mono.Security \
	Mono.Posix \
	System.Core

net_2_0_dirs := \
	corlib				\
	System				\
	System.XML			\
	Mono.CompilerServices.SymbolWriter \
	Mono.Posix			\
	System.Core			\
	Mono.Security			\
	System.Security			\
	System.Configuration		\
	I18N				\
	$(resgen_dir)			\
	System.Drawing			\
	System.Transactions		\
	System.EnterpriseServices	\
	Mono.Data.Tds			\
	System.Data			\
	Accessibility			\
	Mono.WebBrowser			\
	System.Runtime.Serialization.Formatters.Soap \
	Managed.Windows.Forms		\
	Mono.Data.Sqlite		\
	System.Web.ApplicationServices	\
	System.Web			\
	System.Web.Services		\
	System.Runtime.Remoting		\
	System.Configuration.Install 	\
	System.Management		\
	System.Data.OracleClient	\
	Microsoft.VisualC		\
	Cscompmgd			\
	PEAPI				\
	Npgsql				\
	Commons.Xml.Relaxng		\
	Novell.Directory.Ldap		\
	Mono.Security.Win32		\
	System.DirectoryServices	\
	System.DirectoryServices.Protocols	\
	RabbitMQ.Client			\
	Mono.Messaging			\
	System.Messaging	        \
	Mono.Messaging.RabbitMQ		\
	System.ServiceProcess           \
	System.Drawing.Design		\
	System.Design			\
	ICSharpCode.SharpZipLib		\
	Mono.Http			\
	Mono.Cairo                      \
	IBM.Data.DB2			\
	CustomMarshalers		\
	Mono.Cecil			\
	Mono.Cecil.Mdb			\
	Mono.Debugger.Soft		\
	SystemWebTestShim			\
	System.Xml.Linq			\
	System.Runtime.Serialization	\
	System.Data.DataSetExtensions	\
	System.Data.Linq		\
	System.Web.Abstractions		\
	System.Web.Routing		\
	System.IdentityModel		\
	System.IdentityModel.Selectors	\
	System.ServiceModel		\
	System.Web.Extensions		\
	System.Web.Extensions.Design	\
	System.ComponentModel.DataAnnotations	\
	System.Web.DynamicData		\
	System.Web.Mvc2			\
	Mono.C5				\
	Mono.Management			\
	Mono.Options 			\
	Mono.Simd			\
	Mono.Tasklets       		\
	System.Dynamic			\
	Mono.CSharp			\
	System.Net			\
	System.Json

net_2_0_only_dirs := \
	System.Web.Extensions_1.0	\
	System.Web.Extensions.Design_1.0\
	Compat.ICSharpCode.SharpZipLib	\
	WindowsBase			\
	System.ServiceModel.Web 	\
	System.Data.Services.Client	\
	System.Data.Services		\
	System.Web.Mvc \

pcl_facade_dirs := Facades

mobile_common_dirs := \
	corlib	\
	System	\
	System.Core	\
	System.XML	\
	Mono.Security	\
	System	\
	I18N		\
	System.Xml.Linq	\
	System.Runtime.Serialization	\
	System.ServiceModel	\
	System.ServiceModel.Web	\
	System.Json	\
	System.Web.Services	\
	Mono.Data.Tds	\
	System.Transactions	\
	System.Data	\
	Mono.Cairo	\
	Mono.Data.Sqlite	\
	System.Numerics	\
	System.Data.Services.Client \
	System.IO.Compression \
	System.IO.Compression.FileSystem \
	System.ComponentModel.DataAnnotations \
	System.ComponentModel.Composition.4.5 \
	System.Net \
	System.Windows \
	System.Xml.Serialization \
	Mono.CSharp	\
	Microsoft.CSharp \
	$(pcl_facade_dirs)

mobile_static_dirs := \
	$(mobile_common_dirs)	\
	Mono.Dynamic.Interpreter

mobile_dynamic_dirs := \
	$(mobile_common_dirs)	\
	Mono.CompilerServices.SymbolWriter	\
	System.Net.Http

xammac_dirs := \
	$(mobile_dynamic_dirs)

monodroid_dirs := \
	$(mobile_dynamic_dirs)

monotouch_dirs := \
	$(mobile_static_dirs)

monotouch_runtime_dirs := \
	corlib \
	System \
	System.Core \
	System.XML \
	Mono.CSharp

net_4_0_dirs := \
	System.Numerics		\
	Microsoft.CSharp	\
	System.Windows.Forms.DataVisualization	\
	System.Xaml \
	WindowsBase \
	System.ServiceModel.Activation \
	System.ServiceModel.Routing \
	System.ServiceModel.Discovery \
	System.Runtime.Caching \
	System.Runtime.DurableInstancing \
	Mono.Parallel \
	System.Reactive.Interfaces \
	System.Reactive.Core \
	System.Reactive.Linq \
	System.Reactive.PlatformServices \
	System.Reactive.Providers \
	System.Reactive.Runtime.Remoting \
	System.Reactive.Windows.Forms \
	System.Reactive.Windows.Threading \
	System.Reactive.Observable.Aliases \
	System.Reactive.Experimental \
	System.Reactive.Debugger \
	Microsoft.Web.Infrastructure \
	WebMatrix.Data \
	System.ServiceModel.Web \
	System.Data.Services.Client	\
	System.Data.Services \
	System.Json.Microsoft \
	monodoc

net_4_0_only_dirs := \
	System.ComponentModel.Composition

net_4_5_dirs := \
	System.Threading.Tasks.Dataflow \
	System.ComponentModel.Composition.4.5 \
	System.Net.Http	\
	System.Net.Http.WebRequest \
	System.Web.Razor \
	System.Web.WebPages.Deployment \
	System.Web.WebPages \
	System.Web.WebPages.Razor \
	System.Web.Mvc3 \
	System.Net.Http.Formatting \
	System.Web.Http \
	System.Web.Http.SelfHost \
	System.Web.Http.WebHost \
	EntityFramework	\
	EntityFramework.SqlServer	\
	Mono.CodeContracts \
	System.IO.Compression \
	System.IO.Compression.FileSystem \
	System.Windows \
	System.Xml.Serialization \
	$(pcl_facade_dirs)

xbuild_2_0_dirs := \
	Microsoft.Build.Framework	\
	Microsoft.Build.Utilities	\
	Microsoft.Build.Engine		\
	Mono.XBuild.Tasks		\
	Microsoft.Build.Tasks

xbuild_4_0_dirs := \
	$(xbuild_2_0_dirs)	\
	Microsoft.Build

net_2_0_SUBDIRS := $(net_2_0_dirs) $(net_2_0_only_dirs) $(xbuild_2_0_dirs) aot-compiler
monodroid_SUBDIRS := $(monodroid_dirs)
monotouch_SUBDIRS := $(monotouch_dirs)
monotouch_runtime_SUBDIRS := $(monotouch_runtime_dirs)
mobile_static_SUBDIRS := $(mobile_static_dirs)
mobile_SUBDIRS := $(mobile_dynamic_dirs)
xammac_SUBDIRS := $(xammac_dirs)
net_3_5_SUBDIRS := $(xbuild_2_0_dirs)
net_4_0_SUBDIRS := $(net_2_0_dirs) $(net_4_0_dirs) $(net_4_0_only_dirs) $(xbuild_4_0_dirs)
net_4_5_SUBDIRS := $(net_2_0_dirs) $(net_4_0_dirs) $(net_4_5_dirs) $(xbuild_4_0_dirs) aot-compiler
xbuild_12_SUBDIRS := $(xbuild_4_0_dirs)

include ../build/rules.make

SUBDIRS = $(net_2_0_dirs) $(net_2_0_only_dirs) $(mobile_static_dirs) $(mobile_dynamic_dirs) $(monotouch_dirs) $(monodroid_dirs) $(xammac_dirs) $(net_4_0_dirs) $(net_4_0_only_dirs) $(net_4_5_dirs)

DIST_ONLY_SUBDIRS = dlr aot-compiler $(xbuild_4_0_dirs)

# No new makefiles for: System.Messaging, System.Web.Mobile,
# System.ServiceProcess

DISTFILES = \
	ecma.pub		\
	winfx.pub		\
	winfx3.pub		\
	mono.pub		\
	msfinal.pub		\
	silverlight.pub		\
	reactive.pub		\
	mono.snk		\
	LICENSE 		\
	README			\
	doc/API-notes		\
	doc/NUnitGuidelines	\
	doc/TemplateTest.cs	\
	notes/BitVecto32.txt	\
	MicrosoftAjaxLibrary/License.htm	\
	$(monolite_files)

.PHONY: all-local $(STD_TARGETS:=-local)
all-local $(STD_TARGETS:=-local):
	@:

# Files needed to bootstrap C# compiler
basic_files = basic.exe mscorlib.dll System.dll System.Xml.dll Mono.Security.dll System.Core.dll System.Security.dll System.Configuration.dll
monolite_files = $(basic_files:%=lib/monolite/%)

lib/monolite:
	$(MKINSTALLDIRS) $@

$(monolite_files): | lib/monolite
$(monolite_files): lib/monolite/%: lib/basic/%
	cp -p $< $@

$(basic_files:%=lib/basic/%):
	cd $(topdir) && $(MAKE) profile-do--basic--all NO_DIR_CHECK=1 SKIP_AOT=1

dist-default: $(monolite_files)
dist-local: dist-default

csproj-local:

