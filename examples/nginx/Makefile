
ssl:
	mkdir -p ssl
	openssl req -x509 -newkey rsa:4096 -sha256 -nodes -keyout ssl/key.pem -out ssl/cert.pem \
		-days 30 \
		-subj "/CN=do-not.use.prod/"
