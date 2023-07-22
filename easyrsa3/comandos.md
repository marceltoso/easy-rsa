###creacion de certificados vpn client#######
##https://docs.aws.amazon.com/vpn/latest/clientvpn-admin/mutual.html###
#aws acm import-certificate --certificate fileb://server.crt --private-key fileb://server.key #--certificate-chain fileb://ca.crt

#aws acm import-certificate --certificate fileb://client1.domain.tld.crt --private-key fileb://#client1.domain.tld.key --certificate-chain fileb://ca.crt