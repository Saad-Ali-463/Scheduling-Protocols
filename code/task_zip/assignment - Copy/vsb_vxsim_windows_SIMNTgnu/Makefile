# Wind River Workbench generated Makefile.
# Do not edit!!!
#
# The file ".wrmakefile" is the template used by the Wind River Workbench to
# generate the makefiles of this project. Add user-specific build targets and
# make rules only(!) in this project's ".wrmakefile" file. These will then be
# automatically dumped into the makefiles.

WIND_HOME := $(subst \,/,$(WIND_HOME))
WIND_BASE := $(subst \,/,$(WIND_BASE))
WIND_USR := $(subst \,/,$(WIND_USR))
WRVX_COMPBASE := $(subst \,/,$(WRVX_COMPBASE))
WIND_KRNL_MK := $(subst \,/,$(WIND_KRNL_MK))
WIND_USR_MK := $(subst \,/,$(WIND_USR_MK))
WIND_BUILD := $(subst \,/,$(WIND_BUILD))
WIND_BUILD_TOOL := $(subst \,/,$(WIND_BUILD_TOOL))

all : check_vsb pre_build main_all post_build

_clean ::
	@echo "make: removing targets and objects of `pwd`"

TRACE=0
TRACEON=$(TRACE:0=@)
TRACE_FLAG=$(TRACEON:1=)

JOBS?=1
TARGET_JOBS?=$(JOBS)

MAKEFILE := Makefile

FLEXIBLE_BUILD := 1

BUILD_SPEC = vsb_vxsim_windows_SIMNTgnu
DEBUG_MODE = 1
ifeq ($(DEBUG_MODE),1)
MODE_DIR := Debug
else
MODE_DIR := NonDebug
endif
OBJ_DIR := .
WS_ROOT_DIR := C:/Users/s0001061473/Downloads
PRJ_ROOT_DIR := $(WS_ROOT_DIR)/assignment



#Global Build Macros
PROJECT_TYPE = DKM
DEFINES = 
EXPAND_DBG = 0
APICHECK_OPTIONS = -warning


#BuildSpec specific Build Macros
VX_CPU_FAMILY = simpc
CPU = SIMNT
TOOL_FAMILY = gnu
TOOL_VERSION = gnu_4_8_1_8
_CC_VERSION = gnu_4_8_1_11
TOOL = gnu
TOOL_PATH = $(WIND_HOME)/compilers/gnu-4.8.1.11/$(WIND_VX7_GNU_HOST_TYPE)/bin
CC_ARCH_SPEC = -m32 -mfpmath=387 -fno-builtin -fno-implicit-fp -fno-omit-frame-pointer -nostdlib -fno-defer-pop
VSB_DIR = $(WIND_BASE)/samples/prebuilt_projects/vsb_vxsim_windows
VSB_CONFIG_FILE = $(VSB_DIR)/h/config/vsbConfig.h
LIBPATH = 
LIBS = 
DKM_LONGCALL = 
BDGEN_VSB_INCLUDE = $(VSB_DIR)/h/config/auto.conf
APICHECK_CMD = apicheck.sh -r "$(VSB_DIR)/krnl/apicheck/forbidden_api.lst" -n "nmpentium" -u -s "$<" "$@" $(APICHECK_OPTIONS)
APICHECK = 0

IDE_INCLUDES = -I$(VSB_DIR)/share/h -isystem$(VSB_DIR)/krnl/h/system -isystem$(VSB_DIR)/krnl/h/public 

IDE_LIBRARIES = 

IDE_DEFINES = -DCPU=_VX_$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL -D_VSB_CONFIG_FILE=\"$(VSB_DIR)/h/config/vsbConfig.h\"   



#BuildTool flags
ifeq ($(DEBUG_MODE),1)
DEBUGFLAGS_C-Compiler = -gdwarf-3
DEBUGFLAGS_C++-Compiler = -gdwarf-3
DEBUGFLAGS_Linker = -gdwarf-3
DEBUGFLAGS_Partial-Image-Linker = 
DEBUGFLAGS_Librarian = 
DEBUGFLAGS_Assembler = -gdwarf-3
else
DEBUGFLAGS_C-Compiler = -O2
DEBUGFLAGS_C++-Compiler = -O2
DEBUGFLAGS_Linker = -O2
DEBUGFLAGS_Partial-Image-Linker = 
DEBUGFLAGS_Librarian = 
DEBUGFLAGS_Assembler = -O2
endif


