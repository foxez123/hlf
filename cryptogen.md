# crytopgen

| type  |     | certs      | key |
| ---   | --- | ---        | --- |
| ca    |     | .pem       | _sk |
| msp   | .   | admincerts | |
|       | .   | cacerts    | |
|       | .   | tlscerts   | |
|       | .   | signcert   | |
| peers | msp | admincerts  | .   |
|       |     | cacerts     | .   |
|       |     | tlscerts    | .   |
|       |     | signcerts   | keystore (_sk) |
|       | tls | ca.crt      | .   |
|       |     | client.crt  | clent.key |
