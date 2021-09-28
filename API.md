# API Reference <a name="API Reference"></a>

## Constructs <a name="Constructs"></a>

### FlywayConstruct <a name="flywayProjenConstruct.FlywayConstruct"></a>

#### Initializers <a name="flywayProjenConstruct.FlywayConstruct.Initializer"></a>

```typescript
import { FlywayConstruct } from 'flywayProjenConstruct'

new FlywayConstruct(scope: Construct, id: string, VPC: Vpc, subnet: SubnetSelection, securityGroup: SecurityGroup, bucketName: string, url: string, user: string, password: string)
```

##### `scope`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.scope"></a>

- *Type:* [`@aws-cdk/core.Construct`](#@aws-cdk/core.Construct)

---

##### `id`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.id"></a>

- *Type:* `string`

---

##### `VPC`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.VPC"></a>

- *Type:* [`@aws-cdk/aws-ec2.Vpc`](#@aws-cdk/aws-ec2.Vpc)

---

##### `subnet`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.subnet"></a>

- *Type:* [`@aws-cdk/aws-ec2.SubnetSelection`](#@aws-cdk/aws-ec2.SubnetSelection)

---

##### `securityGroup`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.securityGroup"></a>

- *Type:* [`@aws-cdk/aws-ec2.SecurityGroup`](#@aws-cdk/aws-ec2.SecurityGroup)

---

##### `bucketName`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.bucketName"></a>

- *Type:* `string`

---

##### `url`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.url"></a>

- *Type:* `string`

---

##### `user`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.user"></a>

- *Type:* `string`

---

##### `password`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.parameter.password"></a>

- *Type:* `string`

---



#### Properties <a name="Properties"></a>

##### `flywayLambdaMigration`<sup>Required</sup> <a name="flywayProjenConstruct.FlywayConstruct.property.flywayLambdaMigration"></a>

```typescript
public readonly flywayLambdaMigration: Function;
```

- *Type:* [`@aws-cdk/aws-lambda.Function`](#@aws-cdk/aws-lambda.Function)

---