#Project Targets
PROJECT_TARGETS = assignment/$(MODE_DIR)/assignment.out \
	 assignment_partialImage/$(MODE_DIR)/assignment_partialImage.o


#Rules

# assignment
ifeq ($(DEBUG_MODE),1)
assignment/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -gdwarf-3
assignment/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -gdwarf-3
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -gdwarf-3
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -gdwarf-3
else
assignment/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -O2
assignment/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -O2
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -O2
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
assignment/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -O2
endif
assignment/$(MODE_DIR)/% : IDE_INCLUDES = -I$(VSB_DIR)/share/h -isystem$(VSB_DIR)/krnl/h/system -isystem$(VSB_DIR)/krnl/h/public 
assignment/$(MODE_DIR)/% : IDE_LIBRARIES = 
assignment/$(MODE_DIR)/% : IDE_DEFINES = -DCPU=_VX_$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL -D_VSB_CONFIG_FILE=\"$(VSB_DIR)/h/config/vsbConfig.h\"   
assignment/$(MODE_DIR)/% : PROJECT_TYPE = DKM
assignment/$(MODE_DIR)/% : DEFINES = 
assignment/$(MODE_DIR)/% : EXPAND_DBG = 0
assignment/$(MODE_DIR)/% : APICHECK_OPTIONS = -warning
assignment/$(MODE_DIR)/% : VX_CPU_FAMILY = simpc
assignment/$(MODE_DIR)/% : CPU = SIMNT
assignment/$(MODE_DIR)/% : TOOL_FAMILY = gnu
assignment/$(MODE_DIR)/% : TOOL_VERSION = gnu_4_8_1_8
assignment/$(MODE_DIR)/% : _CC_VERSION = gnu_4_8_1_11
assignment/$(MODE_DIR)/% : TOOL = gnu
assignment/$(MODE_DIR)/% : TOOL_PATH = $(WIND_HOME)/compilers/gnu-4.8.1.11/$(WIND_VX7_GNU_HOST_TYPE)/bin
assignment/$(MODE_DIR)/% : CC_ARCH_SPEC = -m32 -mfpmath=387 -fno-builtin -fno-implicit-fp -fno-omit-frame-pointer -nostdlib -fno-defer-pop
assignment/$(MODE_DIR)/% : VSB_DIR = $(WIND_BASE)/samples/prebuilt_projects/vsb_vxsim_windows
assignment/$(MODE_DIR)/% : VSB_CONFIG_FILE = $(VSB_DIR)/h/config/vsbConfig.h
assignment/$(MODE_DIR)/% : LIBPATH = 
assignment/$(MODE_DIR)/% : LIBS = 
assignment/$(MODE_DIR)/% : DKM_LONGCALL = 
assignment/$(MODE_DIR)/% : BDGEN_VSB_INCLUDE = $(VSB_DIR)/h/config/auto.conf
assignment/$(MODE_DIR)/% : APICHECK_CMD = apicheck.sh -r "$(VSB_DIR)/krnl/apicheck/forbidden_api.lst" -n "nmpentium" -u -s "$<" "$@" $(APICHECK_OPTIONS)
assignment/$(MODE_DIR)/% : APICHECK = 0
assignment/$(MODE_DIR)/% : OBJ_DIR := assignment/$(MODE_DIR)

OBJECTS_assignment = assignment_partialImage/$(MODE_DIR)/assignment_partialImage.o

checkDirassignment : 
	mkdir -p assignment/$(MODE_DIR)/
assignment/$(MODE_DIR)/.assignmentObject.list: $(OBJECTS_assignment) | checkDirassignment
	$(file >$@,$^)
