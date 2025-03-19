[**schnur**](README.md)

***

[schnur](README.md) / Schnur

# Class: `abstract` Schnur\<TResult\>

Defined in: [schnur.ts:22](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L22)

Base class for schnur-based parsers

## Type Parameters

### TResult

`TResult` *extends* `any` = `any`

## Constructors

### new Schnur()

> **new Schnur**\<`TResult`\>(): `Schnur`\<`TResult`\>

Defined in: [schnur.ts:285](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L285)

#### Returns

`Schnur`\<`TResult`\>

## Properties

### #content

> `private` **#content**: `SchnurContent`

Defined in: [schnur.ts:278](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L278)

***

### #depends

> `private` **#depends**: [`SchnurDepends`](type-aliases\SchnurDepends.md)

Defined in: [schnur.ts:283](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L283)

***

### #handler

> `private` **#handler**: `SchnurHandler`

Defined in: [schnur.ts:280](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L280)

***

### #identity

> `private` **#identity**: `string`

Defined in: [schnur.ts:277](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L277)

***

### #markers

> `private` **#markers**: `SchnurMarkers`

Defined in: [schnur.ts:282](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L282)

***

### #modeler

> `private` **#modeler**: `SchnurModeler`

Defined in: [schnur.ts:279](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L279)

***

### #preheat

> `private` **#preheat**: `SchnurPreheat`

Defined in: [schnur.ts:281](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L281)

## Accessors

### content

#### Get Signature

> **get** **content**(): `SchnurContent`

Defined in: [schnur.ts:36](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L36)

##### Returns

`SchnurContent`

***

### depends

#### Get Signature

> **get** **depends**(): [`SchnurDepends`](type-aliases\SchnurDepends.md)

Defined in: [schnur.ts:73](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L73)

##### Returns

[`SchnurDepends`](type-aliases\SchnurDepends.md)

***

### handler

#### Get Signature

> **get** **handler**(): `SchnurHandler`

Defined in: [schnur.ts:43](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L43)

##### Returns

`SchnurHandler`

***

### head

#### Get Signature

> **get** `abstract` **head**(): `string`

Defined in: [schnur.ts:204](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L204)

##### Returns

`string`

***

### identity

#### Get Signature

> **get** **identity**(): `string`

Defined in: [schnur.ts:27](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L27)

The schnur identity is constructed by combining the head values of all classes in its prototype chain.

##### Returns

`string`

***

### markers

#### Get Signature

> **get** **markers**(): `SchnurMarkers`

Defined in: [schnur.ts:59](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L59)

##### Returns

`SchnurMarkers`

***

### modeler

#### Get Signature

> **get** **modeler**(): `SchnurModeler`

Defined in: [schnur.ts:66](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L66)

##### Returns

`SchnurModeler`

***

### preheat

#### Get Signature

> **get** **preheat**(): `SchnurPreheat`

Defined in: [schnur.ts:52](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L52)

##### Returns

`SchnurPreheat`

## Methods

### claim()

> **claim**(`context`, `settings`): `SchnurClaim`

Defined in: [schnur.ts:133](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L133)

#### Parameters

##### context

`SchnurContext`

##### settings

`SchnurClaimSettings`

#### Returns

`SchnurClaim`

***

### conclude()

> **conclude**(`context`, `settings`): `SchnurConclude`

Defined in: [schnur.ts:173](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L173)

#### Parameters

##### context

`SchnurContext`

##### settings

`SchnurConcludeSettings`

#### Returns

`SchnurConclude`

***

### doContent()

> `private` **doContent**(): `SchnurContent`

Defined in: [schnur.ts:306](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L306)

#### Returns

`SchnurContent`

***

### doDepends()

> `private` **doDepends**(): [`SchnurDepends`](type-aliases\SchnurDepends.md)

Defined in: [schnur.ts:336](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L336)

#### Returns

[`SchnurDepends`](type-aliases\SchnurDepends.md)

***

### doHandler()

> `private` **doHandler**(): `SchnurHandler`

Defined in: [schnur.ts:310](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L310)

#### Returns

`SchnurHandler`

***

### doIdentity()

> `private` **doIdentity**(): `string`

Defined in: [schnur.ts:291](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L291)

#### Returns

`string`

***

### doMarkers()

> `private` **doMarkers**(): `SchnurMarkers`

Defined in: [schnur.ts:327](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L327)

#### Returns

`SchnurMarkers`

***

### doModeler()

> `private` **doModeler**(): `SchnurModeler`

Defined in: [schnur.ts:315](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L315)

#### Returns

`SchnurModeler`

***

### doPreheat()

> `private` **doPreheat**(): `SchnurPreheat`

Defined in: [schnur.ts:319](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L319)

#### Returns

`SchnurPreheat`

***

### evaluate()

> **evaluate**(`input`, `settings`): `SchnurProduct`\<`null` \| `NonNullable`\<`TResult`\>\>

Defined in: [schnur.ts:95](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L95)

#### Parameters

##### input

`string`

##### settings

[`SchnurSettings`](type-aliases\SchnurSettings.md) = `{}`

#### Returns

`SchnurProduct`\<`null` \| `NonNullable`\<`TResult`\>\>

***

### onAdopt()?

> `optional` **onAdopt**(`process`): `void`

Defined in: [schnur.ts:221](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L221)

#### Parameters

##### process

`SchnurProcess`

#### Returns

`void`

***

### onBegin()?

> `optional` **onBegin**(`process`): `void`

Defined in: [schnur.ts:213](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L213)

#### Parameters

##### process

`SchnurProcess`

#### Returns

`void`

***

### onComplete()?

> `optional` **onComplete**(`process`): `void`

Defined in: [schnur.ts:228](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L228)

#### Parameters

##### process

`SchnurProcess`

#### Returns

`void`

***

### onProduct()?

> `optional` **onProduct**(`process`): `TResult`

Defined in: [schnur.ts:235](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L235)

#### Parameters

##### process

`SchnurProcess`

#### Returns

`TResult`

***

### use()

> **use**(`context`, `claim`?): `SchnurScope`

Defined in: [schnur.ts:114](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L114)

#### Parameters

##### context

`SchnurContext`

##### claim?

`SchnurClaim`

#### Returns

`SchnurScope`

***

### warmup()

> **warmup**(): `void`

Defined in: [schnur.ts:82](https://github.com/bimandev/schnur.js/blob/735c3129c86254d7a740d1915e6b3d7d995a68a4/lib/schnur.ts#L82)

#### Returns

`void`
