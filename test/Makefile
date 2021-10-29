CC      = gcc
LDFLAGS = -lssl -lcrypto

TARGET  = aes rand rsaes hmac

all: $(TARGET)

rand: rand.c
	$(CC) -o $@ $^ $(LDFLAGS)

aes: aes.c
	$(CC) -o $@ $^ $(LDFLAGS)

rsaes: rsaes.c
	$(CC) -o $@ $^ $(LDFLAGS)

hmac: hmac.c
	$(CC) -o $@ $^ $(LDFLAGS)

clean:
	rm $(TARGET)

# EOF

