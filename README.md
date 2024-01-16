# OmniORB
A fork of the OmniORB SVN @ https://sourceforge.net/p/omniorb/svn/HEAD/tree/

This is not an official package from the creators of omniORB or omniORBpy. The creator of these wheels does not hold any rights to omniORB as well as omniORBpy. We do not give any support and are not liable for any damage caused by the use of this software.

For more information about the copyright holders please visit http://omniorb.sourceforge.net/contact.html


## Changes
```diff
Index: omniORB/src/lib/omniORB/orbcore/ssl/sslContext.cc
IDEA additional info:
Subsystem: com.intellij.openapi.diff.impl.patch.CharsetEP
<+>UTF-8
===================================================================
diff --git a/omniORB/src/lib/omniORB/orbcore/ssl/sslContext.cc b/omniORB/src/lib/omniORB/orbcore/ssl/sslContext.cc
--- a/omniORB/src/lib/omniORB/orbcore/ssl/sslContext.cc	(revision ea58324c8ac0c531fd471bb2e66812506c9f51e8)
+++ b/omniORB/src/lib/omniORB/orbcore/ssl/sslContext.cc	(date 1705418195970)
@@ -277,9 +277,9 @@
 /////////////////////////////////////////////////////////////////////////
 void
 sslContext::set_supported_versions() {
-  SSL_CTX_set_options(pd_ctx,
-                      SSL_OP_NO_SSLv2 | SSL_OP_NO_SSLv3 |
-                      SSL_OP_NO_TLSv1 | SSL_OP_NO_TLSv1_1);
+//  SSL_CTX_set_options(pd_ctx,
+//                      SSL_OP_NO_SSLv2 | SSL_OP_NO_SSLv3 |
+//                      SSL_OP_NO_TLSv1 | SSL_OP_NO_TLSv1_1);
 }
 
 /////////////////////////////////////////////////////////////////////////

```
