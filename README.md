Need to set env variables before runing encrypt.py and decrypt.py (run gen_keys.py first)
on linux:\
`export PEMK=./priv.pem`
`export PUB_PEMK=./pub.pem`

After running gen_keys.py, you can encrypt a file with:\
`./encrypt.py FILE_TO_ENCRYPT`

To decrypt the file:\
`./decrypt.py FILE_TO_DECRYPT`