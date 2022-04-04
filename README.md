# zora-subgraph

https://thegraph.com/hosted-service/subgraph/goravsoni/zora-subgraph

```
{
  tokens(first: 5) {
    id
    tokenID
    contentURI
    metadataURI
  }
  users(first: 5) {
    id
    tokens {
      id
    }
    created {
      id
    }
  }
}
```

## Response
```
{
  "data": {
    "tokens": [
      {
        "id": "0",
        "tokenID": "0",
        "contentURI": "https://ipfs.fleek.co/ipfs/bafybeifyqibqlheu7ij7fwdex4y2pw2wo7eaw2z6lec5zhbxu3cvxul6h4",
        "metadataURI": "https://ipfs.fleek.co/ipfs/bafybeifpxcq2hhbzuy2ich3duh7cjk4zk4czjl6ufbpmxep247ugwzsny4"
      },
      {
        "id": "1",
        "tokenID": "1",
        "contentURI": "https://ipfs.fleek.co/ipfs/bafybeickkbbjtoc3qpwpjxyzuiapwky52tfynnvy5c3u6dnr375a4ys3vu",
        "metadataURI": "https://ipfs.fleek.co/ipfs/bafybeifpxcq2hhbzuy2ich3duh7cjk4zk4czjl6ufbpmxep247ugwzsny4"
      },
      {
        "id": "10",
        "tokenID": "10",
        "contentURI": "https://ipfs.fleek.co/ipfs/bafkreiay77d2mfmrpy6blg4mvfwvksrzarxjwyrshbmo6orgujncuggn4i",
        "metadataURI": "https://ipfs.fleek.co/ipfs/bafkreifsl22yu5rueee5op63zwszx776x52asxbezcqa5euz32zmstyh5m"
      },
      {
        "id": "100",
        "tokenID": "100",
        "contentURI": "https://ipfs.fleek.co/ipfs/bafkreic4zqxiofoxuf6dcefp4n5ykynyjncq3ohpz4mh3edet4qseaifb4",
        "metadataURI": "https://ipfs.fleek.co/ipfs/bafkreic364j5bx3tai5esijlnicpssmmudqlo4nwz5reftkpz6w2qrdhym"
      },
      {
        "id": "1000",
        "tokenID": "1000",
        "contentURI": "https://ipfs.fleek.co/ipfs/bafybeic4inyvegt6iyhvojuiy2ymxuawyxn2unmcdd2j3t64ktdsz2an2m",
        "metadataURI": "https://ipfs.fleek.co/ipfs/bafybeiclcorjknoyfc3vwvqk63nk3jhpfxzilrkqhsnvvvwooo7dotcopq"
      }
    ],
    "users": [
      {
        "id": "0x0000000000000000000000000000000000000000",
        "tokens": [
          {
            "id": "1012"
          },
          {
            "id": "1013"
          },
          {
            "id": "1014"
          },
          {
            "id": "1031"
          },
          {
            "id": "1081"
          },
          {
            "id": "1103"
          },
          {
            "id": "1109"
          },
          {
            "id": "1132"
          },
          {
            "id": "1142"
          },
          {
            "id": "1143"
          },
          {
            "id": "1158"
          },
          {
            "id": "1207"
          },
          {
            "id": "1209"
          },
          {
            "id": "1210"
          },
          {
            "id": "1220"
          },
          {
            "id": "1222"
          },
          {
            "id": "1246"
          },
          {
            "id": "1257"
          },
          {
            "id": "1326"
          },
          {
            "id": "1327"
          },
          {
            "id": "1348"
          },
          {
            "id": "1349"
          },
          {
            "id": "1350"
          },
          {
            "id": "1357"
          },
          {
            "id": "1367"
          },
          {
            "id": "1378"
          },
          {
            "id": "1379"
          },
          {
            "id": "1414"
          },
          {
            "id": "1417"
          },
          {
            "id": "1425"
          },
          {
            "id": "1448"
          },
          {
            "id": "1450"
          },
          {
            "id": "1497"
          },
          {
            "id": "1534"
          },
          {
            "id": "1574"
          },
          {
            "id": "1575"
          },
          {
            "id": "1586"
          },
          {
            "id": "1589"
          },
          {
            "id": "160"
          },
          {
            "id": "1622"
          },
          {
            "id": "1669"
          },
          {
            "id": "1684"
          },
          {
            "id": "1693"
          },
          {
            "id": "1733"
          },
          {
            "id": "1749"
          },
          {
            "id": "1760"
          },
          {
            "id": "1767"
          },
          {
            "id": "1796"
          },
          {
            "id": "1799"
          },
          {
            "id": "182"
          },
          {
            "id": "1839"
          },
          {
            "id": "185"
          },
          {
            "id": "1860"
          },
          {
            "id": "1864"
          },
          {
            "id": "1912"
          },
          {
            "id": "1915"
          },
          {
            "id": "1916"
          },
          {
            "id": "193"
          },
          {
            "id": "1930"
          },
          {
            "id": "1954"
          },
          {
            "id": "1955"
          },
          {
            "id": "2003"
          },
          {
            "id": "2008"
          },
          {
            "id": "2025"
          },
          {
            "id": "2027"
          },
          {
            "id": "2052"
          },
          {
            "id": "2099"
          },
          {
            "id": "2100"
          },
          {
            "id": "2118"
          },
          {
            "id": "2132"
          },
          {
            "id": "2135"
          },
          {
            "id": "2151"
          },
          {
            "id": "2159"
          },
          {
            "id": "2164"
          },
          {
            "id": "2213"
          },
          {
            "id": "2242"
          },
          {
            "id": "2262"
          },
          {
            "id": "2264"
          },
          {
            "id": "2266"
          },
          {
            "id": "2273"
          },
          {
            "id": "2278"
          },
          {
            "id": "2307"
          },
          {
            "id": "2382"
          },
          {
            "id": "2397"
          },
          {
            "id": "2412"
          },
          {
            "id": "2415"
          },
          {
            "id": "2469"
          },
          {
            "id": "2502"
          },
          {
            "id": "2505"
          },
          {
            "id": "2509"
          },
          {
            "id": "2524"
          },
          {
            "id": "254"
          },
          {
            "id": "2562"
          },
          {
            "id": "2582"
          },
          {
            "id": "2596"
          },
          {
            "id": "2606"
          },
          {
            "id": "2614"
          },
          {
            "id": "2639"
          },
          {
            "id": "267"
          },
          {
            "id": "2677"
          }
        ],
        "created": []
      },
      {
        "id": "0x000000000000000000000000000000000000dead",
        "tokens": [
          {
            "id": "1250"
          },
          {
            "id": "1577"
          },
          {
            "id": "1728"
          },
          {
            "id": "1874"
          },
          {
            "id": "2246"
          },
          {
            "id": "2578"
          },
          {
            "id": "3313"
          },
          {
            "id": "387"
          },
          {
            "id": "3999"
          },
          {
            "id": "4001"
          },
          {
            "id": "4853"
          },
          {
            "id": "5795"
          },
          {
            "id": "6882"
          },
          {
            "id": "7058"
          },
          {
            "id": "7059"
          },
          {
            "id": "7060"
          },
          {
            "id": "7061"
          },
          {
            "id": "7063"
          },
          {
            "id": "7179"
          },
          {
            "id": "7181"
          },
          {
            "id": "7560"
          }
        ],
        "created": []
      },
      {
        "id": "0x00055b597e0050405b27c90d21343b1eb5b74165",
        "tokens": [],
        "created": [
          {
            "id": "2394"
          },
          {
            "id": "2395"
          },
          {
            "id": "2396"
          }
        ]
      },
      {
        "id": "0x000ab07b26c48ef3caf9ec23520d86794c9fd74a",
        "tokens": [
          {
            "id": "5949"
          },
          {
            "id": "8288"
          }
        ],
        "created": []
      },
      {
        "id": "0x00164d5b44fc187ba9d8cfc6403b45510b7dbd82",
        "tokens": [],
        "created": [
          {
            "id": "8346"
          }
        ]
      }
    ]
  }
}
````
