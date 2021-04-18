# Test Data

## ~/submitstar endpoint

req.body.address && req.body.message && req.body.signature && req.body.star

{
    "address": "1244UFxySQF5M3UHHp7cyBgqnkS3z7BvUH",
    "message": "1244UFxySQF5M3UHHp7cyBgqnkS3z7BvUH:1618721895:starRegistry",
    "signature": "IMIWExOm3hfBRYcIJ9PxmKJtpNh3W4TyiX0Q9p8fFoasdvzVhEW+yethsTPTnIVSRURjsJMRxI7G0aZDQ2qaDFo=",
    "star": {
        "dec": "68° 52' 56.9",
        "ra": "16h 29m 1.0s",
        "story": "Testing the story 4"
    }
}

-----BEGIN BITCOIN SIGNED MESSAGE-----
1244UFxySQF5M3UHHp7cyBgqnkS3z7BvUH:1618721895:starRegistry
-----BEGIN SIGNATURE-----
1244UFxySQF5M3UHHp7cyBgqnkS3z7BvUH
IMIWExOm3hfBRYcIJ9PxmKJtpNh3W4TyiX0Q9p8fFoasdvzVhEW+yethsTPTnIVSRURjsJMRxI7G0aZDQ2qaDFo=
-----END BITCOIN SIGNED MESSAGE-----