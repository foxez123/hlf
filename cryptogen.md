# crytopgen structure

| org sub | sub   | certs       | key  |
| ---     | ---   | ---         | ---  |
| ca      |       | .pem        | _sk  |
| msp     |       | admincerts  |      |
|         |       | cacerts     |      |
|         |       | tlscerts    |      |
|         |       | signcert    | keystore(_sk) |
| peers   | msp   | admincerts  |      |
|         |       | cacerts     |      |
|         |       | tlscerts    |      |
|         |       | signcerts   | keystore(_sk) |
|         | tls   | ca.crt      |      |
| tlsca   |       | .pem        | _sk  |
| users(Admin) | msp | admincerts  |  |
|              |     | cacerts     |  |
|              |     | tlscerts    |  |
|              |     | signcert    | keystor(_sk) |
|              | tls | ca.crt      |  |
|              |     | client.crt  | client.key   |
| users(User1) | msp | admincerts  |  |
|              |     | cacerts     |  |
|              |     | tlscerts    |  |
|              |     | signcert    | keystor(_sk) |
|              | tls | ca.crt      |  |
|              |     | client.crt  | client.key   |
