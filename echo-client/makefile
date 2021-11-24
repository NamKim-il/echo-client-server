TARGET=echo-client
LDLIBS+=-pthread

$(TARGET): $(TARGET).o 
	$(LINK.cpp) $^ $(LOADLIBES) $(LDLIBS) -o $@

clean:
	rm -f $(TARGET) *.o
