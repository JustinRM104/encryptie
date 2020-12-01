$encrypted = $e = NULL;
openssl_seal($data, $encrypted, $e, array($public_key));
$sealed_data = base64_encode($encrypted);
openssl_public_encrypt('this was encrypted with the public key', $secret, $pubKey);
mcrypt_encrypt -- mag niet gebruikt worden
crypt()
encryption_key

RSA KAN MAX 245 bytes


