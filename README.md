# nephele

> Nephele (/ˈnɛfəliː/; Greek: Νεφέλη, from νέφος nephos "cloud") was a cloud nymph who figured prominently in the story of Phrixus and Helle.

## What is it ?

Nephele is a cloud cost api, which a statically generated, and served using Github Pages.

It consists on statically generated JSON files, that can be used as if it where a classical API,
but without the need to process the data for each request.

For example : 

```
curl https://nephele.gaia-app.io/aws/eu-west-1/ec2/t3.micro.json

{
  "provider": "aws",
  "region": "eu-west-1",
  "service": "ec2",
  "instanceType": "t3.micro",
  "onDemandPrice": 0.0114,
  "spotPrice": 0.0034
}
```
