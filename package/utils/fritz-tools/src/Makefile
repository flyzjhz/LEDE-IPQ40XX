.PHONY: all clean

all: fritz_tffs_read fritz_cal_extract

clean:
	@rm -rf fritz_tffs_read fritz_cal_extract

fritz_tffs_read: fritz_tffs_read.c
	$(CC) $(CFLAGS) -o $@ $<

fritz_cal_extract: fritz_cal_extract.c
	$(CC) $(CLAGS) -lz -o $@ $<
