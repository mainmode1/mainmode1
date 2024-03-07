## mainmode1

**[IKEv1 phases](https://en.wikipedia.org/wiki/Internet_Key_Exchange#IKEv1_phases)**

IKE phase one's purpose is to establish a secure authenticated communication channel by using the Diffie-Hellman key exchange algorithm to generate a shared secret key to encrypt further IKE communications. This negotiation results in one single bi-directional ISAKMP Security Association (SA) The authentication can be performed using either pre-shared key (shared secret), signatures, or public key encryption. Phase 1 operates in either Main Mode or Aggressive Mode. Main Mode protects the identity of the peers and the hash of the shared key by encrypting them; Aggressive Mode does not.
