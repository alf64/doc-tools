Self Signed Certificate example

KeyStore Explorer has been used to generate new KeyStore (.jks) of PKCS#12 type

Then the following was done in KeyStore Explorer:
- right click -> Generate New KeyPair
type: RSA, size: 2048
- in the next window with properties (validity period, name, signature algorithm) the Common Name (CN) has been set to alf64gordon@gmail.com
- hit ok
- alias same as name
- pass: alf64 (same to all: key pair, keystore, pfx)
- a new key pair was created
- then by right clicking on this key pair, the export of the keypair was made to .pfx file (PKCS#12) with the same pass

the .pfx can be also inspected in KeyStore Explorer by selecting 'Examine Certificate' at the startup

When inspecting the certificate (open .pfx in KeyStore Explorer -> right click key pair -> View Details -> Certificate Chain Details)
Please note that there is only one cert in the chain
Subject and Issuer fields are the same, which means this is Self Signed Certificate (issued by the same person who it is for)

This kind of certificates are not publicly trusted, but yeah the can be used for your own purposes.
