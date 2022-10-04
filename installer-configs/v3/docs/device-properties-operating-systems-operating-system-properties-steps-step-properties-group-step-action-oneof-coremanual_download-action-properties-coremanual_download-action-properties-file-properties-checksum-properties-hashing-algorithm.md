# Hashing algorithm Schema

```txt
v3/schema/checksum.schema.yml#/properties/operating_systems/items/properties/steps/items/properties/actions/items/oneOf/26/properties/core:manual_download/properties/file/properties/checksum/properties/algorithm
```

Hashing algorithm to use to calculate the checksum

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                          |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [device.schema.json*](../device.schema.json "open original schema") |

## algorithm Type

`string` ([Hashing algorithm](device-properties-operating-systems-operating-system-properties-steps-step-properties-group-step-action-oneof-coremanual_download-action-properties-coremanual_download-action-properties-file-properties-checksum-properties-hashing-algorithm.md))

## algorithm Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value                                  | Explanation |
| :------------------------------------- | :---------- |
| `"RSA-MD4"`                            |             |
| `"RSA-MD5"`                            |             |
| `"RSA-MDC2"`                           |             |
| `"RSA-RIPEMD160"`                      |             |
| `"RSA-SHA1"`                           |             |
| `"RSA-SHA1-2"`                         |             |
| `"RSA-SHA224"`                         |             |
| `"RSA-SHA256"`                         |             |
| `"RSA-SHA3-224"`                       |             |
| `"RSA-SHA3-256"`                       |             |
| `"RSA-SHA3-384"`                       |             |
| `"RSA-SHA3-512"`                       |             |
| `"RSA-SHA384"`                         |             |
| `"RSA-SHA512"`                         |             |
| `"RSA-SHA512/224"`                     |             |
| `"RSA-SHA512/256"`                     |             |
| `"RSA-SM3"`                            |             |
| `"blake2b512"`                         |             |
| `"blake2s256"`                         |             |
| `"id-rsassa-pkcs1-v1_5-with-sha3-224"` |             |
| `"id-rsassa-pkcs1-v1_5-with-sha3-256"` |             |
| `"id-rsassa-pkcs1-v1_5-with-sha3-384"` |             |
| `"id-rsassa-pkcs1-v1_5-with-sha3-512"` |             |
| `"md4"`                                |             |
| `"md4WithRSAEncryption"`               |             |
| `"md5"`                                |             |
| `"md5-sha1"`                           |             |
| `"md5WithRSAEncryption"`               |             |
| `"mdc2"`                               |             |
| `"mdc2WithRSA"`                        |             |
| `"ripemd"`                             |             |
| `"ripemd160"`                          |             |
| `"ripemd160WithRSA"`                   |             |
| `"rmd160"`                             |             |
| `"sha1"`                               |             |
| `"sha1WithRSAEncryption"`              |             |
| `"sha224"`                             |             |
| `"sha224WithRSAEncryption"`            |             |
| `"sha256"`                             |             |
| `"sha256WithRSAEncryption"`            |             |
| `"sha3-224"`                           |             |
| `"sha3-256"`                           |             |
| `"sha3-384"`                           |             |
| `"sha3-512"`                           |             |
| `"sha384"`                             |             |
| `"sha384WithRSAEncryption"`            |             |
| `"sha512"`                             |             |
| `"sha512-224"`                         |             |
| `"sha512-224WithRSAEncryption"`        |             |
| `"sha512-256"`                         |             |
| `"sha512-256WithRSAEncryption"`        |             |
| `"sha512WithRSAEncryption"`            |             |
| `"shake128"`                           |             |
| `"shake256"`                           |             |
| `"sm3"`                                |             |
| `"sm3WithRSAEncryption"`               |             |
| `"ssl3-md5"`                           |             |
| `"ssl3-sha1"`                          |             |
| `"whirlpool"`                          |             |
