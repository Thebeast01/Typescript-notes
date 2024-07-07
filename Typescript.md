# Typescript :

## Types of data types in typescript

1. number
2. string
3. boolean
4. any
5. undefined
6. tuple
7. void => it is void mean if something is void that mean
8. null

**Number :**
So in number type as the name suggest it stores numberical value

```javascript
let value: number = 44;
```

**String :** Use to store string

```javascript

        let name : string : 'Dholu';
```

**boolean:** It stores only ` true` or `false`

```javascript
let isAdult: boolean = true;
```

**tuple:** this is basically and array which can have element of multiple data type

```typescript
let data: [string, number, boolean] = ['Saif', 34, true];
// storing this kind of data is called tuple
```

## Type keyword

It help you to define the data type

```typescript
type User = {
	name: string;
	phone: number;
	email: string;
};
// Now we have create a User type which take the following data we can use it while defining any things
const userData: User = {
	name: 'Joe',
	phone: 3904303,
	email: 'joe@gmail.com',
};
```

Function in typescript

```typescript
const myfun = (n: number, m: number): number => {
	return n + m;
};
```
Other method
```typescript
type funcType = (n : number , m : number ) => number;

        // when we use funcType infront of the function
        const newfuction : funcType = (n , m )=> {
                return n + m ;
        }
```