ifeq ($(TARGET_JOBS),1)
assignment/$(MODE_DIR)/assignment.out : assignment/$(MODE_DIR)/.assignmentObject.list | check_objdirs
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@";rm -f "$@";nmpentium @assignment/$(MODE_DIR)/.assignmentObject.list | tclsh $(WIND_BASE)/build/mk/tcl/munch.tcl -c pentium -tags $(VSB_DIR)/krnl/tags/dkm.tags > $(OBJ_DIR)/ctdt.c; $(TOOL_PATH)/ccpentium $(DEBUGFLAGS_Linker) $(CC_ARCH_SPEC) -fdollars-in-identifiers -Wall   $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES)  $(DKM_LONGCALL) $(IDE_DEFINES) $(DEFINES) -o $(OBJ_DIR)/ctdt.o -c $(OBJ_DIR)/ctdt.c;  $(TOOL_PATH)/ccpentium -r -nostdlib -Wl,-X -T $(WIND_BASE)/build/tool/gnu_4_8_1_8/krnl/ldscripts/link.OUT -o "$@" $(OBJ_DIR)/ctdt.o @assignment/$(MODE_DIR)/.assignmentObject.list $(IDE_LIBRARIES) $(LIBPATH) $(LIBS) $(ADDED_LIBPATH) $(ADDED_LIBS) && if [ "$(EXPAND_DBG)" = "1" ]; then plink "$@";fi && $(if $(_WRS_CONFIG_SECURE_LOADER),signtool  --key=$(_WRS_CONFIG_SECURE_LOADER_PRIVATE_SIGNING_KEY_FILE) --cert=$(_WRS_CONFIG_SECURE_LOADER_PUBLIC_SIGNING_CERT_FILE) --type=ELF $@,true) && true

else
assignment/$(MODE_DIR)/assignment.out : assignment/$(MODE_DIR)/assignment.out_jobs

endif
assignment/$(MODE_DIR)/assignment_compile_file : $(FILE) ;

_clean :: assignment/$(MODE_DIR)/assignment_clean

assignment/$(MODE_DIR)/assignment_clean : 
	$(TRACE_FLAG)if [ -d "assignment" ]; then cd "assignment"; rm -rf $(MODE_DIR); fi


# assignment_partialImage
ifeq ($(DEBUG_MODE),1)
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -gdwarf-3
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -gdwarf-3
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -gdwarf-3
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -gdwarf-3
else
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_C-Compiler = -O2
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_C++-Compiler = -O2
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Linker = -O2
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Partial-Image-Linker = 
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Librarian = 
assignment_partialImage/$(MODE_DIR)/% : DEBUGFLAGS_Assembler = -O2
endif
assignment_partialImage/$(MODE_DIR)/% : IDE_INCLUDES = -I$(VSB_DIR)/share/h -isystem$(VSB_DIR)/krnl/h/system -isystem$(VSB_DIR)/krnl/h/public 
assignment_partialImage/$(MODE_DIR)/% : IDE_LIBRARIES = 
assignment_partialImage/$(MODE_DIR)/% : IDE_DEFINES = -DCPU=_VX_$(CPU) -DTOOL_FAMILY=$(TOOL_FAMILY) -DTOOL=$(TOOL) -D_WRS_KERNEL -D_VSB_CONFIG_FILE=\"$(VSB_DIR)/h/config/vsbConfig.h\"   
assignment_partialImage/$(MODE_DIR)/% : PROJECT_TYPE = DKM
assignment_partialImage/$(MODE_DIR)/% : DEFINES = 
assignment_partialImage/$(MODE_DIR)/% : EXPAND_DBG = 0
assignment_partialImage/$(MODE_DIR)/% : APICHECK_OPTIONS = -warning
assignment_partialImage/$(MODE_DIR)/% : VX_CPU_FAMILY = simpc
assignment_partialImage/$(MODE_DIR)/% : CPU = SIMNT
assignment_partialImage/$(MODE_DIR)/% : TOOL_FAMILY = gnu
assignment_partialImage/$(MODE_DIR)/% : TOOL_VERSION = gnu_4_8_1_8
assignment_partialImage/$(MODE_DIR)/% : _CC_VERSION = gnu_4_8_1_11
assignment_partialImage/$(MODE_DIR)/% : TOOL = gnu
assignment_partialImage/$(MODE_DIR)/% : TOOL_PATH = $(WIND_HOME)/compilers/gnu-4.8.1.11/$(WIND_VX7_GNU_HOST_TYPE)/bin
assignment_partialImage/$(MODE_DIR)/% : CC_ARCH_SPEC = -m32 -mfpmath=387 -fno-builtin -fno-implicit-fp -fno-omit-frame-pointer -nostdlib -fno-defer-pop
assignment_partialImage/$(MODE_DIR)/% : VSB_DIR = $(WIND_BASE)/samples/prebuilt_projects/vsb_vxsim_windows
assignment_partialImage/$(MODE_DIR)/% : VSB_CONFIG_FILE = $(VSB_DIR)/h/config/vsbConfig.h
assignment_partialImage/$(MODE_DIR)/% : LIBPATH = 
assignment_partialImage/$(MODE_DIR)/% : LIBS = 
assignment_partialImage/$(MODE_DIR)/% : DKM_LONGCALL = 
assignment_partialImage/$(MODE_DIR)/% : BDGEN_VSB_INCLUDE = $(VSB_DIR)/h/config/auto.conf
assignment_partialImage/$(MODE_DIR)/% : APICHECK_CMD = apicheck.sh -r "$(VSB_DIR)/krnl/apicheck/forbidden_api.lst" -n "nmpentium" -u -s "$<" "$@" $(APICHECK_OPTIONS)
assignment_partialImage/$(MODE_DIR)/% : APICHECK = 0
assignment_partialImage/$(MODE_DIR)/% : OBJ_DIR := assignment_partialImage/$(MODE_DIR)

