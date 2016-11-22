TARGET=Textures.xbt
TARGET_CURIAL=curial.xbt

all: $(TARGET) $(TARGET_CURIAL)

.PHONY: force

$(TARGET):
	/home/phil/dev/xbmc/tools/depends/native/TexturePacker/bin/TexturePacker -dupecheck -input . -output $(TARGET)

$(TARGET_CURIAL):
	/home/phil/dev/xbmc/tools/depends/native/TexturePacker/bin/TexturePacker -dupecheck -input ../themes/curial -output $(TARGET_CURIAL)

clean:
	rm -f $(TARGET)
	rm -f $(TARGET_CURIAL)

distclean: clean
