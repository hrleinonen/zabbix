Template_Cisco_ASA_1.1.xml support only SNMPv2 and there is no sysName
\

\
Template_Cisco_ASA_1.1.3.xml support SNMPv3\
SNMPv3 support added, new macros:\
{$SECURITY_NAME} = Username\
{$AUTH_PASSPHRASE} = Authentication password\
{$PRIV_PASSPHRASE} = Encryption password\

Use authentication algorithm SHA and encryption algorithm AES (128).

Added OID: ASA System name (ciscoASAsysName)
\

\
Template Net HP Enterprise Switch SNMPv3.xml
Template Module Interfaces SNMPv3.xml
Template Module Generic SNMPv3.xml
Template Module EtherLike-MIB SNMPv3.xml
\

\
SNMPv3 support added, new macros:
{$SECURITY_NAME} = Username
{$AUTH_PASSPHRASE} = Authentication password 
{$PRIV_PASSPHRASE} = Encryption password

Templates are just like V2 templates, but changed to support SNMPv3.
\

