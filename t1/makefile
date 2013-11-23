CXXFLAGS=`fltk-config  --cxxflags`
#-I/usr/local/include -I/usr/local/include/FL/images
LDFLAGS=`fltk-config  --ldflags`
#-L/usr/local/lib -lfltk -ldl -lm -lXext -lX11

t1: t1.o
	g++ -o $@ $< $(LDFLAGS) 
t1.o: t1.cpp
	g++ $(CXXFLAGS) -c $<

clean:
	rm -rf *.o t1
