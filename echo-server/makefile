TARGET=echo-server
LDLIBS+=-pthread

all: $(TARGET)

$(TARGET): $(TARGET).o
	$(LINK.cpp) $^ $(LOADLIBES) $(LDLIBS) -o $@

clean:
	rm -f $(TARGET) *.o
