Version 1.1, only SNMPv2 and missing sysName

Version 1.1.3
SNMPv3 support added, new macros:
{$SECURITY_NAME} = Username
{$AUTH_PASSPHRASE} = Authentication password 
{$PRIV_PASSPHRASE} = Encryption password

Use authentication algorithm SHA and encryption algorithm AES (128).

Added OID: ASA System name (ciscoASAsysName)