assignment_partialImage/$(MODE_DIR)/Objects/assignment/applications.o : $(PRJ_ROOT_DIR)/applications.c $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)/ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -fno-zero-initialized-in-bss -Wall    -MD -MP $(DKM_LONGCALL) $(IDE_DEFINES) $(DEFINES) $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -o "$@" -c "$<" && if [ "$(APICHECK)" = "1" ]; then $(APICHECK_CMD);fi


assignment_partialImage/$(MODE_DIR)/Objects/assignment/dkm.o : $(PRJ_ROOT_DIR)/dkm.c $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)/ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -fno-zero-initialized-in-bss -Wall    -MD -MP $(DKM_LONGCALL) $(IDE_DEFINES) $(DEFINES) $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -o "$@" -c "$<" && if [ "$(APICHECK)" = "1" ]; then $(APICHECK_CMD);fi


assignment_partialImage/$(MODE_DIR)/Objects/assignment/dummyTask.o : $(PRJ_ROOT_DIR)/dummyTask.c $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)/ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -fno-zero-initialized-in-bss -Wall    -MD -MP $(DKM_LONGCALL) $(IDE_DEFINES) $(DEFINES) $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -o "$@" -c "$<" && if [ "$(APICHECK)" = "1" ]; then $(APICHECK_CMD);fi


assignment_partialImage/$(MODE_DIR)/Objects/assignment/metascheduler.o : $(PRJ_ROOT_DIR)/metascheduler.c $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)/ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -fno-zero-initialized-in-bss -Wall    -MD -MP $(DKM_LONGCALL) $(IDE_DEFINES) $(DEFINES) $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -o "$@" -c "$<" && if [ "$(APICHECK)" = "1" ]; then $(APICHECK_CMD);fi


assignment_partialImage/$(MODE_DIR)/Objects/assignment/resources.o : $(PRJ_ROOT_DIR)/resources.c $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)/ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -fno-zero-initialized-in-bss -Wall    -MD -MP $(DKM_LONGCALL) $(IDE_DEFINES) $(DEFINES) $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -o "$@" -c "$<" && if [ "$(APICHECK)" = "1" ]; then $(APICHECK_CMD);fi


assignment_partialImage/$(MODE_DIR)/Objects/assignment/simulation.o : $(PRJ_ROOT_DIR)/simulation.c $(FORCE_FILE_BUILD)
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@"; $(TOOL_PATH)/ccpentium $(DEBUGFLAGS_C-Compiler) $(CC_ARCH_SPEC) -ansi  -fno-zero-initialized-in-bss -Wall    -MD -MP $(DKM_LONGCALL) $(IDE_DEFINES) $(DEFINES) $(ADDED_CFLAGS) $(IDE_INCLUDES) $(ADDED_INCLUDES) -o "$@" -c "$<" && if [ "$(APICHECK)" = "1" ]; then $(APICHECK_CMD);fi


OBJECTS_assignment_partialImage = assignment_partialImage/$(MODE_DIR)/Objects/assignment/applications.o \
	 assignment_partialImage/$(MODE_DIR)/Objects/assignment/dkm.o \
	 assignment_partialImage/$(MODE_DIR)/Objects/assignment/dummyTask.o \
	 assignment_partialImage/$(MODE_DIR)/Objects/assignment/metascheduler.o \
	 assignment_partialImage/$(MODE_DIR)/Objects/assignment/resources.o \
	 assignment_partialImage/$(MODE_DIR)/Objects/assignment/simulation.o

checkDirassignment_partialImage : 
	mkdir -p assignment_partialImage/$(MODE_DIR)/
assignment_partialImage/$(MODE_DIR)/.assignment_partialImageObject.list: $(OBJECTS_assignment_partialImage) | checkDirassignment_partialImage
	$(file >$@,$^)
