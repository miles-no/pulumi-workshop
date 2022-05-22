# pulumi-workshop
Pulumi workshop til Camp Miles 

## Prerequisites

[Download & Install Pulumi](https://www.pulumi.com/docs/get-started/install/)

De forskjellige labbene har litt forskjellige prerequites
[Andre Prerequisites](https://github.com/pulumi/infrastructure-as-code-workshop/blob/master/00-installing-prerequisites.md)


## AWS - TypeScript

Prerequisites: Pulumi, Node.js, AWS CLI

[TypeScript på AWS](https://github.com/pulumi/infrastructure-as-code-workshop/blob/master/labs/aws/in-person/typescript/README.md)

### Credentials

Dere får utdelt tilgang tilgang til AWS underveis.
For å autentisere med AWS kan du kjøre kommandoen `aws configure` (etter at CLI'et er installert):

```
$ aws configure
AWS Access Key ID [None]: <my access key id>
AWS Secret Access Key [None]: <my secret access key>
Default region name [None]: eu-north-1
Default output format [None]: json
```

Merk at region må settes til `eu-north-1`.

Verifiser så at tilgangene er på plass:
```
$ aws sts get-caller-identity
{
    "Account": "278642226010", 
    "UserId": "<my access key id>", 
    "Arn": "arn:aws:iam::278642226010:user/<my username>"
}
```


## Azure - C#

Noen av dere har MSDN-abonnement som også gir deg gratis credits i Azure. Hvis du har dette, og ennå ikke har aktivert dette, så kan det gjøres på: [my.visualstudio.com](https://my.visualstudio.com)

Dersom du ikke har MSDN, kan du registrere deg for et gratis prøveabonnement her: [Azure trial](https://azure.microsoft.com/nb-no/free/)


Prerequisites: Pulumi, dotnet (6), Azure CLI

[C# på Azure](https://github.com/pulumi/infrastructure-as-code-workshop/blob/master/labs/azure/csharp/README.md)

##  Jeg er ferdig før tiden, hva nå?

Dersom du blir ferdig før tiden, kan f.eks.:

* Gjøre AWS-workshop hvis du er ferdig med Azure, og vica versa
* Prøv å deploy og lek deg med et større eksempel fra Pulumis How-To bibliotek: [AWS](https://www.pulumi.com/registry/packages/aws/how-to-guides/) [Azure](https://www.pulumi.com/registry/packages/azure-native/how-to-guides/)
* Velge du kan velge en annen kombinasjon av sky/programmeringsspråk: (https://github.com/pulumi/infrastructure-as-code-workshop)

* Hjelpe en kollega på workshoppen :)
* Lese deg opp på litt teori fra Ressursene under.
* Eksperimentere eller leke deg med andre tjenester i det du har jobbet med allerede.


# Ressurser

- [Pulumi arkitektur og konsepter](https://www.pulumi.com/docs/intro/concepts/)
- [Pulumi CLI (kommandoer)](https://www.pulumi.com/docs/reference/cli/)
- [Pulumi SDK referanser](https://www.pulumi.com/docs/reference/pulumi-sdk/)
- [AWS API Docs](https://www.pulumi.com/registry/packages/aws/)
- [Azure in the Pulumi registry](https://www.pulumi.com/registry/packages/azure-native/)
- [Azure API Docs](https://www.pulumi.com/registry/packages/azure-native/api-docs/)
