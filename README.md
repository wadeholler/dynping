## dynping

DynamopDB Ping is an example of testing our connection to DynamoDB.
Currently this is done via a ListTables call.

*note* - this is a quick hack ymmv

*note* - there is a statically linked binary for linux in the binary
folder temporarily.

Run it:

	export AWS_REGION={your-region}
	exoprt AWS_ACCESS_KEY_ID={access_key}
	export AWS_SECRET_ACCESS_KEY={secret_key}
	./dynping

