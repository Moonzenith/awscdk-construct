# API Reference <a name="API Reference" id="api-reference"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### WebAppConstruct <a name="WebAppConstruct" id="awscdk-construct.WebAppConstruct"></a>

#### Initializers <a name="Initializers" id="awscdk-construct.WebAppConstruct.Initializer"></a>

```typescript
import { WebAppConstruct } from 'awscdk-construct'

new WebAppConstruct(scope: Construct, id: string)
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#awscdk-construct.WebAppConstruct.Initializer.parameter.scope">scope</a></code> | <code>constructs.Construct</code> | *No description.* |
| <code><a href="#awscdk-construct.WebAppConstruct.Initializer.parameter.id">id</a></code> | <code>string</code> | *No description.* |

---

##### `scope`<sup>Required</sup> <a name="scope" id="awscdk-construct.WebAppConstruct.Initializer.parameter.scope"></a>

- *Type:* constructs.Construct

---

##### `id`<sup>Required</sup> <a name="id" id="awscdk-construct.WebAppConstruct.Initializer.parameter.id"></a>

- *Type:* string

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#awscdk-construct.WebAppConstruct.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#awscdk-construct.WebAppConstruct.addAssets">addAssets</a></code> | *No description.* |
| <code><a href="#awscdk-construct.WebAppConstruct.run">run</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="awscdk-construct.WebAppConstruct.toString"></a>

```typescript
public toString(): string
```

Returns a string representation of this construct.

##### `addAssets` <a name="addAssets" id="awscdk-construct.WebAppConstruct.addAssets"></a>

```typescript
public addAssets(path: string, destinationPath?: string): WebAppConstruct
```

###### `path`<sup>Required</sup> <a name="path" id="awscdk-construct.WebAppConstruct.addAssets.parameter.path"></a>

- *Type:* string

---

###### `destinationPath`<sup>Optional</sup> <a name="destinationPath" id="awscdk-construct.WebAppConstruct.addAssets.parameter.destinationPath"></a>

- *Type:* string

---

##### `run` <a name="run" id="awscdk-construct.WebAppConstruct.run"></a>

```typescript
public run(path: string, commands: string | string[]): WebAppConstruct
```

###### `path`<sup>Required</sup> <a name="path" id="awscdk-construct.WebAppConstruct.run.parameter.path"></a>

- *Type:* string

---

###### `commands`<sup>Required</sup> <a name="commands" id="awscdk-construct.WebAppConstruct.run.parameter.commands"></a>

- *Type:* string | string[]

---

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#awscdk-construct.WebAppConstruct.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |

---

##### ~~`isConstruct`~~ <a name="isConstruct" id="awscdk-construct.WebAppConstruct.isConstruct"></a>

```typescript
import { WebAppConstruct } from 'awscdk-construct'

WebAppConstruct.isConstruct(x: any)
```

Checks if `x` is a construct.

###### `x`<sup>Required</sup> <a name="x" id="awscdk-construct.WebAppConstruct.isConstruct.parameter.x"></a>

- *Type:* any

Any object.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#awscdk-construct.WebAppConstruct.property.node">node</a></code> | <code>constructs.Node</code> | The tree node. |
| <code><a href="#awscdk-construct.WebAppConstruct.property.webappBucket">webappBucket</a></code> | <code>aws-cdk-lib.aws_s3.Bucket</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="awscdk-construct.WebAppConstruct.property.node"></a>

```typescript
public readonly node: Node;
```

- *Type:* constructs.Node

The tree node.

---

##### `webappBucket`<sup>Required</sup> <a name="webappBucket" id="awscdk-construct.WebAppConstruct.property.webappBucket"></a>

```typescript
public readonly webappBucket: Bucket;
```

- *Type:* aws-cdk-lib.aws_s3.Bucket

---



## Classes <a name="Classes" id="Classes"></a>

### Hello <a name="Hello" id="awscdk-construct.Hello"></a>

#### Initializers <a name="Initializers" id="awscdk-construct.Hello.Initializer"></a>

```typescript
import { Hello } from 'awscdk-construct'

new Hello()
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#awscdk-construct.Hello.sayHello">sayHello</a></code> | *No description.* |

---

##### `sayHello` <a name="sayHello" id="awscdk-construct.Hello.sayHello"></a>

```typescript
public sayHello(): string
```





