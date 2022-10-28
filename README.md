# xxtereshko-snippets

`cl`

```tsx
console.log("$1 =>", $1)
```

`rf`

```tsx
type Props = {}

export const $1 = ({}: Props) => {
  return $0
}
```

`rfe`

```tsx
type Props = {}

const $1 = ({}: Props) => {
  return $0
}

export default $1
```

`us`

```tsx
const [$1, set$1] = useState($2)
```

`ue`

```tsx
useEffect(() => {
  $0
}, [$1])
```

`uer`

```tsx
useEffect(() => {
  $2

  return () => {
    $3
  }
}, [$1])
```

`ule`

```tsx
useLayoutEffect(() => {
  $2
}, [$1])
```

`uler`

```tsx
useLayoutEffect(() => {
  $2

  return () => {
    $3
  }
}, [$1])
```

`ha`

```tsx
const $1 = ($2) => {
  $0
}
```

`dob`

```tsx
const { $2 } = $1
```

`dar`

```tsx
const [$2] = $1
```

`sti`

```tsx
setInterval(() => {
  $2
}, $1)
```

`sto`

```tsx
setTimeout(() => {
  $2
}, $1)
```

Enjoy! ❤️