ifeq ($(TARGET_JOBS),1)
assignment_partialImage/$(MODE_DIR)/assignment_partialImage.o : assignment_partialImage/$(MODE_DIR)/.assignment_partialImageObject.list | check_objdirs
	$(TRACE_FLAG)if [ ! -d "`dirname "$@"`" ]; then mkdir -p "`dirname "$@"`"; fi;echo "building $@";  $(TOOL_PATH)/ccpentium -r -nostdlib -Wl,-X  -o "$@" @assignment_partialImage/$(MODE_DIR)/.assignment_partialImageObject.list $(ADDED_OBJECTS) $(IDE_LIBRARIES) $(LIBPATH) $(LIBS) $(ADDED_LIBPATH) $(ADDED_LIBS) && if [ "$(EXPAND_DBG)" = "1" ]; then plink "$@";fi

else
assignment_partialImage/$(MODE_DIR)/assignment_partialImage.o : assignment_partialImage/$(MODE_DIR)/assignment_partialImage.o_jobs

endif
assignment_partialImage/$(MODE_DIR)/assignment_partialImage_compile_file : $(FILE) ;

_clean :: assignment_partialImage/$(MODE_DIR)/assignment_partialImage_clean

assignment_partialImage/$(MODE_DIR)/assignment_partialImage_clean : 
	$(TRACE_FLAG)if [ -d "assignment_partialImage" ]; then cd "assignment_partialImage"; rm -rf $(MODE_DIR); fi

force : 

TARGET_JOBS_RULE?=echo "Update the makefile template via File > Import > Build Settings : Update makefile template";exit 1
%_jobs : 
	$(TRACE_FLAG)$(TARGET_JOBS_RULE)

DEP_FILES := assignment_partialImage/$(MODE_DIR)/Objects/assignment/applications.d assignment_partialImage/$(MODE_DIR)/Objects/assignment/dkm.d assignment_partialImage/$(MODE_DIR)/Objects/assignment/dummyTask.d \
	 assignment_partialImage/$(MODE_DIR)/Objects/assignment/metascheduler.d assignment_partialImage/$(MODE_DIR)/Objects/assignment/resources.d assignment_partialImage/$(MODE_DIR)/Objects/assignment/simulation.d
-include $(DEP_FILES)

OBJ_DIRS := assignment_partialImage/$(MODE_DIR)/Objects/assignment
check_objdirs : 
	$(TRACE_FLAG)echo "Creating object dirs";\
	for dir in $(OBJ_DIRS); do\
		if [ ! -d "$$dir" ]; then mkdir -p "$$dir"; fi;\
	done


ifdef BDGEN_VSB_INCLUDE
include $(BDGEN_VSB_INCLUDE)
endif

-include $(PRJ_ROOT_DIR)/*.makefile

-include *.makefile

TARGET_JOBS_RULE=$(MAKE) -f $(MAKEFILE) --jobs $(TARGET_JOBS) $(MFLAGS) $* TARGET_JOBS=1
ifeq ($(JOBS),1)
main_all : external_build $(PROJECT_TARGETS)
	@echo "make: built targets of `pwd`"
else
main_all : external_build 
	@$(MAKE) -f $(MAKEFILE) --jobs $(JOBS) $(MFLAGS) $(PROJECT_TARGETS) TARGET_JOBS=1 &&\
	echo "make: built targets of `pwd`"
endif 

check_vsb :
	@if [ "$(SKIP_VSB_CHECK)" = "" ]; then\
		if [ -f $(WIND_BASE)/build/mk/scripts/check_vsb.sh ]; then\
			jobsoption="";\
			if [ "$(JOBS)" != "" ]; then\
				jobsoption="-j $(JOBS)";\
			fi;\
			sh $(WIND_BASE)/build/mk/scripts/check_vsb.sh $$jobsoption $(VSB_DIR);\
		fi;\
	fi

# entry point for extending the build
external_build ::
	@echo ""

# main entry point for pre processing prior to the build
pre_build :: check_objdirs $(PRE_BUILD_STEP) generate_sources
	@echo ""

# entry point for generating sources prior to the build
generate_sources ::
	@echo ""

# main entry point for post processing after the build
post_build :: $(POST_BUILD_STEP) deploy_output
	@echo ""

# entry point for deploying output after the build
deploy_output ::
	@echo ""

clean :: external_clean $(CLEAN_STEP) _clean

# entry point for extending the build clean
external_clean ::
	@echo ""
