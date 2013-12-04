Video saving utility based on Lukasz Karluks work of the same name 
http://www.julapy.com/work/featured/
https://code.google.com/p/julapy/source/browse/trunk/openframeworks/ofxJulapyUtils/ofxVideoSaver.h?r=722

Note:
openframeworks expects to be compiled as a 32bit application. This means that only about 650mb are going to be available to it on a 64bit OS. setting /LARGEADDRESSAWARE linker option in visual studio can extend the length of the video, but it will still run out of available memory before using all system memory. 
