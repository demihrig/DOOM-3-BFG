CC=gcc

TARGETS = \
	Base64.cpp \
	BitMsg.cpp \
	CmdArgs.cpp \
	CommandLink.cpp \
	Dict.cpp \
	Heap.cpp \
	LangDict.cpp \
	Lexer.cpp \
	Lib.cpp \
	MapFile.cpp \
	ParallelJobList.cpp \
	Parser.cpp \
	precompiled.cpp \
	RectAllocator.cpp \
	SoftwareCache.cpp \
	Str.cpp \
	Thread.cpp \
	Timer.cpp \
	Token.cpp \
	bv/Bounds.cpp \
	bv/Box.cpp \
	bv/Sphere.cpp\
	containers/HashIndex.cpp \
	geometry/DrawVert.cpp \
	geometry/JointTransform.cpp \
	geometry/RenderMatrix.cpp \
	geometry/Surface.cpp \
	geometry/Surface_Patch.cpp \
	geometry/Surface_Polytope.cpp \
	geometry/Surface_SweptSpline.cpp \
	geometry/TraceModel.cpp \
	geometry/Winding2D.cpp \
	geometry/Winding.cpp


EXTRA_INC=/usr/include/wine/windows

CFLAGS=--std=c++03 -w

all: $(TARGETS)
	$(CC) $(CFLAGS) -c $(TARGETS) $(patsubst %, -I%, $(EXTRA_INC))